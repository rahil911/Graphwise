# Timeline & Milestones
## 20-Week Execution Roadmap for Graphwise Benchmarking Study

**Project**: GW-001

**Duration**: 20 weeks (5 months)

**Start Date**: TBD (aligned with Graphwise FY2026 planning)

**Team**: University of Washington MSIM

**Version**: 1.0

---

## Executive Timeline Overview

```
PHASE 1: Discovery         PHASE 2: Benchmarking      PHASE 3: Analysis         PHASE 4: Publication
Weeks 1-4                  Weeks 5-14                 Weeks 15-18               Weeks 19-20
├─ Literature Review       ├─ Methodology Design      ├─ Statistical Analysis   ├─ Paper Drafting
├─ Requirements           ├─ Infrastructure Setup    ├─ Competitive Evaluation ├─ Final Review
└─ Methodology Document    ├─ Performance Testing     ├─ Visualization         └─ Submission
                          ├─ GraphRAG Evaluation     └─ Findings Synthesis
                          └─ TCO Data Collection
```

**Critical Path**: Weeks 9-14 (Benchmarking Execution) depend on Weeks 5-8 (Methodology Design)
**Key Milestones**: Week 6 (Methodology Review), Week 12 (Interim Results), Week 20 (Final Delivery)

---

## Phase 1: Discovery & Literature Review (Weeks 1-4)

### Phase Owner: Rahil M. Harihar (Research Lead & PM)

### Week 1-2: Literature Review & Competitive Landscape

**Primary Activities**:
- **Rahil**: Survey existing benchmarks (LDBC SNB, SPARQL Performance Benchmark, BSBM, LUBM, Wikidata)
- **Siddarth**: Deep-dive into data.world study methodology (arXiv:2311.07509)
- **Mathew**: Research big data benchmarking standards (TPC-H, TPC-DS)
- **Shreyas**: Competitive intelligence gathering (Graphwise, Stardog, Neo4j, AWS Neptune, Franz Inc., Fluree)

**Deliverables**:
- Annotated bibliography (50+ sources: academic papers, vendor whitepapers, industry reports)
- Research gap analysis: What's missing from current benchmarking landscape?
- Initial hypothesis: RDF reasoning vs. property graph traversal performance trade-offs

**Tools**: Zotero (reference management), Notion (collaborative notes), Miro (gap analysis visualization)

**Stakeholder Engagement**:
- Kickoff meeting with Graphwise technical SMEs (Week 1, Day 3)
- NDA execution and platform access provisioning discussion

---

### Week 3-4: Requirements Gathering & Use Case Definition

**Primary Activities**:
- **Rahil**: Interview Graphwise stakeholders
  - What competitive questions need answering for FY2026 planning?
  - Which use cases are highest priority? (Life sciences vs. publishing vs. Customer 360)
  - What metrics matter most for enterprise procurement decisions?
- **Siddarth**: Define technical evaluation criteria
  - Query performance dimensions (simple, complex, reasoning-required)
  - Scalability metrics (scale factors SF1 to SF1000)
  - GraphRAG-specific metrics (LLM accuracy, hallucination rates)
- **Mathew**: Infrastructure requirements analysis
  - Cloud platform selection (AWS recommended for consistency)
  - Instance types and configurations for fair comparison
  - Budget estimation for 6 platforms × 3 scale factors
- **Shreyas**: KPI framework design
  - Enterprise decision criteria mapping
  - TCO analysis components (infrastructure, licensing, development time)

**Deliverables**:
- Requirements document (15-20 pages) outlining:
  - Research questions (5-7 core questions)
  - Use case scenarios (3 priority domains)
  - Success metrics for benchmarking study
- Graphwise stakeholder sign-off on scope and priorities

**Milestone Review** (End of Week 4):
- **Attendees**: Rahil (presenter), Graphwise technical SME, UW faculty advisor (optional)
- **Agenda**: Present research questions, use cases, evaluation criteria
- **Success Criteria**: Graphwise approval to proceed to methodology design

---

## Phase 2: Benchmarking Design & Execution (Weeks 5-14)

### Weeks 5-6: Methodology Design

**Phase Owner**: Siddarth Bhave (Technical Architect)
**Support**: Rahil (research methodology), Mathew (statistical design), Shreyas (comparative framework)

**Primary Activities**:
- **Siddarth**: Design query suites
  - 50 representative queries per use case (life sciences, publishing, Customer 360)
  - SPARQL, Cypher, and Gremlin equivalents
  - Complexity levels: simple (1-2 triple patterns), medium (3-5), complex (6+ with reasoning)
- **Mathew**: Statistical analysis plan
  - Sample size calculation (power analysis for 95% CI)
  - Significance testing approach (t-tests, ANOVA, post-hoc corrections)
  - Outlier detection and removal procedures
- **Shreyas**: Comparative evaluation framework
  - Feature comparison matrix (RDF vs. property graph capabilities)
  - Use case fit decision tree
  - TCO model structure (Year 1 implementation, Years 2-3 ongoing costs)

**Independent Review**:
- External validation by 2 graph database experts (academic or industry)
- Fairness check: Are queries optimally written for each platform?
- Bias detection: Any unintentional advantages for specific vendors?

**Deliverables**:
- 30-page benchmark specification document:
  - Research methodology (inspired by data.world, LDBC standards)
  - Query suite with equivalence validation
  - Statistical analysis plan with power calculations
  - Infrastructure setup procedures
- UW faculty advisor approval (Week 6, Day 5)

**Milestone Review** (End of Week 6):
- **Attendees**: Full team, Graphwise technical SME, UW faculty advisor
- **Agenda**: Methodology walkthrough, query suite review, fairness validation
- **Success Criteria**: Approval to proceed with infrastructure setup and benchmarking

---

### Weeks 7-8: Platform Selection & Configuration

**Phase Owner**: Mathew Jerry Meleth (Data Engineering Lead)
**Support**: Siddarth (technical configuration), Shreyas (vendor coordination)

**Primary Activities**:
- **Mathew**: AWS infrastructure provisioning
  - Set up VPC with isolated subnets for each platform
  - Provision r5.2xlarge instances (8 vCPUs, 64GB RAM, SSD storage)
  - Configure CloudWatch monitoring and logging
- **Siddarth**: Platform installations
  - Graphwise GraphDB 11 Enterprise (latest with GraphRAG support)
  - Stardog Enterprise (latest version)
  - Franz Inc. AllegroGraph (latest with neuro-symbolic AI)
  - AWS Neptune (RDF mode, property graph mode, Neptune Analytics)
  - Neo4j Aura Enterprise or self-managed on AWS
  - TigerGraph Cloud or AWS deployment
- **Shreyas**: Vendor coordination
  - Request academic licenses or free trials
  - Coordinate with Enterprise Knowledge for platform access if needed
  - Document configuration settings for replicability

**Data Generation**:
- **Mathew**: Create synthetic datasets at multiple scale factors
  - SF1: 1M triples/nodes (baseline)
  - SF10: 10M (medium scale)
  - SF100: 100M (enterprise scale)
- Based on real-world ontologies: Dublin Core (publishing), Gene Ontology (life sciences), Customer 360 schema

**Deliverables**:
- 6 fully configured platforms with identical hardware
- Dataset generators (Python scripts) for SF1, SF10, SF100
- Infrastructure documentation (runbook for replication)

---

### Weeks 9-10: Data Loading & Validation

**Phase Owner**: Mathew Jerry Meleth
**Support**: Siddarth (performance monitoring), Shreyas (data quality validation)

**Primary Activities**:
- **Mathew**: Bulk data loading
  - Load SF1 dataset into all 6 platforms
  - Measure load time (triples/second or nodes/second)
  - Validate data integrity (record counts, relationship validation)
- **Siddarth**: Index creation and optimization
  - Configure platform-specific indexes
  - Measure index build time
  - Validate query plan optimization (EXPLAIN queries)
- **Shreyas**: Data quality checks
  - Verify entity counts match across platforms
  - Validate relationship cardinality
  - Check for data corruption or loading errors

**Warm-Up Testing**:
- Run each of 50 queries 10 times to populate caches
- Identify and fix any query syntax errors or platform-specific issues
- Baseline performance profiling

**Deliverables**:
- All 6 platforms loaded with SF1 dataset
- Data loading performance report (load time, index build time)
- Query validation report (all 50 queries execute successfully on all platforms)

---

### Weeks 11-12: Performance Benchmarking

**Phase Owner**: Siddarth Bhave & Mathew Jerry Meleth (Joint)
**Support**: Shreyas (monitoring and logging)

**Primary Activities**:
- **Automated Test Execution**:
  - 100 runs per query × 50 queries × 6 platforms = **30,000 test runs**
  - Collect metrics: latency (min, median, p95, p99, max), throughput, CPU/memory utilization
  - Randomize query execution order to avoid cache bias

- **Concurrency Testing**:
  - Gradual client ramp-up: 1 → 10 → 50 → 100 simultaneous clients
  - Measure throughput degradation and latency increase under load
  - Identify concurrency bottlenecks

- **Scalability Testing**:
  - Repeat performance tests at SF10 and SF100 (if time/budget allows)
  - Measure scaling efficiency: Does performance degrade linearly or worse?

- **Reasoning Validation** (RDF-only):
  - Graphwise, Stardog, Franz Inc.: Test RDFS++ and OWL 2 RL inference
  - Measure inference time (materialization vs. query-time)
  - Verify correctness of inferred triples

**Data Collection Infrastructure**:
- Python scripts with Pandas for automated metric collection
- Store results in structured format (JSON or CSV)
- Real-time monitoring dashboards (Grafana + Prometheus)

**Deliverables**:
- Raw performance dataset: 30,000 test runs with complete metrics
- Concurrency test results
- Scaling analysis (SF1 vs. SF10 performance comparison)

**Milestone Review** (End of Week 12):
- **Attendees**: Full team presents interim results to Graphwise
- **Agenda**: Preliminary performance findings, early insights, any surprises
- **Success Criteria**: Graphwise feedback incorporated into remaining tests

---

### Week 13: GraphRAG Evaluation

**Phase Owner**: Siddarth Bhave (LLM integration)
**Support**: Rahil (LLM prompt engineering), Mathew (data pipeline), Shreyas (validation coordination)

**Primary Activities**:
- **LLM Integration Setup**:
  - Configure API access: GPT-4, Claude 3.5 Sonnet
  - Implement GraphRAG adapters for each platform:
    - Graphwise: SPARQL query generation + OWL reasoning
    - Neo4j: Cypher query generation + graph algorithms
    - AWS Neptune: SPARQL/Gremlin on OneGraph model

- **Test Query Execution** (Pharmaceutical R&D scenario):
  - 50 questions × 6 configurations = 300 LLM queries
  - Configurations:
    1. Baseline (direct LLM, no graph)
    2. Vector RAG (embeddings only)
    3. GraphRAG (Graphwise)
    4. GraphRAG (Neo4j)
    5. GraphRAG (AWS Neptune)
    6. Hybrid (graph + vector)

- **Domain Expert Validation**:
  - **Shreyas**: Coordinate with 3 pharmaceutical researchers
  - Each expert independently validates answers
  - Inter-rater agreement calculation (Fleiss' kappa)
  - Dispute resolution for disagreements

**Metrics Collected**:
- Accuracy (% correct answers)
- Multi-hop reasoning success rate (queries requiring 3+ relationship traversals)
- Hallucination rate (% responses with false information)
- Explainability score (1-5 scale based on reasoning chain visibility)
- Cost per query (LLM tokens + graph query cost)
- Latency (p50, p95, p99)

**Deliverables**:
- GraphRAG evaluation dataset with domain expert validation
- LLM accuracy comparison across platforms
- Hallucination rate analysis

---

### Week 14: TCO Data Collection & Analysis

**Phase Owner**: Shreyas B Subramanya (Operations & TCO Lead)
**Support**: Mathew (infrastructure cost tracking), Rahil (development time estimation)

**Primary Activities**:
- **Infrastructure Cost Analysis**:
  - AWS bills for all 6 platforms (compute, storage, data transfer)
  - Licensing fees (Graphwise, Stardog, Neo4j, Franz Inc.)
  - Normalize to 3-year TCO model

- **Development Time Tracking**:
  - Log hours spent: ontology engineering (RDF) vs. schema design (property graphs)
  - Query development time: SPARQL vs. Cypher complexity
  - Integration effort: connector setup, ETL development

- **Training Requirements**:
  - Estimate learning curve: SPARQL vs. Cypher for developers unfamiliar with graph technologies
  - Training material availability and quality assessment

- **TCO Model Construction**:
  - Year 1: Implementation costs (ontology, migration, training)
  - Years 2-3: Ongoing costs (licensing, infrastructure, maintenance)
  - Break-even analysis: When does RDF semantic value justify complexity premium?

**Deliverables**:
- 3-year TCO comparison table (6 platforms)
- Break-even analysis and sensitivity scenarios
- Cost-performance trade-off visualization

---

## Phase 3: Analysis & Synthesis (Weeks 15-18)

### Weeks 15-16: Statistical Analysis & Key Findings

**Phase Owner**: Mathew Jerry Meleth (Data Analytics Lead)
**Support**: Shreyas (visualization), Siddarth (technical interpretation)

**Primary Activities**:
- **Statistical Testing**:
  - Pairwise comparisons (t-tests): Graphwise vs. each competitor for query performance
  - ANOVA: Overall performance differences across all platforms
  - Post-hoc corrections (Bonferroni) for multiple comparisons
  - Effect size calculation (Cohen's d) to quantify practical significance

- **Confidence Intervals**:
  - 95% CI for median latency, p95 latency, throughput metrics
  - Visualize uncertainty ranges (error bars on charts)

- **Outlier Analysis**:
  - Identify and investigate anomalies (e.g., one platform 10x slower on specific query type)
  - Validate outliers are real performance issues, not measurement errors

- **Key Findings Identification**:
  - "Graphwise reasoning queries 45% faster than Stardog for OWL inference"
  - "Neo4j traversal performance 30% better than RDF platforms for simple lookups"
  - "GraphRAG with Graphwise achieves 82% LLM accuracy vs. 54% baseline"

**Deliverables**:
- Statistical analysis report with significance test results
- Key findings summary (10-15 top insights)
- Detailed statistical tables for paper appendices

---

### Week 17: Competitive Platform Analysis & Use Case Fit

**Phase Owner**: Shreyas B Subramanya (Competitive Analysis Lead)
**Support**: Rahil (strategic interpretation), Siddarth (technical validation)

**Primary Activities**:
- **Platform-by-Platform Comparison**:
  - **Graphwise GraphDB**: Strengths (reasoning, W3C standards, GraphRAG), weaknesses (SPARQL learning curve)
  - **Stardog**: Strengths (virtualization, ontology mgmt), weaknesses (enterprise pricing)
  - **Franz Inc. AllegroGraph**: Strengths (neuro-symbolic AI, scale), weaknesses (less visible GraphRAG integration)
  - **AWS Neptune**: Strengths (managed service, OneGraph model), weaknesses (limited reasoning vs. dedicated RDF engines)
  - **Neo4j**: Strengths (developer experience, Cypher), weaknesses (limited semantic reasoning)
  - **TigerGraph**: Strengths (real-time analytics), weaknesses (less emphasis on semantic standards)

- **Use Case Fit Decision Tree**:
  - **When to choose Graphwise**: Regulatory compliance, semantic integration, GraphRAG for LLMs, ontology reuse critical
  - **When to choose Neo4j**: Real-time recommendations, fraud detection, developer velocity priority
  - **When to choose AWS Neptune**: Existing AWS commitment, hybrid RDF + property graph needs

- **Feature Comparison Matrix**:
  - Standards compliance, reasoning capabilities, query performance, scalability, TCO
  - Color-coded heatmap: Green (strong), Yellow (adequate), Red (weak)

**Deliverables**:
- Competitive intelligence report (20-25 pages)
- Use case fit decision tree (visual diagram)
- Feature comparison matrix (Excel + Power BI dashboard)

---

### Week 18: Visualization & Dashboard Design

**Phase Owner**: Shreyas B Subramanya & Mathew Jerry Meleth (Joint)
**Support**: Rahil (narrative framing)

**Primary Activities**:
- **Academic Paper Visualizations**:
  - Performance comparison bar charts (median latency by query complexity)
  - Scalability curves (latency vs. dataset size: SF1, SF10, SF100)
  - GraphRAG accuracy comparison (grouped bar chart: 6 configurations)
  - TCO comparison (3-year stacked bar chart: infrastructure + licensing + development)

- **Interactive Dashboards** (Power BI / Tableau):
  - Drill-down capability: Overall performance → specific query types → individual queries
  - Filters: Platform, use case, complexity level
  - Heatmaps: Performance across platforms × query types

- **Sales Enablement Materials**:
  - One-page scorecards for each platform
  - Decision tree flowchart (printable PDF)
  - Executive summary infographics

**Deliverables**:
- 15-20 publication-quality charts for academic paper
- Interactive Power BI dashboard (for Graphwise internal use)
- Sales enablement one-pagers (PDF)

---

## Phase 4: Paper Writing & Publication (Weeks 19-20)

### Week 19: Academic Paper Drafting

**Phase Owner**: Siddarth Bhave (Technical Writing Lead)
**Support**: All team members (section authors)

**Primary Activities**:
- **Siddarth**: Methodology section (10-12 pages)
  - Research design, query suite description, equivalence validation
  - Platform configurations, infrastructure setup
  - Statistical analysis plan
  - Replication procedures

- **Siddarth**: Results section (8-10 pages)
  - Performance benchmark findings (tables + charts)
  - GraphRAG evaluation results
  - Statistical significance testing outcomes
  - Key insights and patterns identified

- **Rahil**: Introduction & Discussion (8-10 pages)
  - Introduction: Research motivation, gap analysis, research questions
  - Discussion: Interpretation of findings, RDF vs. property graph trade-offs, use case recommendations
  - Limitations: Scope constraints, generalizability concerns

- **Rahil**: Conclusion (2-3 pages)
  - Summary of contributions
  - Implications for Graphwise positioning
  - Future work recommendations

- **Mathew**: Appendices & Supplementary Materials
  - Detailed statistical tables
  - Query suite (full SPARQL/Cypher/Gremlin code)
  - Dataset generation procedures

- **Shreyas**: Competitive Analysis section (5-7 pages)
  - Platform comparison discussion
  - Use case fit analysis integration

**Writing Standards**:
- ISWC or VLDB conference format (LaTeX template)
- Maximum 25-35 pages including references
- IEEE or ACM citation style

**Deliverables**:
- Complete draft academic paper (25-35 pages)
- Executive summary (8-10 pages) for Graphwise leadership

---

### Week 20: Final Review & Submission

**Phase Owner**: Rahil M. Harihar (Overall Project Lead)
**Support**: All team members (peer review)

**Primary Activities**:
- **Internal Peer Review**:
  - Each team member reviews all sections
  - Focus areas: clarity, technical accuracy, logical flow, citation completeness
  - Identify gaps or inconsistencies

- **External Review** (Optional):
  - UW faculty advisor technical review
  - Graphwise SME review for accuracy and relevance
  - Independent graph database expert (if available)

- **Final Edits**:
  - Incorporate review feedback
  - Proofreading and grammar check
  - Format to conference template standards
  - Validate all citations and references

- **Deliverable Packaging**:
  1. Academic paper (PDF, LaTeX source)
  2. Executive summary (PDF, PowerPoint version)
  3. GitHub repository: Benchmark suite (data generators, query suites, evaluation scripts, README)
  4. Supplementary materials (datasets, raw results, statistical analysis notebooks)

**Final Presentation** (Week 20, Day 5):
- **Attendees**: Full team, Graphwise executive team, UW faculty advisor
- **Format**: 60-minute presentation + 30-minute Q&A
- **Agenda**:
  - Research overview and methodology (Rahil, 10 min)
  - Key performance findings (Siddarth, 15 min)
  - GraphRAG evaluation results (Siddarth, 10 min)
  - Competitive analysis and use case fit (Shreyas, 10 min)
  - TCO and ROI implications (Mathew, 10 min)
  - Q&A and discussion (30 min)

**Success Criteria**:
- Graphwise executive approval of deliverables
- Commitment to co-author conference submission (if desired)
- Discussion of next steps: media strategy, sales enablement rollout

**Milestone**: Project Completion & Handoff

---

## Key Milestones Summary

| Week | Milestone | Deliverable | Owner | Review |
|------|-----------|-------------|-------|--------|
| **4** | **Discovery Complete** | Requirements document, research questions | Rahil | Graphwise SME |
| **6** | **Methodology Approved** | 30-page benchmark specification | Siddarth | UW faculty + Graphwise |
| **8** | **Infrastructure Ready** | 6 platforms configured, datasets loaded | Mathew | Internal team |
| **12** | **Interim Results** | Preliminary performance findings | Siddarth + Mathew | Graphwise (mid-project check-in) |
| **14** | **Benchmarking Complete** | Full dataset: performance + GraphRAG + TCO | All | Internal validation |
| **18** | **Analysis Complete** | Statistical findings, competitive analysis, visualizations | Mathew + Shreyas | Internal peer review |
| **20** | **Final Delivery** | Academic paper, executive summary, GitHub repo | Rahil | Graphwise executive presentation |

---

## Resource Allocation

### Time Commitment (per team member)

**Rahil M. Harihar**: ~300 hours (15 hrs/week × 20 weeks)
- Weeks 1-4: 20 hrs/week (discovery, requirements)
- Weeks 5-18: 12 hrs/week (project management, stakeholder communication)
- Weeks 19-20: 25 hrs/week (paper writing, final delivery)

**Siddarth Bhave**: ~350 hours (17.5 hrs/week × 20 weeks)
- Weeks 1-6: 15 hrs/week (literature review, methodology design)
- Weeks 9-14: 25 hrs/week (benchmarking execution - peak workload)
- Weeks 15-20: 18 hrs/week (analysis, technical writing)

**Mathew Jerry Meleth**: ~320 hours (16 hrs/week × 20 weeks)
- Weeks 7-10: 20 hrs/week (infrastructure setup, data loading)
- Weeks 11-12: 25 hrs/week (performance testing - peak workload)
- Weeks 15-16: 20 hrs/week (statistical analysis)
- Other weeks: 12-15 hrs/week

**Shreyas B Subramanya**: ~280 hours (14 hrs/week × 20 weeks)
- Weeks 1-8: 12 hrs/week (competitive research, TCO framework)
- Weeks 13-14: 18 hrs/week (GraphRAG validation, TCO analysis)
- Weeks 15-18: 18 hrs/week (competitive analysis, visualization)
- Other weeks: 10-12 hrs/week

**Total Team Effort**: ~1,250 hours (~7.8 person-months)

---

## Risk Management Timeline

**Week 2**: If KG API or platform access issues arise, pivot to alternative data sources
**Week 6**: Methodology review checkpoint - adjust scope if needed before infrastructure investment
**Week 12**: Interim results review - extend testing if results inconclusive
**Week 18**: Analysis deadline - if statistical significance weak, extend by 1 week
**Week 19**: Writing buffer - if drafting takes longer, compress review to Week 20 only

**Contingency Buffer**: Built-in 2-week slack across 20-week timeline (can extend to Week 22 if critical)

---

## Success Metrics Timeline

**Immediate (Week 20)**:
- Academic paper completed and approved by Graphwise
- Executive summary delivered for sales enablement
- GitHub benchmark suite published

**3 Months Post-Delivery**:
- Conference submission (ISWC, VLDB, WWW)
- 10+ sales conversations reference research
- 2+ media mentions (Database Trends, Big Data Wire)

**6 Months Post-Delivery**:
- Benchmark suite: 100+ GitHub stars, 20+ forks
- Conference acceptance (if submitted)
- Gartner or analyst citation

**12 Months Post-Delivery**:
- 20+ academic citations
- 2+ independent teams replicate benchmark
- Graphwise market positioning measurably improved

---

## Conclusion

This 20-week timeline delivers a comprehensive academic-quality benchmarking study through four carefully sequenced phases:

1. **Discovery** (Weeks 1-4): Research foundation and requirements
2. **Benchmarking** (Weeks 5-14): Methodology design, infrastructure setup, performance testing
3. **Analysis** (Weeks 15-18): Statistical analysis, competitive evaluation, visualization
4. **Publication** (Weeks 19-20): Paper writing, review, final delivery

**Team synergies** ensure efficient execution:
- Rahil orchestrates overall timeline and stakeholder communication
- Siddarth leads technical architecture and benchmarking
- Mathew manages data infrastructure and statistical analysis
- Shreyas handles competitive analysis and documentation

**Graphwise receives** actionable research by Week 20, aligned with FY2026 planning window, establishing thought leadership in the $48.4B semantic technologies market.

---

**Next Steps After Approval**:
1. Week 1, Day 1: Kickoff meeting and NDA execution
2. Week 1, Day 3: Platform access provisioning
3. Week 2, Day 1: Begin literature review
4. Weekly status updates to Graphwise (Fridays, 30-minute sync)
