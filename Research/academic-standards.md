# Academic Research Standards for Benchmarking Study

**Project**: Graphwise Semantic Layer Benchmarking Study

**Document Version**: 1.0

**Last Updated**: November 1, 2025

**Purpose**: Comprehensive guide to academic standards for creating publication-quality benchmarking research

---

## Executive Summary

This document provides comprehensive academic standards for creating a publication-quality benchmarking paper for Graphwise's semantic layer platform evaluation. Our goal is to produce research comparable to the data.world Knowledge Graph benchmark study (arXiv:2311.07509) that can be:

1. **Published** in academic venues (ISWC, ESWC, Semantic Web Journal)
2. **Cited** as authoritative industry research
3. **Replicated** by other researchers and practitioners
4. **Trusted** by the semantic technology community

### Key Takeaways

- **Target Quality**: Academic-quality benchmarking study with industry relevance
- **Primary Reference**: data.world KG benchmark paper (Sequeda et al., 2023)
- **Recommended Venues**: ISWC (conference), Semantic Web Journal, arXiv preprint
- **Timeline**: 4-6 months from experiment design to first draft
- **Critical Success Factors**: Reproducibility, statistical rigor, vendor neutrality, clear methodology

---

## Data.world Paper Analysis

### Paper Overview

**Title**: "A Benchmark to Understand the Role of Knowledge Graphs on Large Language Model's Accuracy for Question Answering on Enterprise SQL Databases"

**Authors**: Juan Sequeda, Dean T. Allemang, Bryon Jacob (data.world)
**Published**: November 2023, arXiv:2311.07509
**Conference**: GRADES-NDA 2023 (7th Joint Workshop on Graph Data Management)
**Pages**: 34 pages
**License**: Creative Commons BY 4.0

### Structure Breakdown

Based on analysis of similar benchmarking papers and workshop format:

1. **Abstract** (150-250 words)
   - Structured summary of problem, method, results, conclusions
   - Key finding highlighted: 16% accuracy (SQL) vs 54% accuracy (KG+SPARQL)

2. **Introduction**
   - Problem statement: LLM accuracy on enterprise databases
   - Motivation: Knowledge graphs as semantic layer
   - Research questions clearly stated (RQ1, RQ2)
   - Contribution: Benchmark framework and empirical results

3. **Background & Related Work**
   - LLMs for question answering
   - Knowledge graphs and semantic technologies
   - Previous benchmarking studies
   - Enterprise database challenges

4. **Methodology**
   - Research questions formulation
   - Benchmark structure: schema, queries, ontology
   - Experimental setup: GPT-4, insurance domain
   - Data collection process (Sept-Oct 2023)

5. **Experimental Setup**
   - 43 enterprise questions
   - SQL vs SPARQL comparison
   - 86 LLM calls, 172 query executions
   - Zero-shot prompting approach

6. **Results**
   - Four-part presentation: overall, question quadrant, partial accuracy, inaccurate results
   - Tables and figures showing comparative performance
   - Statistical analysis of accuracy metrics

7. **Discussion**
   - Interpretation of findings
   - Implications for enterprise knowledge graphs
   - Practical significance for industry

8. **Limitations**
   - Scope: Single domain (insurance)
   - Single LLM tested (GPT-4)
   - Question set size
   - Generalizability considerations

9. **Conclusion**
   - Summary of key findings
   - Contributions to field
   - Future work directions

10. **References**
    - Mix of academic papers and industry reports
    - Recent citations (2020-2023)
    - Foundational semantic web papers

### Writing Style

**Tone**:
- Formal academic language
- Technical precision in terminology
- Objective, evidence-based claims
- Balance between accessibility and rigor

**Key Characteristics**:
- **Declarative statements**: "Our results demonstrate..." not "We believe..."
- **Quantified claims**: All findings backed by specific numbers
- **Context provided**: Industry relevance explained for academic audience
- **Reproducible**: Sufficient detail for replication

### Statistical Rigor

**Metrics Used**:
- Accuracy percentages (primary metric)
- Categorical analysis (question quadrants)
- Partial vs. complete accuracy breakdown
- Comparative analysis (SQL vs. SPARQL)

**Presentation**:
- Clear baseline establishment (16% SQL accuracy)
- Improvement quantified (54% with KG, 238% relative improvement)
- Results categorized by question type
- Error analysis included

### Key Strengths

1. **Clear Research Questions**: RQ1 and RQ2 explicitly stated and answered
2. **Real Enterprise Data**: Insurance domain with actual business questions
3. **Transparent Methodology**: Data collection dates, question count, execution details
4. **Practical Relevance**: Bridges academic research and industry needs
5. **Reproducibility**: Benchmark framework can be replicated
6. **Open Access**: CC BY 4.0 license promotes community use
7. **Significant Findings**: 238% improvement is compelling result

### Lessons for Our Study

**What to Emulate**:
- Clear problem statement with industry relevance
- Structured research questions (RQ format)
- Transparent experimental setup
- Four-part results presentation
- Balance academic rigor with practical insights
- Open access publication

**How We'll Improve**:
- **Broader scope**: Multiple semantic platforms (not just one comparison)
- **Multiple domains**: Not limited to single industry
- **Diverse metrics**: Beyond accuracy - include performance, scalability, cost
- **Statistical testing**: Add significance tests, confidence intervals, effect sizes
- **More extensive benchmarks**: Leverage LDBC, BSBM, custom enterprise scenarios
- **Deeper vendor comparison**: Apples-to-apples methodology across platforms

---

## Target Publication Venues

### Recommended Primary Venues

#### 1. International Semantic Web Conference (ISWC)

**Overview**:
- Premier conference for semantic web, linked data, knowledge graphs
- Held annually (November typically)
- Proceedings published by Springer in LNCS series
- Strong peer review process

**Paper Format**:
- **Format**: Springer LNCS (Lecture Notes in Computer Science)
- **Page Limit**: 15 pages maximum (excluding references)
- **Template**: LaTeX or Word template provided
- **Review**: Double-blind peer review

**Timeline**:
- Abstract deadline: May (typically)
- Paper deadline: May-June
- Notification: August
- Camera-ready: September
- Conference: November

**Fit for Our Project**: ★★★★★
- Perfect audience: semantic technology researchers and practitioners
- Benchmark papers are valued (Resources Track)
- Industry collaboration welcomed
- High visibility in target community

**Acceptance Rate**: ~15-20% (competitive but achievable with quality work)

#### 2. Extended Semantic Web Conference (ESWC)

**Overview**:
- Major European conference for semantic technologies
- Held May/June annually
- Also publishes in Springer LNCS
- Resources Track specifically for benchmarks

**Paper Format**:
- **Format**: Springer LNCS
- **Page Limit**: 15 pages (unlimited references)
- **Language**: English
- **Review**: Peer review with resources track criteria

**Resources Track Requirements**:
- Benchmark metrics must measure something "significant, relevant and important"
- Clear description of domain, modeling problems, requirements
- Design and coverage explained
- Advantages, complexities, and limitations discussed
- Data/code availability expected

**Timeline**:
- Submission: November-December
- Notification: February-March
- Conference: May-June

**Fit for Our Project**: ★★★★★
- Resources Track explicitly welcomes benchmark papers
- Earlier in year than ISWC (faster publication)
- Strong semantic web community
- European industry connections

#### 3. Semantic Web Journal (IOS Press)

**Overview**:
- Leading journal for semantic web research
- Published by IOS Press
- Open access options available
- Rolling submissions (no deadlines)

**Paper Types**:
- **Full Research Papers**: Novel research contributions
- **Dataset Descriptions**: 10 pages, describing KGs/datasets
- **Tools and Systems**: 10 pages, describing software

**Requirements**:
- Data and software must be hosted at stable long-term URL
- No subsequent changes allowed after publication
- Emphasis on open science practices
- Public review process (reviews published)

**Timeline**:
- Submission: Rolling
- First review: 6-8 weeks
- Revisions: 2-4 weeks
- Publication: 3-6 months total

**Fit for Our Project**: ★★★★☆
- High credibility in semantic web community
- No conference deadline pressure
- Open access aligns with industry dissemination goals
- Public reviews increase transparency

**Impact Factor**: 3.0-3.5 (solid mid-tier journal)

#### 4. Journal of Web Semantics (Elsevier)

**Overview**:
- Interdisciplinary journal covering semantic web technologies
- Published by Elsevier
- Single-blind peer review

**Benchmark Paper Requirements**:
- **Length**: 15-25 pages (double column format recommended)
- **Content**: Novel benchmarks including datasets
- **Evaluation**: Extensive evaluations required
- **Scope**: Problems of interest to community

**Review Process**:
- Initial editorial assessment
- Minimum 2 expert reviewers
- Single anonymized review

**Emphasis Areas**:
- Robust evaluation methodologies for KG-AI systems
- Correctness, scalability, data quality
- Reliability, interpretability, accountability

**Timeline**:
- Submission: Rolling
- First decision: 8-12 weeks
- Revisions: 4-6 weeks
- Publication: 4-8 months

**Fit for Our Project**: ★★★★☆
- Explicit benchmark paper category
- Page range accommodates comprehensive evaluation
- Strong emphasis on evaluation methodology
- Broader audience than semantic web specialists

#### 5. VLDB / SIGMOD (Database Conferences)

**Overview**:
- Top-tier database conferences
- VLDB: Very Large Data Bases
- SIGMOD: ACM Special Interest Group on Management of Data

**Relevance**:
- Database benchmarking track
- Performance evaluation papers valued
- Graph database sessions
- HTAP (Hybrid Transactional/Analytical Processing) benchmarks

**Format**:
- **VLDB**: 12 pages (conference style)
- **SIGMOD**: 12-14 pages (ACM format)
- **Review**: Highly competitive, rigorous peer review

**Fit for Our Project**: ★★★☆☆
- Broader database audience (not semantic-specific)
- Very competitive acceptance (~15-20%)
- Strong focus on performance benchmarking
- Less focus on semantic layer specifically
- Could position as "database comparison" rather than "semantic study"

**Recommendation**: Consider as secondary venue if ISWC/ESWC rejected

#### 6. arXiv Preprint

**Overview**:
- Open-access preprint repository
- No peer review (moderated only)
- Immediate publication (1 day processing)
- Citable with DOI
- Free to submit and access

**Requirements**:
- **Format**: LaTeX preferred (PDF accepted)
- **Categories**: cs.DB (Databases), cs.AI (Artificial Intelligence)
- **Endorsement**: Required for first-time submitters
- **License**: Creative Commons options available
- **File Size**: 10MB limit per file

**Why Submit to arXiv**:
1. **Speed**: Paper public within 24 hours
2. **Visibility**: Widely searched by researchers
3. **Priority**: Establishes precedence for ideas
4. **Complement**: Can submit to arXiv AND conference/journal
5. **Iteration**: Can update with revisions (version tracking)

**Timeline**:
- Submission: Anytime
- Processing: 1 business day
- Publication: Next announcement day (Sun-Thu)

**Fit for Our Project**: ★★★★★
- **Recommended**: Submit to arXiv BEFORE conference submission
- Establishes timestamp for work
- Makes research available immediately to Graphwise stakeholders
- Can cite arXiv version while journal version under review
- data.world paper used arXiv successfully

**Note**: Many conferences allow arXiv preprints despite double-blind review

### Recommended Publication Strategy

**Phase 1**: arXiv Preprint (Month 6)
- Submit immediately when first complete draft ready
- Get DOI and public URL
- Share with Graphwise and industry contacts
- Use for early feedback

**Phase 2**: Conference Submission (Month 6-7)
- Target: ESWC 2026 (submit Nov/Dec 2025) OR ISWC 2026 (submit May/June 2026)
- Revise based on arXiv feedback
- Follow double-blind review requirements
- Prepare for revision cycle

**Phase 3**: Journal Submission (If needed, Month 10-12)
- If conference rejected: Semantic Web Journal or Journal of Web Semantics
- Incorporate reviewer feedback from conference
- Expand to journal length if necessary
- Leverage arXiv downloads/citations as evidence of interest

**Expected Outcome**:
- arXiv version: Guaranteed publication, immediate visibility
- Conference acceptance: 40-50% chance with strong work (ESWC Resources Track favorable)
- Journal acceptance: 60-70% chance if conference reviews positive

---

## Paper Structure Template

### Abstract (150-250 words)

**Template**:

```
[CONTEXT - 2 sentences]: What is the problem space and why does it matter?

[GAP - 1-2 sentences]: What is missing in current research or practice?

[CONTRIBUTION - 1 sentence]: What does this paper contribute?

[METHOD - 2-3 sentences]: How did you conduct the study? What did you benchmark?

[KEY RESULTS - 2-3 sentences]: What are the most important quantified findings?

[IMPLICATIONS - 1-2 sentences]: What do these results mean for research/practice?
```

**Example for Graphwise Study**:

```
Semantic layer platforms promise to bridge the gap between enterprise data silos
and advanced AI applications through knowledge graphs and ontologies. However,
there is limited empirical evidence comparing the performance, scalability, and
usability of different semantic technologies for enterprise use cases.

This paper presents a comprehensive benchmark of six semantic layer platforms
(Graphwise AI Suite, AWS Neptune, Fluree, Franz Inc. AllegroGraph, OpenLink
Virtuoso, Stardog, and Neo4j) across three dimensions: query performance, data
modeling capabilities, and enterprise integration complexity.

We designed 50 benchmark queries spanning analytics, question answering, and
reasoning tasks across three enterprise domains (finance, healthcare, life sciences).
Results show that [PLATFORM X] achieves 3.2x faster query execution for analytical
workloads while [PLATFORM Y] demonstrates superior reasoning capabilities with
45% higher accuracy on inference tasks. RDF-based platforms exhibited 60% better
semantic expressiveness but 2.8x higher modeling complexity compared to property
graph approaches.

These findings provide empirical guidance for practitioners selecting semantic
technologies and establish reproducible benchmarks for future research.
```

**Key Principles**:
- Start broad (context) → narrow (gap) → specific (contribution)
- Lead with strongest quantified result
- No citations in abstract
- Standalone (readable without paper)
- Avoid vague claims ("better", "improved") - use numbers

---

### 1. Introduction (3-4 pages)

**Structure**:

**1.1 Motivation (0.75 pages)**
- Start with real-world problem that non-experts understand
- Quantify the problem (market size, cost of inefficiency, opportunity)
- Explain why timing is important (e.g., rise of GraphRAG, LLMs)
- Connect to Graphwise's business context (hybrid AI, deterministic + probabilistic)

**1.2 Problem Statement (0.5 pages)**
- What specific knowledge gap exists?
- Why haven't existing benchmarks addressed this?
- Why is apples-to-apples comparison difficult?
- What prevents practitioners from making informed decisions?

**1.3 Research Questions (0.25 pages)**
Format as explicit RQ1, RQ2, RQ3:

```
RQ1: How do semantic layer platforms compare in query execution
     performance across analytical, transactional, and reasoning workloads?

RQ2: What trade-offs exist between semantic expressiveness and
     implementation complexity across RDF and property graph approaches?

RQ3: To what extent do platform-specific features (e.g., inference engines,
     vectorization, caching) impact real-world enterprise use case performance?
```

**1.4 Contributions (0.5 pages)**
Bulleted list of specific contributions:
- Novel benchmark framework spanning X platforms, Y queries, Z domains
- Empirical performance comparison with reproducible methodology
- Open-source benchmark suite and dataset (with GitHub link)
- Practical decision framework for platform selection
- Quantified trade-off analysis (expressiveness vs. complexity vs. performance)

**1.5 Scope and Limitations (0.5 pages)**
What's IN scope:
- Platforms compared: (list)
- Workload types: (list)
- Metrics: (list)
- Use cases: (list)

What's OUT of scope:
- Streaming/real-time workloads
- Graph analytics (PageRank, community detection)
- Specific vendor features not generalizable
- Cost comparison (pricing varies)

**1.6 Paper Organization (0.25 pages)**
```
The remainder of this paper is organized as follows. Section 2 provides
background on semantic technologies and reviews related benchmarking work.
Section 3 describes our benchmark methodology, including platform selection,
workload design, and evaluation metrics. Section 4 presents experimental
setup and implementation details. Section 5 reports results across performance,
expressiveness, and usability dimensions. Section 6 discusses implications,
limitations, and lessons learned. Section 7 concludes with summary and future work.
```

**Writing Tips**:
- Use "we" (active voice): "We designed a benchmark..." not "A benchmark was designed..."
- Be specific: Not "many companies" but "67% of Fortune 500 companies"
- Cite recent industry reports: Gartner, Forrester, market research
- Connect to current trends: GraphRAG, LLMs, hybrid AI
- Set clear scope early to manage expectations

---

### 2. Background & Related Work (3-4 pages)

**Structure**:

**2.1 Semantic Technologies Overview (0.75 pages)**
- Knowledge Graphs: RDF vs. Property Graphs
- Ontologies and Reasoning (OWL, RDFS, SHACL)
- Query Languages: SPARQL vs. Cypher vs. Gremlin
- Semantic Layer Architecture
- Citations: W3C standards, foundational papers (Berners-Lee, etc.)

**2.2 Enterprise Use Cases (0.5 pages)**
- Knowledge Management and Enterprise Search
- Question Answering and Conversational AI
- Data Integration and Master Data Management
- Regulatory Compliance and Data Governance
- Citations: Industry case studies (BBC, Reuters, pharmaceutical companies)

**2.3 Existing Benchmarking Frameworks (1.5 pages)**

**2.3.1 Database Benchmarks**
- TPC-H, TPC-DS (relational benchmarks - why insufficient for KGs)
- YCSB (key-value stores)
- Limitations for semantic technologies

**2.3.2 RDF/SPARQL Benchmarks**
- **Berlin SPARQL Benchmark (BSBM)**: E-commerce use case, scalability testing
- **SP2Bench**: DBLP bibliography data, SPARQL operator coverage
- **LDBC Social Network Benchmark**: Property graph focus, realistic data
- **LDBC Semantic Publishing Benchmark**: Media/publishing domain, RDF-based
- Citations: Original benchmark papers

**2.3.3 Knowledge Graph Benchmarks**
- Wikidata SPARQL benchmarks
- DBpedia query logs
- Enterprise-specific: Insurance, healthcare, finance
- Citations: Recent papers (2020-2024)

**2.4 Platform Comparison Studies (0.75 pages)**
- data.world KG-LLM benchmark (Sequeda et al., 2023) - detailed discussion
- Graph database performance comparisons (Neo4j, JanusGraph, TigerGraph)
- RDF store evaluations (Virtuoso, Stardog, GraphDB)
- What's missing: Cross-paradigm comparison (RDF vs. property graphs)
- What's missing: Enterprise integration complexity

**2.5 Gap Analysis (0.5 pages)**
Table summarizing existing work:

| Study | Year | Platforms | Metrics | Domains | Limitations |
|-------|------|-----------|---------|---------|-------------|
| Sequeda et al. | 2023 | SQL vs. KG | Accuracy | Insurance | Single domain, LLM-focused |
| LDBC SNB | 2023 | Neo4j, JanusGraph, etc. | Query time | Social network | Property graphs only |
| ... | ... | ... | ... | ... | ... |

**Our contribution**: First comprehensive cross-paradigm benchmark covering RDF and property graphs with enterprise integration complexity metrics.

**Writing Tips**:
- Organize chronologically or thematically (not by author)
- Be critical but fair: "While X provides valuable insights, it is limited to..."
- Connect each subsection back to your research questions
- Use table or figure to synthesize related work
- Cite 30-50 papers (mix of foundational and recent)
- Include both academic papers and industry reports

---

### 3. Methodology (4-5 pages)

**This is the most critical section for reproducibility.**

**3.1 Research Design (0.5 pages)**

```
We adopt a comparative benchmarking methodology to evaluate semantic layer
platforms across three dimensions: (1) query execution performance,
(2) semantic expressiveness and modeling capabilities, and (3) enterprise
integration complexity. Our approach follows established database benchmarking
principles (Gray, 1993) adapted for semantic technologies.
```

**Design Choices**:
- Why these platforms? (Selection criteria)
- Why these workloads? (Representativeness)
- Why these domains? (Generalizability)
- Why these metrics? (Relevance to practitioners)

**3.2 Platform Selection (1 page)**

**Selection Criteria**:
1. Market presence (DB-Engines ranking, Gartner reports)
2. Active development (GitHub activity, release frequency)
3. Enterprise adoption (customer case studies)
4. Technology diversity (RDF, property graph, hybrid)

**Platforms Selected**:

| Platform | Vendor | Type | Primary Language | Reasoning Support |
|----------|--------|------|------------------|-------------------|
| Graphwise AI Suite | Graphwise (Ontotext + SWC) | RDF | SPARQL | OWL, SHACL |
| AWS Neptune | Amazon | Dual (RDF + PG) | SPARQL, Gremlin | Limited |
| AllegroGraph | Franz Inc. | RDF | SPARQL, Prolog | RDFS++ |
| Virtuoso | OpenLink | RDF | SPARQL | RDFS, OWL |
| Stardog | Stardog Union | RDF | SPARQL | OWL 2 |
| Neo4j | Neo4j Inc. | Property Graph | Cypher | GDS library |
| Fluree | Fluree PBC | Blockchain + RDF | FlureeQL, SPARQL | Limited |

**Version Numbers**: Specify exact versions tested (critical for reproducibility)

**3.3 Benchmark Workload Design (1.5 pages)**

**3.3.1 Domain Selection**
- **Finance**: Risk analytics, regulatory reporting, KYC (Know Your Customer)
- **Healthcare**: Clinical decision support, drug interactions, patient pathways
- **Life Sciences**: Molecular biology, protein interactions, research data integration

**Rationale**: Cover different data characteristics (structured vs. unstructured),
reasoning complexity (simple lookups vs. multi-hop inference), and query patterns
(OLTP vs. OLAP).

**3.3.2 Query Categories**

**Category 1: Analytical Queries (20 queries)**
- Aggregations: COUNT, SUM, AVG across large datasets
- Joins: Multi-entity relationships (e.g., customer-transaction-product)
- Time-series: Temporal analysis
- Example: "Total transaction volume by customer segment in Q4 2024"

**Category 2: Navigational Queries (15 queries)**
- Path traversal: Shortest path, all paths
- Subgraph extraction: Retrieve entity neighborhood
- Pattern matching: Find specific graph patterns
- Example: "All drug interactions within 3 hops of Aspirin"

**Category 3: Reasoning & Inference Queries (10 queries)**
- Class hierarchy: Subsumption, classification
- Property propagation: Transitive properties
- Constraint validation: SHACL shapes
- Example: "All medications contraindicated for patients with diabetes and hypertension"

**Category 4: Question Answering (5 queries)**
- Natural language questions
- LLM integration (SPARQL/Cypher generation)
- Semantic matching
- Example: "Which customers are at high risk of churn based on behavior?"

**3.3.3 Data Scale**
- **Small**: 100K triples/nodes (rapid prototyping scenarios)
- **Medium**: 10M triples/nodes (departmental deployment)
- **Large**: 1B triples/nodes (enterprise-wide deployment)

**Data Generation**:
- Synthetic data using established generators (BSBM, custom scripts)
- Schema complexity: 50-100 classes, 200-300 properties
- Data distribution: Realistic (power-law, temporal patterns)

**3.4 Evaluation Metrics (1 page)**

**Performance Metrics**:
- **Query Execution Time**: Median, p95, p99 latency (milliseconds)
- **Throughput**: Queries per second (QPS) at saturation
- **Scalability**: Performance degradation as data grows (100K → 10M → 1B)
- **Cold Start**: First query vs. cached query performance
- **Concurrency**: Performance under 1, 10, 100 concurrent users

**Expressiveness Metrics**:
- **Modeling Effort**: Lines of schema code (ontology/schema definition)
- **Query Complexity**: Average query length (lines of SPARQL/Cypher)
- **Feature Coverage**: Percentage of requirements expressible natively
- **Inference Capabilities**: Supported reasoning (RDFS, OWL 2 DL, OWL 2 RL)

**Integration Metrics**:
- **Setup Time**: Hours to deploy and configure (installation to first query)
- **Data Loading Time**: Hours to import benchmark dataset
- **API Complexity**: Number of API calls for common tasks
- **Documentation Quality**: Availability, clarity, examples (1-5 scale)
- **Tool Ecosystem**: Available connectors, libraries, IDE support

**Cost Metrics** (if applicable):
- **Infrastructure Cost**: Cloud deployment cost ($/month)
- **Licensing**: Software license fees
- **Note**: Pricing varies by deployment, so report relative costs or omit

**3.5 Experimental Controls (0.5 pages)**

**Hardware Standardization**:
- Cloud instance type: AWS m5.2xlarge (8 vCPU, 32 GB RAM)
- Storage: 500 GB SSD
- Network: 10 Gbps
- Rationale: Typical enterprise deployment configuration

**Software Standardization**:
- Operating system: Ubuntu 22.04 LTS
- Java version: OpenJDK 17 (for JVM-based platforms)
- Disabled caching between test runs
- Cleared OS cache: `sync; echo 3 > /proc/sys/vm/drop_caches`

**Measurement Protocol**:
- Warm-up: 10 query executions (discarded)
- Measurement: 30 query executions per test
- Metrics: Median (primary), p95, p99 (variability)
- Randomization: Query order randomized to avoid ordering effects
- Timing: Client-side measurement (end-to-end latency)

**3.6 Threats to Validity (0.5 pages)**

**Internal Validity**:
- Platform configuration: Default settings used (may not be optimal)
- Tuning: No vendor-specific tuning applied (fair but may not reflect best performance)
- Mitigation: Document all configuration parameters

**External Validity**:
- Synthetic data: May not capture all real-world patterns
- Query selection: May not represent all enterprise use cases
- Mitigation: Multiple domains, diverse query types

**Construct Validity**:
- Metrics: Execution time may not capture all aspects of "performance"
- Mitigation: Multiple metrics (throughput, scalability, concurrency)

**Writing Tips**:
- Be exhaustive: Reviewers will scrutinize methodology
- Justify every choice: "Why this metric?" "Why this scale?"
- Provide reproducibility checklist
- Reference established benchmarking principles (Gray, 1993; TPC guidelines)
- Include diagram of experimental workflow

---

### 4. Experimental Setup (2-3 pages)

**4.1 Platform Deployment (1 page)**

For EACH platform, provide:

**4.1.1 Graphwise AI Suite**
- Version: X.Y.Z
- Deployment: Docker container / Cloud instance
- Configuration:
  - JVM heap: 16 GB
  - Query timeout: 300 seconds
  - Reasoning: Enabled (OWL 2 RL)
- Data loading: Bulk RDF import via [tool]
- Loading time: X hours for Y triples

[Repeat for each platform...]

**Table: Platform Configurations**

| Platform | Version | Deployment | Heap/Memory | Special Config |
|----------|---------|------------|-------------|----------------|
| Graphwise | 10.x | Docker | 16 GB | OWL 2 RL reasoning |
| Neptune | Engine X.Y | AWS Managed | db.r5.2xlarge | SPARQL endpoint |
| ... | ... | ... | ... | ... |

**4.2 Data Preparation (0.75 pages)**

**Schema Design**:
- Ontology/schema design per domain
- Class hierarchy depth: 5-7 levels
- Property types: Object properties (relationships) vs. datatype properties
- Example: Finance ontology (Customer → Account → Transaction)

**Data Generation**:
- Tools: BSBM generator (modified), custom Python scripts
- Distributions: Zipf distribution for entity popularity
- Temporal patterns: Realistic transaction frequencies
- Referential integrity: Ensured (no dangling references)

**Data Loading**:
- Format: RDF (Turtle, N-Triples) for RDF stores; CSV import for property graphs
- Loading scripts: Available on GitHub [link]
- Validation: Ran test queries to verify data integrity

**4.3 Query Implementation (0.75 pages)**

**Query Translation**:
- Each benchmark query implemented in:
  - SPARQL (for RDF platforms)
  - Cypher (for Neo4j)
  - Gremlin (for Neptune property graph mode)
  - FlureeQL (for Fluree)

**Translation Challenges**:
- Reasoning queries: Not directly translatable to Cypher (workarounds documented)
- Aggregations: Syntax differences (GROUP BY in SPARQL vs. Cypher)
- Vendor-specific extensions: Used only when necessary, documented

**Query Repository**:
- All queries published: [GitHub repo link]
- Organized by category and platform
- Includes expected results for validation

**4.4 Measurement Infrastructure (0.5 pages)**

**Execution Framework**:
- Custom Python harness: [GitHub link]
- Libraries: requests (HTTP), rdflib (RDF processing), time (timing)
- Parallelization: Single-threaded for consistency
- Logging: All query executions logged with timestamps

**Timing Methodology**:
- Start: Timestamp immediately before HTTP request / API call
- End: Timestamp after result fully received
- Includes: Network latency, query execution, result serialization
- Excludes: Client-side processing of results

**Data Collection**:
- CSV output: query_id, platform, execution_time_ms, result_count
- Statistical analysis: pandas, scipy.stats
- Visualization: matplotlib, seaborn

**Writing Tips**:
- Provide enough detail for exact replication
- Include version numbers for ALL software
- Link to all code and data repositories
- Acknowledge limitations of synthetic data
- Use tables for multi-platform configurations

---

### 5. Results (5-7 pages)

**Organization**: Present results aligned with research questions

**5.1 Query Execution Performance (RQ1) - 2.5 pages**

**5.1.1 Overall Performance Comparison**

**Figure 1**: Bar chart showing median query execution time by platform (lower is better)
- X-axis: Platform names
- Y-axis: Median latency (milliseconds, log scale)
- Error bars: Interquartile range (IQR)
- Caption: "Median query execution time across all 50 benchmark queries.
  Error bars represent IQR (25th to 75th percentile). N=30 executions per query."

**Key Findings**:
- Platform X achieved lowest median latency (45 ms) across all queries
- Platform Y exhibited highest variability (IQR = 120-850 ms)
- RDF platforms: Median 120 ms (range: 45-340 ms)
- Property graph platforms: Median 80 ms (range: 60-95 ms)

**Statistical Test**:
- Kruskal-Wallis H-test: χ²(6) = 234.5, p < 0.001 (significant difference)
- Pairwise comparisons: Dunn's test with Bonferroni correction
- Effect size: η² = 0.67 (large effect)

**5.1.2 Performance by Query Category**

**Figure 2**: Grouped bar chart by query category
- Analytical queries: Platform X leads (35 ms median)
- Navigational queries: Platform Y leads (22 ms median)
- Reasoning queries: Platform Z leads (180 ms median)

**Table: Performance Summary by Category**

| Category | Platform 1 | Platform 2 | Platform 3 | ... | Winner |
|----------|------------|------------|------------|-----|---------|
| Analytical (n=20) | 35 ms | 52 ms | 120 ms | ... | Platform 1 |
| Navigational (n=15) | 45 ms | 22 ms | 80 ms | ... | Platform 2 |
| Reasoning (n=10) | 280 ms | N/A | 180 ms | ... | Platform 3 |
| Question Answering (n=5) | 340 ms | 520 ms | 410 ms | ... | Platform 1 |

**5.1.3 Scalability Analysis**

**Figure 3**: Line chart showing performance degradation as data scales
- X-axis: Data size (100K, 10M, 1B triples/nodes, log scale)
- Y-axis: Median query time (milliseconds, log scale)
- Lines: One per platform
- Caption: "Query execution time as dataset scales. Analytical queries only (n=20)."

**Findings**:
- Platform X: Linear scaling (O(n)) up to 10M, sublinear beyond
- Platform Y: Quadratic scaling (O(n²)) - performance degrades significantly
- Threshold: Most platforms exhibit performance cliff at ~50M triples

**5.1.4 Concurrency Performance**

**Figure 4**: Line chart showing throughput vs. concurrent users
- X-axis: Concurrent users (1, 10, 50, 100)
- Y-axis: Throughput (queries per second)

**Findings**:
- Platform X: Scales to 100 concurrent users (85 QPS)
- Platform Y: Throughput degrades after 10 users (contention bottleneck)

**5.2 Semantic Expressiveness (RQ2) - 1.5 pages**

**5.2.1 Modeling Effort**

**Table: Schema Complexity**

| Domain | Platform | Schema LOC | Classes | Properties | Inference Rules |
|--------|----------|------------|---------|------------|-----------------|
| Finance | Graphwise | 450 | 45 | 120 | 18 (OWL) |
| Finance | Neo4j | 180 | 12 (labels) | 45 (properties) | 0 (manual) |
| ... | ... | ... | ... | ... | ... |

**Findings**:
- RDF platforms: Average 420 LOC per domain (higher expressiveness)
- Property graphs: Average 160 LOC per domain (simpler, less expressive)
- Trade-off: Expressiveness vs. simplicity

**5.2.2 Feature Coverage**

**Table: Reasoning Capability Coverage**

| Requirement | Graphwise | Neptune | AllegroGraph | Virtuoso | Stardog | Neo4j | Fluree |
|-------------|-----------|---------|--------------|----------|---------|-------|--------|
| Class hierarchy (RDFS) | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ~ |
| Property transitivity | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ |
| OWL 2 RL reasoning | ✓ | ✗ | ~ | ~ | ✓ | ✗ | ✗ |
| SHACL validation | ✓ | ✓ | ~ | ~ | ✓ | ✗ | ✗ |

✓ = Fully supported, ~ = Partial support, ✗ = Not supported

**Scoring**:
- RDF platforms: Average 75% feature coverage
- Property graph: Average 20% feature coverage (native features only)

**5.2.3 Query Complexity**

**Figure 5**: Box plot of query length (lines of code) by platform

**Findings**:
- SPARQL queries: Median 12 lines (range: 5-35)
- Cypher queries: Median 8 lines (range: 3-18)
- But: Cypher cannot express reasoning natively (requires application logic)

**5.3 Enterprise Integration (RQ3) - 1.5 pages**

**5.3.1 Setup Complexity**

**Table: Integration Effort**

| Platform | Setup Time | Data Load Time (10M) | API Calls (common task) | Doc Quality (1-5) |
|----------|------------|----------------------|-------------------------|-------------------|
| Graphwise | 2.5 hours | 45 minutes | 3 | 4.5 |
| Neptune | 1 hour (managed) | 30 minutes | 5 | 4.0 |
| Neo4j | 1.5 hours | 20 minutes | 2 | 5.0 |
| ... | ... | ... | ... | ... |

**5.3.2 Tool Ecosystem**

**Figure 6**: Radar chart showing tool ecosystem maturity
- Axes: IDE support, client libraries, visualization tools, admin tools, community size
- Shapes: One per platform

**Findings**:
- Neo4j: Most mature ecosystem (5/5 across all axes)
- RDF platforms: Strong standards compliance (SPARQL, RDF), fewer tools

**5.4 Statistical Summary**

**Table: Cross-Cutting Results**

| Dimension | Best Performer | Metric | Runner-Up | Statistical Significance |
|-----------|----------------|--------|-----------|--------------------------|
| Analytical Performance | Platform X | 35 ms | Platform Y (52 ms) | p < 0.001, d = 1.2 |
| Reasoning | Platform Z | 180 ms | Platform A (280 ms) | p < 0.01, d = 0.8 |
| Scalability | Platform X | Linear to 1B | Platform Y (cliff at 50M) | N/A |
| Expressiveness | Graphwise | 75% coverage | Stardog (72%) | N/A |

**Writing Tips**:
- Lead with figures/tables, then explain in text
- Always include sample sizes (n=X)
- Report both descriptive and inferential statistics
- Use consistent color scheme across figures
- Make figures standalone (detailed captions)
- Avoid interpretation in Results - save for Discussion

---

### 6. Discussion (3-4 pages)

**6.1 Key Findings Synthesis (1 page)**

**Finding 1: Performance-Expressiveness Trade-off**
- RDF platforms: Higher expressiveness (75% feature coverage), slower (120 ms median)
- Property graphs: Lower expressiveness (20% coverage), faster (80 ms median)
- **Implication**: Choice depends on use case
  - Simple navigation → Property graphs
  - Complex reasoning → RDF stores
  - Hybrid needs → Graphwise (optimized RDF) or Neptune (dual-mode)

**Finding 2: Scalability Ceiling**
- Most platforms hit performance cliff at 50M triples
- Exception: Platform X maintains linear scaling to 1B
- **Implication**: Enterprises with >50M entities need careful platform selection
- **Technical reason**: Index size exceeds RAM, causes disk thrashing

**Finding 3: Reasoning as Differentiator**
- Reasoning queries: 3-5x slower than simple lookups
- But: Enable queries impossible in property graphs
- **Example**: Drug interaction inference - 180 ms (automatic) vs. manual coding
- **ROI calculation**: Development time saved >> query overhead

**6.2 Practical Recommendations (1 page)**

**For Practitioners**:

**Scenario 1: High-performance analytics, simple schema**
- **Recommend**: Neo4j or Neptune (property graph mode)
- **Rationale**: 35-50% faster, simpler modeling
- **Trade-off**: No native reasoning, manual rule coding

**Scenario 2: Complex domain models, regulatory compliance**
- **Recommend**: Graphwise, Stardog, or AllegroGraph
- **Rationale**: OWL/SHACL support, audit trails, inference
- **Trade-off**: 20-40% slower, steeper learning curve

**Scenario 3: Mixed workloads (analytics + reasoning)**
- **Recommend**: Graphwise AI Suite (optimized RDF)
- **Rationale**: Best-in-class reasoning performance, acceptable analytics speed
- **Trade-off**: Cost (commercial license)

**Scenario 4: Cloud-native deployment**
- **Recommend**: AWS Neptune (managed service)
- **Rationale**: Zero ops overhead, dual RDF/PG support
- **Trade-off**: Vendor lock-in, limited reasoning

**Decision Matrix**:

| Priority | Platform 1 | Platform 2 | Platform 3 |
|----------|------------|------------|------------|
| Performance > all | Neo4j | Neptune PG | Platform X |
| Reasoning > all | Graphwise | Stardog | AllegroGraph |
| Balanced | Graphwise | Neptune | Virtuoso |
| Cost-sensitive | Virtuoso (open) | Neo4j Community | Fluree |

**6.3 Comparison to Related Work (0.75 pages)**

**vs. data.world study (Sequeda et al., 2023)**:
- Similarities: Benchmark methodology, enterprise focus
- Differences: We compare platforms; they compare SQL vs. KG
- Complementary: Our work extends to multi-platform comparison
- Consistent findings: KG improves accuracy (their 238% gain aligns with our reasoning advantage)

**vs. LDBC SNB benchmarks**:
- Similarities: Standardized workload, reproducibility
- Differences: LDBC focuses on property graphs; we include RDF
- Extension: Our work bridges LDBC and semantic web communities

**6.4 Implications for Research (0.5 pages)**

**For Semantic Web Community**:
- Need for standardized cross-paradigm benchmarks
- Opportunity: Optimize RDF stores for analytical workloads
- Gap: Hybrid reasoning + performance (Graphwise leads but room for improvement)

**For Database Community**:
- Knowledge graphs are production-ready for enterprise use
- Performance gap is narrowing (2-3x, not 10x)
- Reasoning capabilities differentiate KGs from traditional graphs

**6.5 Limitations and Threats to Validity (1 page)**

**Methodology Limitations**:
1. **Synthetic data**: Real enterprise data may have different characteristics
   - Mitigation: Multiple domains, realistic distributions
   - Future work: Benchmark on real customer datasets (with permission)

2. **Default configurations**: Platforms not optimally tuned
   - Mitigation: Tuning requires deep expertise, may not be available to typical users
   - Future work: Vendor-tuned benchmark (invite vendors to optimize)

3. **Query selection bias**: Our 50 queries may not represent all use cases
   - Mitigation: Diverse categories, multiple domains
   - Future work: Crowdsource queries from practitioners

4. **Version sensitivity**: Results may change with software updates
   - Mitigation: Version numbers documented, reproducible
   - Future work: Re-run benchmark annually

**Generalizability**:
- Findings apply to similar enterprise use cases
- May not generalize to: Scientific data, social networks, IoT
- Scaling results: Hardware-dependent (tested on m5.2xlarge)

**Construct Validity**:
- "Performance" measured as latency only
- Did not measure: Update performance, backup/restore, high availability
- Future work: Expand to operational metrics

**External Validity**:
- Cloud deployment only (AWS)
- Did not test: On-premise, hybrid cloud, multi-cloud
- Future work: Infrastructure comparison

**Ethical Considerations**:
- No conflicts of interest: University-led research
- Vendor neutrality: All platforms tested equally
- Transparency: All code/data public
- Note: If Graphwise sponsors, disclose prominently

**Writing Tips**:
- Be honest about limitations
- Don't oversell findings
- Suggest specific future work to address gaps
- Frame limitations as opportunities for community
- Acknowledge what you didn't test

---

### 7. Conclusion (1-1.5 pages)

**7.1 Summary of Contributions (0.5 pages)**

```
This paper presented a comprehensive benchmark of seven semantic layer platforms
across query performance, semantic expressiveness, and enterprise integration
complexity. Our key contributions include:

1. **Empirical comparison**: First cross-paradigm benchmark comparing RDF and
   property graph platforms on equal footing, covering 50 queries across 3 domains.

2. **Quantified trade-offs**: RDF platforms demonstrate 60% higher semantic
   expressiveness but 35% slower performance compared to property graphs for
   analytical workloads, while achieving 3-5x faster reasoning query execution
   when reasoning is required.

3. **Scalability analysis**: Identified performance ceiling at ~50M entities for
   most platforms, with [Platform X] achieving linear scaling to 1B entities.

4. **Practical decision framework**: Provided evidence-based recommendations for
   platform selection based on use case priorities.

5. **Open benchmark suite**: Released reproducible benchmark framework, queries,
   and data on GitHub [link], enabling community validation and extension.
```

**7.2 Key Findings Recap (0.25 pages)**

Bullet summary of 3-5 most important results:
- Platform X achieved 35 ms median latency for analytical queries (best-in-class)
- Graphwise demonstrated superior reasoning performance (180 ms vs. 280+ ms competitors)
- Property graphs are 35% faster but support only 20% of semantic requirements
- RDF platforms scale linearly to 50M entities; beyond that, architecture matters
- Enterprise integration effort ranges from 1-3 hours (managed) to 4-8 hours (self-hosted)

**7.3 Implications (0.25 pages)**

**For Practitioners**:
- Performance differences are significant but not prohibitive (2-3x, not 10x)
- Reasoning capabilities justify overhead for knowledge-intensive applications
- Cloud-managed options reduce integration complexity

**For Vendors**:
- Opportunity to optimize RDF stores for analytical performance
- Reasoning remains key differentiator for semantic platforms
- Hybrid architectures (Neptune dual-mode) show promise

**For Researchers**:
- Need for standardized benchmarks across paradigms
- Query optimization for semantic queries under-researched
- Scalability beyond 1B entities remains open challenge

**7.4 Future Work (0.5 pages)**

**Short-term (1 year)**:
- Extend benchmark to additional platforms (Blazegraph, MillenniumDB, QLever)
- Include update/write workloads (current focus: read queries)
- Test on real enterprise datasets (anonymized customer data)
- Vendor-tuned configurations (invite vendors to optimize)

**Medium-term (2-3 years)**:
- Hybrid AI benchmarks: GraphRAG, vector + graph, LLM integration
- Multi-cloud deployment comparison (AWS, Azure, GCP)
- Cost-performance optimization models
- Benchmark-driven platform improvements (work with vendors)

**Long-term (5 years)**:
- Establish community-maintained benchmark (like TPC, LDBC)
- Annual benchmark refresh with new platforms and workloads
- Industry standard for semantic platform evaluation
- Integration with enterprise architecture decision frameworks

**7.5 Closing Statement (0.25 pages)**

```
As enterprises increasingly adopt knowledge graphs and semantic technologies for
AI applications, the need for rigorous, reproducible platform evaluations becomes
critical. Our benchmark provides the first comprehensive cross-paradigm comparison,
enabling evidence-based technology selection. By open-sourcing our methodology,
queries, and data, we invite the community to validate, extend, and refine this
work. We hope this research accelerates semantic technology adoption and informs
future platform development, ultimately advancing the state of enterprise knowledge
management and hybrid AI systems.
```

**Writing Tips**:
- Do not introduce new information in Conclusion
- Recapitulate key findings in 1-2 sentences each
- End with forward-looking statement
- Keep it concise (1-1.5 pages max)
- Inspire community action (use our benchmark, extend it)

---

### 8. References

**Target Count**: 40-60 references

**Citation Style**:
- **Conferences**: Typically use Springer LNCS style (numbered, e.g., [1], [2])
- **Journals**: May use author-year (e.g., Sequeda et al., 2023)
- **Tool**: BibTeX with appropriate .bst file

**Composition**:
- **Foundational papers** (20-30%): Semantic web pioneers, benchmark methodology
  - Berners-Lee, T., Hendler, J., Lassila, O.: The semantic web. Scientific American (2001)
  - Gray, J.: The Benchmark Handbook for Database and Transaction Systems (1993)

- **Recent research** (40-50%): Papers from 2020-2025
  - Sequeda, J., et al.: Benchmark to Understand Role of Knowledge Graphs... (2023)
  - LDBC papers (2020-2024)
  - Graph database comparison studies (2022-2024)

- **Standards & specifications** (10-15%): W3C specifications
  - SPARQL 1.1 Specification
  - OWL 2 Web Ontology Language
  - SHACL Shapes Constraint Language

- **Industry reports** (10-20%): Gartner, Forrester, vendor whitepapers
  - Gartner: Magic Quadrant for Cloud Database Management Systems (2024)
  - Forrester: Knowledge Graphs for Enterprise Data Management (2023)

- **Technical documentation** (5-10%): Platform documentation, GitHub repos
  - Neo4j Documentation (version X.Y)
  - Graphwise Technical Specifications

**Example BibTeX Entries**:

```bibtex
@article{sequeda2023benchmark,
  title={A Benchmark to Understand the Role of Knowledge Graphs on Large Language Model's Accuracy for Question Answering on Enterprise SQL Databases},
  author={Sequeda, Juan and Allemang, Dean and Jacob, Bryon},
  journal={arXiv preprint arXiv:2311.07509},
  year={2023}
}

@inproceedings{angles2023ldbc,
  title={LDBC Social Network Benchmark v0.3.3},
  author={Angles, Renzo and others},
  booktitle={Proceedings of GRADES-NDA},
  year={2023},
  publisher={ACM}
}

@article{berners2001semantic,
  title={The semantic web},
  author={Berners-Lee, Tim and Hendler, James and Lassila, Ora},
  journal={Scientific American},
  volume={284},
  number={5},
  pages={34--43},
  year={2001}
}
```

**Management**:
- Use Zotero or Mendeley to collect papers
- Export to BibTeX (.bib file)
- Use LaTeX \cite{key} commands
- Run BibTeX to generate bibliography

---

## Academic Writing Guidelines

### Tone & Style

**Academic Voice**:
- **Formal but accessible**: Not stuffy, but not casual
- **Active voice preferred**: "We designed a benchmark" > "A benchmark was designed"
- **Third person for others**: "Sequeda et al. demonstrated..."
- **First person plural for our work**: "We found..." not "The authors found..."

**Technical Precision**:
- Use exact terminology: "RDF triple store" not "graph database" (too generic)
- Define acronyms on first use: "SPARQL Protocol and RDF Query Language (SPARQL)"
- Specify versions: "GPT-4" not just "GPT"
- Quantify claims: "35% faster" not "much faster"

**Objectivity**:
- Avoid hype: "Our results show..." not "Our revolutionary approach proves..."
- Acknowledge limitations: "While our benchmark covers X, it does not address Y..."
- Fair to competitors: "Platform X excels at reasoning but underperforms on analytics"
- Evidence-based: Every claim must cite data or prior work

**Clarity**:
- Short sentences: 15-25 words ideal
- Avoid nested clauses: Break into multiple sentences
- Concrete examples: Not "performance varies" but "latency ranges from 35-340 ms"
- Visual aids: Use figures/tables, don't just describe in text

---

### Section-by-Section Guide

**Abstract**:
- ✅ Standalone (readable without paper)
- ✅ No citations
- ✅ One key number (the headline result)
- ✅ 150-250 words (strict)
- ✅ Structured (context → gap → contribution → method → results → implications)

**Introduction**:
- ✅ Start broad (anyone can understand first paragraph)
- ✅ Narrow to specific problem by end of section
- ✅ Explicit research questions (RQ1, RQ2, RQ3)
- ✅ Bulleted contributions
- ✅ Roadmap sentence ("The remainder of this paper...")

**Related Work**:
- ✅ Thematic organization (not chronological list)
- ✅ Critical analysis (don't just summarize)
- ✅ Table synthesizing prior benchmarks
- ✅ Clear gap statement (what's missing)
- ✅ 30-50 citations

**Methodology**:
- ✅ Reproducibility: Someone can replicate from this section alone
- ✅ Justification: Why each design choice?
- ✅ Threats to validity: Acknowledge limitations
- ✅ Diagram of experimental workflow

**Results**:
- ✅ Figures first, then text explanation
- ✅ Descriptive statistics: mean, median, std dev
- ✅ Inferential statistics: p-values, effect sizes
- ✅ No interpretation (save for Discussion)
- ✅ Sample sizes always reported (n=X)

**Discussion**:
- ✅ Interpret results (what do they mean?)
- ✅ Compare to related work (consistent or contradictory?)
- ✅ Practical implications (what should practitioners do?)
- ✅ Honest limitations (what can't we claim?)

**Conclusion**:
- ✅ Summarize contributions (bullet list)
- ✅ No new information
- ✅ Future work (specific, not vague)
- ✅ Closing vision statement

---

### Common Pitfalls to Avoid

**Pitfall 1: Vague claims**
- ❌ "Our approach is much better"
- ✅ "Our approach achieves 35% lower latency (p < 0.001)"

**Pitfall 2: Missing baselines**
- ❌ "Platform X completes queries in 45 ms"
- ✅ "Platform X completes queries in 45 ms, compared to 120 ms for Platform Y"

**Pitfall 3: Cherry-picking results**
- ❌ Only reporting best-case scenarios
- ✅ Report median, p95, p99; show variability

**Pitfall 4: No statistical testing**
- ❌ "Platform X is faster" (based on eyeballing means)
- ✅ "Platform X is significantly faster (t(58)=4.2, p<0.001, d=1.1)"

**Pitfall 5: Overgeneralizing**
- ❌ "RDF platforms are always slower than property graphs"
- ✅ "RDF platforms exhibited 35% higher latency for analytical queries in our benchmark"

**Pitfall 6: Mixing Results and Discussion**
- ❌ "Platform X achieved 45 ms, which is impressive because..."
- ✅ Results: "Platform X: 45 ms"; Discussion: "This represents a 2x improvement over..."

**Pitfall 7: Poor figure quality**
- ❌ Low-resolution screenshots, default Excel colors
- ✅ Vector graphics (PDF), colorblind-safe palette, 300 DPI

**Pitfall 8: Inconsistent terminology**
- ❌ "Knowledge graph", "semantic graph", "RDF graph" used interchangeably
- ✅ Define term once, use consistently

**Pitfall 9: Missing reproducibility details**
- ❌ "We ran the queries on a cloud server"
- ✅ "AWS m5.2xlarge instance (8 vCPU, 32 GB RAM, Ubuntu 22.04, OpenJDK 17)"

**Pitfall 10: No acknowledgment of limitations**
- ❌ Claiming universal applicability
- ✅ "Our findings apply to enterprise analytics workloads; streaming and graph analytics were not evaluated"

---

## Citation Standards

### Recommended Style

**For ISWC/ESWC (Springer LNCS)**:
- **Format**: Numbered citations [1], [2], etc.
- **In-text**: "Sequeda et al. [15] demonstrated..."
- **Bibliography**: Sorted by citation order or alphabetically (check conference guidelines)
- **BibTeX style**: `splncs04.bst` (Springer's official style)

**For Semantic Web Journal**:
- **Format**: Author-year (Sequeda et al., 2023)
- **In-text**: "Previous work (Sequeda et al., 2023) showed..."
- **Bibliography**: Alphabetical by author last name
- **BibTeX style**: `plain.bst` or `apalike.bst`

**For arXiv**:
- **No strict requirement**: Use your target venue's style
- **Recommendation**: Springer LNCS (most common in CS)

---

### Citation Density

**Target**: 1.5-2 citations per page (for 15-page paper: 40-60 total)

**Distribution by Section**:
- **Abstract**: 0 citations
- **Introduction**: 5-10 (context, motivation)
- **Related Work**: 20-30 (bulk of citations)
- **Methodology**: 5-10 (benchmarking principles, tools)
- **Results**: 0-2 (only if comparing to prior work)
- **Discussion**: 5-10 (interpretation, comparison)
- **Conclusion**: 0-2 (future work references)

**Quality over quantity**:
- Cite seminal papers (Berners-Lee, 2001)
- Cite recent work (2020-2025)
- Cite diverse sources (not just one research group)
- Cite both academic and industry

---

### Types of Sources

**Academic Papers (60-70%)**:
- Conference papers: ISWC, ESWC, WWW, SIGMOD, VLDB
- Journal articles: Semantic Web, Journal of Web Semantics, VLDB Journal
- Workshop papers: GRADES-NDA, COLD, etc.
- ArXiv preprints: Acceptable if peer-reviewed version not yet available

**Standards & Specifications (10-15%)**:
- W3C Recommendations: SPARQL, RDF, OWL, SHACL
- LDBC benchmarks: Social Network Benchmark, Semantic Publishing
- TPC benchmarks: TPC-H, TPC-DS (for background)

**Industry Reports (10-15%)**:
- Gartner Magic Quadrants
- Forrester Wave reports
- IDC MarketScape
- Vendor whitepapers (use sparingly, potential bias)

**Technical Documentation (5-10%)**:
- Platform documentation (Neo4j, Graphwise, etc.)
- GitHub repositories (for reproducibility)
- Software versions

**Books (5-10%)**:
- "Designing and Building Enterprise Knowledge Graphs" (Sequeda & Lassila)
- "Semantic Web for the Working Ontologist" (Allemang & Hendler)
- "Graph Databases" (Robinson, Webber, Eifrem)

---

### Bibliography Management Tools

**Recommended: Zotero (Free, Open-Source)**

**Why Zotero**:
- Free and open-source
- Browser plugin: One-click import from Google Scholar, ACM DL, IEEE Xplore
- BibTeX export: Seamless LaTeX integration
- Groups: Collaborate with team
- Plugins: Better BibTeX (citation key customization)

**Setup**:
1. Install Zotero: https://www.zotero.org/
2. Install browser connector
3. Install Better BibTeX plugin
4. Create collection: "Graphwise Benchmark Paper"
5. Export → BibTeX → Auto-update

**Alternative: Mendeley**
- Similar features
- Owned by Elsevier
- Good PDF annotation
- LaTeX integration via BibTeX export

**For LaTeX Users**:
- Keep .bib file in same directory as .tex file
- Use `\bibliography{references}` in LaTeX
- Run: `pdflatex → bibtex → pdflatex → pdflatex`
- Or use Overleaf (handles compilation automatically)

**Citation Key Format**:
- Template: `authorYEARkeyword`
- Example: `sequeda2023benchmark`
- Consistent: Easier to remember when writing

---

## Figures & Visualizations

### Quality Standards

**Resolution**:
- **Minimum**: 300 DPI for raster images (PNG, JPG)
- **Preferred**: Vector graphics (PDF, SVG, EPS)
  - Scales infinitely
  - Smaller file size
  - Professional appearance
- **Tools**: matplotlib (Python), ggplot2 (R), Tableau, draw.io (diagrams)

**File Formats by Type**:
- **Charts/Graphs**: PDF (vector) from matplotlib/ggplot2
- **Diagrams**: PDF or SVG from draw.io, Lucidchart, or TikZ (LaTeX)
- **Screenshots**: PNG at 300 DPI (avoid if possible)
- **Photos**: JPG at 300 DPI (not common in CS papers)

**Sizing**:
- **Width**: Column width (8.5 cm for LNCS) or page width (17.8 cm)
- **Height**: No more than 0.6 x page height (~18 cm)
- **Font size**: 8-10 pt in figure (readable when scaled)
- **Line width**: 1-2 pt (visible but not overwhelming)

---

### Formatting Guidelines

**Chart Components**:
- ✅ **Title**: Not in figure (use caption instead)
- ✅ **Axes labels**: Clear, units specified (e.g., "Query Execution Time (ms)")
- ✅ **Legend**: Inside plot area (top-right or top-left) if space; otherwise outside
- ✅ **Grid**: Light gray, subtle (aids reading but not distracting)
- ✅ **Tick marks**: Labeled appropriately (not too dense, not too sparse)
- ✅ **Error bars**: IQR or standard error, explained in caption

**Color Palette** (Colorblind-Safe):
- **Okabe-Ito palette** (recommended):
  - Blue: `#0072B2`
  - Orange: `#E69F00`
  - Green: `#009E73`
  - Red: `#D55E00`
  - Purple: `#CC79A7`
  - Yellow: `#F0E442`
  - Cyan: `#56B4E9`
  - Black: `#000000`

- **Why**: 8% of men are colorblind (red-green most common)
- **Avoid**: Red-green combinations, rainbow gradients

**Matplotlib Example**:
```python
import matplotlib.pyplot as plt
from matplotlib import rcParams

# Set publication quality defaults
rcParams['font.size'] = 10
rcParams['font.family'] = 'serif'
rcParams['font.serif'] = ['Times New Roman']
rcParams['figure.dpi'] = 300
rcParams['savefig.dpi'] = 300
rcParams['savefig.format'] = 'pdf'

# Okabe-Ito colors
colors = ['#0072B2', '#E69F00', '#009E73', '#D55E00', '#CC79A7']

fig, ax = plt.subplots(figsize=(8, 5))
ax.bar(platforms, latencies, color=colors)
ax.set_ylabel('Median Latency (ms)')
ax.set_xlabel('Platform')
ax.grid(axis='y', alpha=0.3)
plt.tight_layout()
plt.savefig('performance_comparison.pdf')
```

**Common Chart Types**:

1. **Bar Chart**: Comparing platforms on single metric
   - Grouped bars: Multiple metrics per platform
   - Stacked bars: Breakdown of components
   - Horizontal bars: Long category names

2. **Line Chart**: Performance over time or scale
   - Multiple lines: Different platforms
   - Error bands: Confidence intervals

3. **Box Plot**: Showing distribution and outliers
   - One box per platform
   - Shows median, IQR, outliers

4. **Scatter Plot**: Correlation analysis
   - X-axis: One metric (e.g., data size)
   - Y-axis: Another metric (e.g., latency)
   - Points: Individual queries

5. **Heatmap**: Matrix of results
   - Rows: Platforms
   - Columns: Query categories
   - Color: Performance (green=good, red=bad)

6. **Radar Chart**: Multi-dimensional comparison
   - Axes: Different metrics (performance, scalability, usability)
   - Shapes: Different platforms

---

### Caption Writing

**Structure**:
```
Figure X: [One-sentence description]. [Details about axes, data, sample size].
[Explanation of visual elements like error bars, colors]. [Key takeaway].
```

**Example**:
```
Figure 3: Query execution time as dataset scales from 100K to 1B triples.
Each line represents a different platform (n=20 analytical queries per data
size). Error bars indicate 95% confidence intervals. Platform X maintains
linear scaling (slope=1.1) while Platform Y exhibits quadratic degradation
(slope=2.3) beyond 50M triples.
```

**Best Practices**:
- ✅ Standalone: Reader should understand figure without reading main text
- ✅ Descriptive: Not "Performance results" but "Query performance by platform"
- ✅ Complete: Define all acronyms, symbols, colors
- ✅ Highlight: Point out the key insight ("Platform X maintains linear scaling...")
- ✅ Sample size: Always include (n=X)

**Placement**:
- **LaTeX**: Use `\begin{figure}[t]` (top of page) or `[h]` (here)
- **Reference in text**: "Figure 3 shows that Platform X..."
- **Never**: "See figure below" (figures may float in LaTeX)
- **All figures must be referenced**: Don't include orphan figures

---

### Accessibility

**Colorblind Considerations**:
1. Use colorblind-safe palettes (Okabe-Ito, viridis, ColorBrewer)
2. Test with colorblind simulator: https://www.color-blindness.com/coblis-color-blindness-simulator/
3. Add patterns/textures in addition to color (hatching in bars)
4. Use line styles (solid, dashed, dotted) for multi-line charts

**Contrast**:
- **WCAG 2.1 Standard**: 4.5:1 contrast ratio for text
- **Charts**: Ensure foreground (data) vs. background contrast
- **Grid lines**: Light gray (#CCCCCC) on white background

**Text Readability**:
- **Font size**: Minimum 8 pt in final figure
- **Font**: Sans-serif (Helvetica, Arial) for charts; serif (Times) for diagrams
- **Labels**: Horizontal (not rotated if possible)

**Alternative Representations**:
- Provide data tables in appendix or supplementary material
- Include raw data in GitHub repository
- Screen reader friendly: Alt text for figures (if publishing HTML)

---

## Statistical Reporting

### Required Statistics

**Descriptive Statistics** (Always Report):

1. **Central Tendency**:
   - **Mean**: Average (if normally distributed)
   - **Median**: Middle value (preferred for skewed data like latency)
   - **Mode**: Most frequent value (rare in benchmarking)

2. **Variability**:
   - **Standard Deviation (SD)**: Spread around mean
   - **Interquartile Range (IQR)**: 25th to 75th percentile (robust to outliers)
   - **Range**: Min to max (shows extreme values)

3. **Sample Size**:
   - **n**: Always report (e.g., "n=30 executions per query")

**Format Example**:
```
Platform X achieved a median latency of 45 ms (IQR: 38-52 ms, n=30)
compared to Platform Y's 120 ms (IQR: 95-180 ms, n=30).
```

---

### Significance Testing

**When to Use**:
- Comparing two or more platforms
- Determining if observed differences are meaningful (not due to chance)

**Common Tests for Benchmarking**:

**1. T-Test (Two groups, normally distributed)**
- **Use case**: Compare two platforms
- **Assumption**: Normal distribution, equal variances
- **Report**: t(df) = X.XX, p = 0.XXX
- **Example**: "Platform X significantly outperformed Platform Y (t(58)=4.2, p<0.001)"

**2. Mann-Whitney U Test (Two groups, non-normal)**
- **Use case**: Compare two platforms (latency data often skewed)
- **Assumption**: None (non-parametric)
- **Report**: U = XXX, p = 0.XXX
- **Example**: "Platform X exhibited lower latency (U=1245, p=0.003)"

**3. ANOVA (Three or more groups, normally distributed)**
- **Use case**: Compare multiple platforms
- **Assumption**: Normal distribution, equal variances
- **Report**: F(df1, df2) = X.XX, p = 0.XXX
- **Follow-up**: Post-hoc tests (Tukey HSD) for pairwise comparisons

**4. Kruskal-Wallis H-Test (Three or more groups, non-normal)**
- **Use case**: Compare multiple platforms (latency)
- **Assumption**: None (non-parametric)
- **Report**: χ²(df) = XX.XX, p = 0.XXX
- **Follow-up**: Dunn's test with Bonferroni correction for pairwise

**Example**:
```
A Kruskal-Wallis H-test revealed significant differences in query latency
across platforms (χ²(6) = 234.5, p < 0.001). Pairwise comparisons using
Dunn's test with Bonferroni correction showed Platform X significantly
outperformed all others (all p < 0.01).
```

---

### Effect Sizes

**Why Report Effect Size**:
- p-value only tells if difference is statistically significant (unlikely due to chance)
- Effect size tells if difference is **practically significant** (large enough to matter)
- APA, JARS standards require effect size reporting

**Common Effect Size Measures**:

**1. Cohen's d (Standardized mean difference)**
- **Use**: Compare two groups
- **Formula**: d = (Mean1 - Mean2) / Pooled SD
- **Interpretation**:
  - Small: d = 0.2
  - Medium: d = 0.5
  - Large: d = 0.8
- **Report**: "Platform X was significantly faster (M=45 ms) than Platform Y (M=120 ms), t(58)=4.2, p<0.001, d=1.2 (large effect)"

**2. Eta-squared (η²) for ANOVA/Kruskal-Wallis**
- **Use**: Proportion of variance explained
- **Interpretation**:
  - Small: η² = 0.01
  - Medium: η² = 0.06
  - Large: η² = 0.14
- **Report**: "Platform choice explained 67% of variance in query latency (η² = 0.67)"

**3. Correlation (r) for relationships**
- **Use**: Relationship between two continuous variables
- **Example**: Data size vs. latency
- **Interpretation**:
  - Small: r = 0.1
  - Medium: r = 0.3
  - Large: r = 0.5

---

### Presentation Best Practices

**1. Report Both Descriptive and Inferential**
```
Platform X achieved a median latency of 45 ms (IQR: 38-52 ms), significantly
lower than Platform Y's 120 ms (IQR: 95-180 ms), U=1245, p=0.003, d=1.2.
```

**2. Use Confidence Intervals**
```
Platform X: Median = 45 ms, 95% CI [40, 50]
Platform Y: Median = 120 ms, 95% CI [105, 135]
```

**3. Visualize Distributions (Box Plots)**
- Shows median, IQR, outliers
- More informative than bar charts with error bars

**4. Correct for Multiple Comparisons**
- **Problem**: Testing 7 platforms pairwise = 21 comparisons
- **Issue**: 5% false positive rate × 21 tests = ~65% chance of Type I error
- **Solution**: Bonferroni correction (divide α by number of tests)
  - New α = 0.05 / 21 = 0.0024
  - Or use Dunn's test (built-in correction)

**5. Report Exact p-Values (When Possible)**
- ✅ "p = 0.003" (preferred)
- ✅ "p < 0.001" (if very small)
- ❌ "p < 0.05" (too vague)

**6. Don't Conflate Significance and Importance**
- ❌ "Platform X is significantly better" (implies both statistical and practical)
- ✅ "Platform X was statistically significantly faster (p<0.001) with a large effect size (d=1.2), representing a 2.7x improvement"

**Python Example (scipy)**:
```python
from scipy import stats
import numpy as np

# Data
platform_x = [45, 48, 42, 50, 44, ...]  # n=30
platform_y = [120, 135, 110, 150, 125, ...]  # n=30

# Descriptive statistics
print(f"Platform X: Median={np.median(platform_x)}, IQR={np.percentile(platform_x, 75) - np.percentile(platform_x, 25)}")

# Mann-Whitney U test
statistic, p_value = stats.mannwhitneyu(platform_x, platform_y, alternative='less')
print(f"U={statistic}, p={p_value:.4f}")

# Cohen's d
mean_diff = np.mean(platform_x) - np.mean(platform_y)
pooled_std = np.sqrt((np.std(platform_x)**2 + np.std(platform_y)**2) / 2)
cohens_d = mean_diff / pooled_std
print(f"Cohen's d={cohens_d:.2f}")
```

---

## Reproducibility & Ethics

### Data Availability

**Best Practice**: Make all data publicly available

**What to Share**:
1. **Benchmark datasets**:
   - RDF files (Turtle, N-Triples)
   - CSV files (for property graphs)
   - Schema/ontology files (OWL, SHACL)

2. **Query files**:
   - SPARQL queries (one file per query)
   - Cypher queries
   - Gremlin queries
   - Expected results (for validation)

3. **Raw results**:
   - CSV with all measurements
   - Columns: query_id, platform, execution_time_ms, timestamp, hardware, etc.

4. **Analysis scripts**:
   - Python/R scripts for statistical analysis
   - Jupyter notebooks with visualizations
   - Requirements.txt (dependencies)

**Where to Host**:

**Option 1: GitHub (Code + Small Data)**
- ✅ Free, unlimited public repos
- ✅ Version control (track changes)
- ✅ Issues (community can report bugs)
- ✅ Pull requests (community contributions)
- ❌ File size limit: 100 MB per file
- **Best for**: Code, queries, small datasets (<1 GB)

**Option 2: Zenodo (Large Data + DOI)**
- ✅ Free (funded by CERN)
- ✅ DOI: Permanent, citable
- ✅ Large files: Up to 50 GB per dataset
- ✅ Versioning: Upload new versions, old ones remain
- ✅ GitHub integration: Auto-archive releases
- **Best for**: Datasets, large files

**Option 3: Figshare**
- Similar to Zenodo
- Owned by Digital Science (Springer Nature)
- 20 GB per file, 20 TB total

**Option 4: University Repository**
- Check if your institution has a data repository
- Often free for affiliated researchers
- May require embargo periods

**Recommended Strategy**:
1. **GitHub**: Code, queries, analysis scripts
2. **Zenodo**: Datasets (link to GitHub)
3. **Link in paper**: "All data and code available at https://github.com/your-org/graphwise-benchmark and archived at Zenodo DOI: 10.5281/zenodo.XXXXXXX"

**Example README.md**:
```markdown
# Graphwise Semantic Layer Benchmark

## Datasets
- `data/finance/`: Finance domain (10M triples)
- `data/healthcare/`: Healthcare domain (10M triples)
- `data/lifesciences/`: Life sciences domain (10M triples)

## Queries
- `queries/sparql/`: SPARQL queries (RDF platforms)
- `queries/cypher/`: Cypher queries (Neo4j)
- `queries/gremlin/`: Gremlin queries (Neptune PG)

## Results
- `results/raw/`: Raw CSV files (all measurements)
- `results/analysis/`: Jupyter notebooks

## Reproduction
1. Install dependencies: `pip install -r requirements.txt`
2. Deploy platforms: See `deployment/` directory
3. Load data: `python load_data.py --platform graphwise`
4. Run benchmark: `python run_benchmark.py --platform graphwise`
5. Analyze: `jupyter notebook analysis.ipynb`

## Citation
If you use this benchmark, please cite:
[BibTeX entry]
```

---

### Code Availability

**What to Share**:
1. **Benchmark harness**: Python/Java script that runs queries
2. **Data generators**: Scripts to create synthetic data
3. **Platform deployment**: Docker Compose, Kubernetes configs
4. **Analysis code**: Statistical tests, figure generation

**Best Practices**:
- ✅ **README**: Clear instructions to reproduce
- ✅ **Requirements**: Python: requirements.txt; R: sessionInfo()
- ✅ **Version pins**: Exact versions (numpy==1.24.3, not numpy>=1.0)
- ✅ **Docker**: Containerize for reproducibility
- ✅ **License**: Choose open-source license (MIT, Apache 2.0, GPL)

**License Recommendations**:
- **MIT**: Permissive, allows commercial use
- **Apache 2.0**: Permissive, includes patent grant
- **GPL v3**: Copyleft, requires derivatives to be open-source
- **CC BY 4.0**: For datasets/documentation (not code)

**Example License Header**:
```python
# Copyright (c) 2025 University of Washington Team
# Licensed under the MIT License
# See LICENSE file in the project root for full license information.
```

---

### Vendor Neutrality

**Why It Matters**:
- Benchmarking is susceptible to bias (vendor-funded studies often favor sponsor)
- Academic credibility requires objectivity
- Community trust depends on transparency

**Best Practices**:

**1. Disclose Funding**:
```
Acknowledgments: This research was conducted in collaboration with Graphwise.
The authors maintained full editorial control, and Graphwise did not influence
the selection of competing platforms, benchmark design, or interpretation of results.
```

**2. Test All Platforms Equally**:
- Same hardware, same configuration approach
- No vendor-specific tuning (unless done for all)
- Document any platform-specific settings

**3. Report All Results**:
- Don't cherry-pick favorable results
- Include cases where sponsored platform underperforms
- Acknowledge strengths of competitors

**4. Independent Review**:
- Have non-Graphwise researchers review methodology
- Invite vendor feedback (optional): Share results pre-publication, allow corrections

**5. Avoid Marketing Language**:
- ❌ "Graphwise is the best platform for enterprises"
- ✅ "Graphwise achieved lowest latency for reasoning queries (180 ms median)"

**6. Conflict of Interest Statement**:
```
Conflicts of Interest: This research was partially funded by Graphwise. The
lead author has no financial relationship with Graphwise. Co-authors [names]
consulted for Graphwise during the project period but did not participate in
data collection or statistical analysis.
```

---

### Open Science Practices

**What is Open Science**:
- Transparent, reproducible, accessible research
- Open access publications (no paywalls)
- Open data (public datasets)
- Open source (public code)

**Benefits**:
- Higher citations (open access papers cited 30-50% more)
- Community validation (others can check your work)
- Industry impact (practitioners can use benchmark)
- Accelerates science (build on each other's work)

**How to Implement**:

**1. Open Access Publication**:
- **Option 1**: arXiv preprint (free, immediate)
- **Option 2**: Open access journal (Semantic Web Journal, MDPI Sensors)
- **Option 3**: Conference + arXiv (conference for prestige, arXiv for access)
- **Option 4**: Pay open access fee (~$2,000-$3,000 for Springer/Elsevier)

**2. Open Data**:
- Upload to Zenodo or Figshare (with DOI)
- Use open license: CC BY 4.0 (attribution required)

**3. Open Source**:
- GitHub public repository
- MIT or Apache 2.0 license

**4. Pre-registration** (Advanced):
- Register study design before data collection
- Prevents p-hacking and HARKing (Hypothesizing After Results Known)
- Platform: Open Science Framework (OSF)

---

### Ethical Considerations

**Research Ethics Checklist**:

**1. Human Subjects**: Not applicable (benchmarking study, no human data)

**2. Data Privacy**:
- If using real enterprise data (with permission): Anonymize, remove PII
- If synthetic data: Not applicable

**3. Vendor Relationships**:
- Disclose any financial relationships
- Maintain editorial independence
- Report all results (favorable and unfavorable)

**4. Environmental Impact**:
- Large-scale benchmarks consume energy
- Consider: "We acknowledge the carbon footprint of this study. All experiments ran on AWS data centers powered by 100% renewable energy."

**5. Dual Use**:
- Could benchmark be used maliciously? (e.g., to identify vulnerabilities)
- Mitigation: Responsible disclosure to vendors before publication

**6. Authorship**:
- **First author**: Primary contributor (writing, experiments)
- **Middle authors**: Significant contributions (design, analysis, review)
- **Last author**: PI or senior advisor (funding, oversight)
- **Acknowledgments**: Minor contributions (technical support, funding)

**7. Citation Ethics**:
- Cite all influences (no plagiarism)
- Don't over-cite own work (citation padding)
- Don't cite irrelevant papers (for favor)

---

## Benchmarking Paper Examples

### Example 1: Sequeda et al. (2023) - Knowledge Graphs & LLMs

**Title**: "A Benchmark to Understand the Role of Knowledge Graphs on Large Language Model's Accuracy for Question Answering on Enterprise SQL Databases"

**Key Characteristics**:
- **Domain**: Enterprise SQL + Knowledge Graphs
- **Platforms**: SQL (baseline) vs. SPARQL (KG)
- **Metrics**: Accuracy (primary), partial accuracy
- **Scale**: 43 questions, insurance domain
- **Findings**: 16% (SQL) → 54% (KG), 238% improvement

**Strengths**:
- Clear problem statement (LLM accuracy)
- Real enterprise scenario (insurance)
- Transparent methodology (dates, question count, LLM version)
- Open access (arXiv + workshop)
- Reproducible (benchmark framework described)

**What We Learn**:
- Industry-relevant problem attracts citations
- Explicit research questions (RQ1, RQ2) structure paper clearly
- Quantified improvement (238%) is compelling headline
- Open access (CC BY 4.0) enables broad dissemination

**How We'll Adapt**:
- Broader scope: Multiple platforms (not just SQL vs. KG)
- More metrics: Performance + expressiveness + usability
- Larger scale: 50 queries, 3 domains

---

### Example 2: LDBC Social Network Benchmark

**Title**: "The LDBC Social Network Benchmark" (Angles et al., 2020+)

**Key Characteristics**:
- **Domain**: Social network (Facebook-like)
- **Platforms**: Property graph databases (Neo4j, TigerGraph, JanusGraph)
- **Workloads**: Interactive (OLTP), Business Intelligence (OLAP), Graph Analytics
- **Scale**: Scalable data generator (1 GB to 1 TB+)
- **Community**: LDBC consortium (vendors + researchers)

**Strengths**:
- Standardized benchmark (widely adopted)
- Three workload types (comprehensive)
- Realistic data distribution (power laws, temporal patterns)
- Audited results (vendors submit, LDBC verifies)
- Multiple papers (benchmark design, results, updates)

**Limitations**:
- Property graphs only (no RDF)
- Social network domain (not generalizable to all use cases)
- Vendor-driven (potential bias, though audited)

**What We Learn**:
- Standardization drives adoption (everyone uses LDBC now)
- Multiple workload types increase relevance
- Community buy-in (vendors participate willingly)
- Audited results ensure fairness

**How We'll Adapt**:
- Include both RDF and property graphs
- Multiple domains (finance, healthcare, life sciences)
- Open community validation (publish code, invite vendor feedback)

---

### Example 3: Berlin SPARQL Benchmark (BSBM)

**Title**: "The Berlin SPARQL Benchmark" (Bizer & Schultz, 2009)

**Key Characteristics**:
- **Domain**: E-commerce (products, vendors, reviews)
- **Platforms**: RDF stores (Virtuoso, Jena, Sesame, etc.)
- **Queries**: 12 SPARQL queries (mix of SELECT, DESCRIBE, CONSTRUCT)
- **Scale**: Configurable (1K to 100M products)
- **Tool**: Data generator + benchmark driver

**Strengths**:
- First widely-adopted SPARQL benchmark
- Simple, understandable domain (e-commerce)
- Configurable scale (test small to large)
- Tool support (automated benchmark)

**Limitations**:
- Dated (2009, pre-SPARQL 1.1)
- Simple schema (doesn't test complex queries)
- No reasoning queries
- Single domain

**What We Learn**:
- Simple domain is accessible (everyone understands e-commerce)
- Tool support is critical (manual benchmarking is error-prone)
- Scalability testing requires data generator
- Community needs standardized benchmarks (BSBM filled gap)

**How We'll Adapt**:
- Multiple domains (not just e-commerce)
- Include reasoning queries (BSBM doesn't)
- Modern SPARQL features (SPARQL 1.1, GeoSPARQL)
- Cross-paradigm (BSBM is RDF-only)

---

### Example 4: Graph Database Performance Comparison (2023)

**Title**: "Experimental Evaluation of Graph Databases: JanusGraph, Nebula Graph, Neo4j, and TigerGraph" (MDPI Applied Sciences, 2023)

**Key Characteristics**:
- **Platforms**: 4 property graph databases
- **Benchmark**: LDBC Social Network Benchmark (SNB)
- **Metrics**: Query execution time, node load time, memory usage, CPU usage
- **Scale**: SF-1 (1 GB) to SF-10 (10 GB)
- **Workloads**: LDBC SNB Interactive (OLTP-style)

**Findings**:
- Neo4j: Best overall performance
- TigerGraph: Best for analytics queries
- JanusGraph, Nebula: Good for distributed deployments
- Memory: Critical factor (all platforms struggle when exceeding RAM)

**Strengths**:
- Uses standardized benchmark (LDBC SNB)
- Multiple platforms (fair comparison)
- Multiple metrics (not just query time)
- Statistical analysis (means, error bars)

**Limitations**:
- Property graphs only (no RDF)
- Single domain (social network)
- Limited query types (LDBC SNB Interactive, not BI or analytics)
- No reasoning evaluation

**What We Learn**:
- Standardized benchmarks enable comparison
- Multiple metrics paint fuller picture
- Hardware matters (memory bottleneck is common)
- No single "best" platform (depends on workload)

**How We'll Adapt**:
- Include RDF platforms
- Multiple domains and query types
- Reasoning as differentiator (property graphs can't do this)
- Cloud deployment (managed services)

---

### Example 5: RDF Store Evaluation (Journal of Big Data, 2021)

**Title**: "An empirical study on the evaluation of the RDF storage systems" (Journal of Big Data, 2021)

**Key Characteristics**:
- **Platforms**: 7 RDF stores (Virtuoso, GraphDB, Stardog, AllegroGraph, etc.)
- **Benchmarks**: BSBM, LUBM, WatDiv, DBpedia
- **Metrics**: Load time, query time, storage size
- **Scale**: 1M to 100M triples
- **Analysis**: Statistical tests (ANOVA)

**Findings**:
- Virtuoso: Fastest for simple queries
- GraphDB: Best for complex queries
- Stardog: Best reasoning performance
- Trade-offs: Load time vs. query time (indexing overhead)

**Strengths**:
- Multiple benchmarks (tests diverse scenarios)
- Statistical rigor (ANOVA, post-hoc tests)
- Multiple metrics (not just query time)
- Open source platforms (reproducible)

**Limitations**:
- RDF only (no property graphs)
- Older versions (2021, platforms have updated)
- No reasoning evaluation (despite mentioning Stardog)
- No enterprise integration complexity

**What We Learn**:
- Multiple benchmarks increase generalizability
- Statistical testing is expected
- Trade-offs exist (no universal winner)
- Need to update periodically (software evolves)

**How We'll Adapt**:
- Cross-paradigm (RDF + property graphs)
- Include reasoning explicitly
- Recent versions (2024-2025)
- Enterprise integration complexity (not just performance)

---

### Common Patterns Across Examples

**1. Clear Scope**:
- All papers define what they test (platforms, workloads, metrics)
- Explicit limitations (what's not tested)

**2. Standardized Benchmarks**:
- LDBC, BSBM, LUBM widely used
- Enables comparison across studies

**3. Multiple Metrics**:
- Not just query time: Load time, memory, CPU, scalability
- Multi-dimensional view of performance

**4. Statistical Rigor** (Varies):
- Older papers: Descriptive stats only (means, error bars)
- Recent papers: Inferential stats (ANOVA, t-tests)
- Trend: Increasing rigor over time

**5. Open Access** (Increasing):
- Sequeda et al.: arXiv (free)
- MDPI: Open access journal
- LDBC: Technical reports + papers
- Trend: More open science

**6. Tool Support**:
- BSBM: Data generator + benchmark driver
- LDBC: Data generator + workload drivers
- Community adoption requires tools (not just paper)

**7. Vendor Engagement** (Mixed):
- LDBC: Vendors participate, submit results
- Academic papers: Independent evaluation
- Trade-off: Vendor engagement vs. neutrality

---

## Writing Timeline

### Phase-by-Phase Breakdown

**Total Duration**: 4-6 months (for comprehensive benchmark paper)

---

#### Phase 1: Literature Review & Planning (Weeks 1-3)

**Activities**:
- Read 40-60 papers (related work)
- Organize citations in Zotero
- Draft research questions
- Design benchmark methodology
- Select platforms to test
- Obtain vendor licenses/access

**Deliverables**:
- Annotated bibliography (Zotero collection)
- Research questions document (RQ1, RQ2, RQ3)
- Benchmark design document (queries, metrics, hardware)
- Platform access confirmed

**Team Responsibilities**:
- **Rahil**: Literature review (semantic web, LLMs, GraphRAG)
- **Mathew**: Infrastructure setup (AWS, Docker, platform deployment)
- **Shreyas**: Benchmark design (queries, metrics, KPIs)
- **Siddarth**: Tool development (benchmark harness, data generator)

**Milestones**:
- Week 1: 20 papers read
- Week 2: 40 papers read, RQs drafted
- Week 3: Methodology finalized, platforms selected

---

#### Phase 2: Experiment Design & Data Preparation (Weeks 4-6)

**Activities**:
- Deploy platforms (7 platforms × ~4 hours each)
- Generate benchmark data (3 domains × 3 scales)
- Implement queries (50 queries × 5 languages)
- Validate data integrity
- Pilot test (run 5 queries to verify setup)

**Deliverables**:
- All platforms deployed and configured
- Benchmark datasets (finance, healthcare, life sciences)
- Query repository (SPARQL, Cypher, Gremlin, FlureeQL)
- Pilot results (smoke test)

**Team Responsibilities**:
- **Mathew**: Platform deployment, Docker Compose configs
- **Siddarth**: Data generation scripts, schema design
- **Shreyas**: Query implementation, translation across languages
- **Rahil**: Validation, documentation

**Milestones**:
- Week 4: 3 platforms deployed
- Week 5: All 7 platforms deployed, data generated
- Week 6: Queries implemented, pilot test successful

---

#### Phase 3: Data Collection & Benchmarking (Weeks 7-10)

**Activities**:
- Run full benchmark (50 queries × 7 platforms × 3 scales × 30 executions = 31,500 query runs!)
- Monitor for errors, re-run failed executions
- Collect logs (execution times, resource usage)
- Organize data (CSV files, database)
- Preliminary analysis (sanity checks)

**Deliverables**:
- Raw results CSV (all measurements)
- Execution logs (timestamps, errors)
- Data quality report (missing values, outliers)

**Team Responsibilities**:
- **Mathew**: Benchmark execution, infrastructure monitoring
- **Siddarth**: Automation, error handling, logging
- **Shreyas**: Data organization, preliminary analysis
- **Rahil**: Quality assurance, issue triage

**Milestones**:
- Week 7: Small-scale benchmarks complete
- Week 8: Medium-scale benchmarks complete
- Week 9: Large-scale benchmarks complete
- Week 10: All data collected, validated

**Note**: This is the most time-consuming phase. Can parallelize by running multiple platforms simultaneously (if hardware permits).

---

#### Phase 4: Statistical Analysis & Visualization (Weeks 11-12)

**Activities**:
- Descriptive statistics (medians, IQRs, ranges)
- Inferential statistics (Kruskal-Wallis, Dunn's test, effect sizes)
- Create figures (bar charts, line charts, box plots)
- Create tables (summary tables, comparison matrices)
- Interpret results (identify patterns, winners, trade-offs)

**Deliverables**:
- Statistical analysis report (Python/R notebook)
- All figures (PDF, 300 DPI, colorblind-safe)
- All tables (LaTeX format)
- Key findings summary (bullet points)

**Team Responsibilities**:
- **Shreyas**: Statistical analysis (scipy, pandas)
- **Siddarth**: Visualization (matplotlib, seaborn)
- **Rahil**: Interpretation, findings writeup
- **Mathew**: Review, sanity checks

**Milestones**:
- Week 11: Descriptive stats complete, figures drafted
- Week 12: Inferential stats complete, all visuals finalized

---

#### Phase 5: Writing First Draft (Weeks 13-16)

**Activities**:
- Write all sections (Abstract, Intro, Related Work, Methodology, Results, Discussion, Conclusion)
- Integrate figures and tables
- Write captions
- Compile references (BibTeX)
- Internal review (team reads each section)

**Deliverables**:
- Full first draft (15-20 pages)
- All sections complete (no TODOs)
- Figures and tables integrated
- References compiled

**Team Responsibilities**:
- **Rahil**: Abstract, Introduction, Discussion, Conclusion (4 pages)
- **Shreyas**: Related Work, Methodology (6 pages)
- **Mathew**: Experimental Setup (2 pages)
- **Siddarth**: Results (5 pages)
- **All**: Review each other's sections

**Milestones**:
- Week 13: Abstract, Introduction, Related Work drafted
- Week 14: Methodology, Experimental Setup drafted
- Week 15: Results, Discussion drafted
- Week 16: Conclusion drafted, full draft compiled

**Writing Schedule** (Week 13-16 Detail):
- **Week 13**:
  - Mon-Tue: Abstract, Introduction (Rahil)
  - Wed-Fri: Related Work (Shreyas)
- **Week 14**:
  - Mon-Wed: Methodology (Shreyas)
  - Thu-Fri: Experimental Setup (Mathew)
- **Week 15**:
  - Mon-Thu: Results (Siddarth)
  - Fri: Discussion (Rahil)
- **Week 16**:
  - Mon: Conclusion (Rahil)
  - Tue-Wed: Integration, formatting
  - Thu-Fri: Internal review

---

#### Phase 6: Revision & Refinement (Weeks 17-18)

**Activities**:
- Address internal review feedback
- Improve clarity (simplify complex sentences)
- Strengthen arguments (add citations, data)
- Proofread (grammar, typos, consistency)
- Check formatting (LNCS template, page limits)
- Run plagiarism check (Turnitin, iThenticate)

**Deliverables**:
- Revised draft (incorporates all feedback)
- Proofread (zero typos)
- Formatted (ready for submission)

**Team Responsibilities**:
- **All**: Address feedback for their sections
- **Rahil**: Overall coherence, storytelling
- **Shreyas**: Fact-checking, citation accuracy
- **Siddarth**: Figure/table consistency
- **Mathew**: Reproducibility checklist

**Milestones**:
- Week 17: Major revisions complete
- Week 18: Proofreading complete, formatting finalized

---

#### Phase 7: Pre-Submission Preparation (Week 19)

**Activities**:
- Upload to arXiv (preprint)
- Obtain DOI for datasets (Zenodo)
- Finalize GitHub repository (code, data, README)
- Prepare supplementary materials (if required)
- Write cover letter (if journal submission)
- Double-check submission requirements

**Deliverables**:
- arXiv preprint (live URL)
- Zenodo dataset (DOI)
- GitHub repository (public)
- Submission package (paper + supplementary)

**Team Responsibilities**:
- **Siddarth**: GitHub cleanup, documentation
- **Mathew**: Zenodo upload, data packaging
- **Shreyas**: Supplementary materials
- **Rahil**: arXiv submission, cover letter

**Milestones**:
- arXiv preprint live
- Zenodo DOI obtained
- GitHub repository public
- Ready for conference/journal submission

---

#### Phase 8: Submission & Peer Review Response (Weeks 20-24+)

**Activities**:
- Submit to conference (ESWC or ISWC) or journal
- Wait for reviews (6-12 weeks typically)
- Respond to reviewer comments
- Revise manuscript
- Resubmit (if minor revisions) or appeal (if rejected)

**Deliverables**:
- Submitted manuscript
- Reviewer response letter (if revisions)
- Revised manuscript (if accepted with revisions)

**Team Responsibilities**:
- **All**: Respond to reviewer comments for their sections
- **Rahil**: Draft response letter
- **Shreyas**: Coordinate revisions

**Timeline** (Variable):
- **Conference**:
  - Week 20: Submit to ESWC (Nov/Dec deadline)
  - Week 30: Reviews received (Feb/Mar)
  - Week 32: Revisions submitted (if required)
  - Week 34: Camera-ready (if accepted)
  - Week 44: Conference presentation (May/Jun)

- **Journal**:
  - Week 20: Submit to Semantic Web Journal
  - Week 26: First review (6-8 weeks)
  - Week 28: Revise & resubmit
  - Week 34: Second review (4-6 weeks)
  - Week 36: Accepted
  - Week 40: Published online

**Note**: Peer review is unpredictable. Budget 3-6 months for full publication cycle.

---

### Milestones Summary

| Week | Phase | Milestone | Owner |
|------|-------|-----------|-------|
| 1-3 | Literature Review | RQs finalized, platforms selected | All |
| 4-6 | Experiment Design | Platforms deployed, queries implemented | Mathew, Siddarth |
| 7-10 | Data Collection | All benchmark runs complete | Mathew, Shreyas |
| 11-12 | Analysis | Statistical analysis, figures finalized | Shreyas, Siddarth |
| 13-16 | Writing | First draft complete | All |
| 17-18 | Revision | Proofread, formatted draft | All |
| 19 | Pre-Submission | arXiv live, GitHub public, Zenodo DOI | Siddarth, Mathew |
| 20 | Submission | Submitted to conference/journal | Rahil |
| 20-24+ | Peer Review | Respond to reviews, revise | All |

---

### Realistic Timeline Adjustments

**If Faster (3 months)**:
- Reduce scope: 3 platforms instead of 7
- Fewer queries: 25 instead of 50
- Single domain: Finance only
- Trade-off: Less comprehensive, but faster to publish

**If Slower (9-12 months)**:
- Add qualitative evaluation (user studies, expert interviews)
- Include cost analysis (cloud pricing)
- Test on real enterprise data (requires partnerships)
- Multiple benchmark frameworks (LDBC + BSBM + custom)
- Trade-off: More comprehensive, higher impact, but longer timeline

**Recommended for Graphwise**:
- **6 months**: Balanced (comprehensive but achievable)
- **Target submission**: ESWC 2026 (Nov/Dec 2025 deadline) or ISWC 2026 (May/Jun 2026 deadline)
- **arXiv preprint**: Month 5 (get early visibility)

---

### Team Responsibilities (Recap)

**Rahil** (Product Manager & AI/ML Lead):
- Project management (timeline, milestones)
- Writing (Abstract, Introduction, Discussion, Conclusion)
- Literature review (semantic web, LLMs, GraphRAG)
- Submission process (arXiv, conference)

**Mathew** (Cloud & Data Engineering Lead):
- Infrastructure (AWS, Docker, platform deployment)
- Benchmark execution (run queries, monitor)
- Data packaging (Zenodo upload)
- Experimental setup writing

**Shreyas** (Operations & Analytics Lead):
- Benchmark design (queries, metrics, KPIs)
- Statistical analysis (scipy, pandas)
- Related work & methodology writing
- Query implementation (SPARQL, Cypher)

**Siddarth** (Software Engineering & AI Systems Lead):
- Tool development (benchmark harness, data generator)
- Automation (scripts, error handling)
- Visualization (matplotlib, figures)
- GitHub repository (documentation, code cleanup)
- Results section writing

---

## Quality Checklist

Use this checklist before submission to ensure academic quality:

### Content Quality

- [ ] **Clear research question**: RQ1, RQ2, RQ3 explicitly stated
- [ ] **Comprehensive literature review**: 40-60 recent + foundational citations
- [ ] **Reproducible methodology**: Someone can replicate from paper alone
- [ ] **Rigorous statistical analysis**: Descriptive + inferential stats, effect sizes
- [ ] **Professional figures and tables**: Vector graphics, colorblind-safe, 300 DPI
- [ ] **Proper citations**: All claims cited, BibTeX formatted correctly
- [ ] **Limitations discussed**: Honest about scope, threats to validity
- [ ] **Future work outlined**: Specific next steps, not vague
- [ ] **Accessible to non-experts**: Introduction understandable to general CS audience
- [ ] **Proofread**: Zero typos, grammar errors, formatting inconsistencies

### Reproducibility

- [ ] **Data available**: Uploaded to Zenodo with DOI
- [ ] **Code available**: Public GitHub repository
- [ ] **README**: Clear instructions to reproduce results
- [ ] **Version numbers**: All software versions documented
- [ ] **Hardware specs**: Cloud instance type, OS, memory, CPU
- [ ] **Random seeds**: Documented (if applicable)
- [ ] **Configuration files**: Docker Compose, Kubernetes configs, platform settings
- [ ] **Expected results**: Validation data provided (for sanity checks)

### Writing Quality

- [ ] **Abstract**: 150-250 words, standalone, no citations, one key number
- [ ] **Introduction**: Broad → narrow, RQs, contributions, roadmap
- [ ] **Related Work**: Thematic, critical, gap analysis, synthesis table
- [ ] **Methodology**: Reproducible, justified, threats to validity
- [ ] **Results**: Figures first, descriptive + inferential stats, no interpretation
- [ ] **Discussion**: Interpret, compare, implications, limitations
- [ ] **Conclusion**: Summarize, no new info, future work
- [ ] **Consistent terminology**: Knowledge graph vs. semantic graph (pick one)
- [ ] **Active voice**: "We designed" not "was designed"
- [ ] **Quantified claims**: "35% faster" not "much faster"

### Figures & Tables

- [ ] **All figures referenced in text**: "Figure 3 shows..."
- [ ] **Standalone captions**: Readable without main text
- [ ] **Vector graphics**: PDF for charts, PNG at 300 DPI for screenshots
- [ ] **Colorblind-safe**: Okabe-Ito palette or similar
- [ ] **Consistent styling**: Same fonts, colors across figures
- [ ] **Readable labels**: 8-10 pt font size minimum
- [ ] **Error bars explained**: IQR, 95% CI, or std dev specified in caption
- [ ] **Sample sizes reported**: (n=30) in caption or axis label

### Statistical Rigor

- [ ] **Descriptive stats**: Median, IQR (or mean, SD if normal)
- [ ] **Sample sizes**: Always reported (n=X)
- [ ] **Significance tests**: Kruskal-Wallis, Dunn's, or appropriate test
- [ ] **p-values reported**: Exact (p=0.003) or bounded (p<0.001)
- [ ] **Effect sizes**: Cohen's d, η², or correlation (r)
- [ ] **Multiple comparisons corrected**: Bonferroni, Dunn's, or similar
- [ ] **Confidence intervals**: 95% CI for key results
- [ ] **Assumptions checked**: Normality (if parametric test), outliers handled

### Ethics & Transparency

- [ ] **Conflict of interest disclosed**: Graphwise funding acknowledged
- [ ] **Vendor neutrality maintained**: All platforms tested equally
- [ ] **All results reported**: Including cases where sponsored platform underperforms
- [ ] **Data privacy**: No PII (if real data used)
- [ ] **Open access**: arXiv preprint or OA journal
- [ ] **License specified**: MIT/Apache for code, CC BY for data
- [ ] **Authorship justified**: All authors contributed substantially

### Formatting & Submission

- [ ] **Page limit**: 15 pages (LNCS) or journal guidelines
- [ ] **Template**: Springer LNCS or journal template applied
- [ ] **Margins**: Per template (typically 1 inch)
- [ ] **Font**: Per template (typically Times 10-11 pt)
- [ ] **References formatted**: BibTeX with correct .bst file
- [ ] **Supplementary materials**: Prepared (if required)
- [ ] **Anonymization**: Author info removed (if double-blind)
- [ ] **PDF generated**: Compiles without errors
- [ ] **File size**: Under conference limit (typically 10-15 MB)

### Pre-Submission

- [ ] **Internal review**: All team members read full paper
- [ ] **External review** (optional): Advisor or colleague reads
- [ ] **Plagiarism check**: Turnitin or iThenticate (<15% similarity)
- [ ] **arXiv preprint**: Uploaded and live
- [ ] **GitHub repository**: Public, README complete
- [ ] **Zenodo dataset**: Uploaded with DOI
- [ ] **Cover letter**: Written (if journal)
- [ ] **Submission checklist**: Conference/journal requirements met

---

## Recommended Tools

### Writing: LaTeX with Overleaf

**LaTeX**:
- Industry standard for academic CS papers
- Superior typesetting (equations, figures, references)
- BibTeX integration (automatic bibliography)
- Templates available (LNCS, ACM, IEEE)

**Overleaf**:
- Online LaTeX editor (no local installation)
- Real-time collaboration (like Google Docs for LaTeX)
- Version history (track changes)
- Rich text mode (for non-LaTeX users)
- Zotero/Mendeley integration

**Setup**:
1. Create Overleaf account: https://www.overleaf.com/
2. Select template: Gallery → Conference → Springer LNCS
3. Share with team: Share → Add collaborators
4. Connect Zotero: Account → Integrations → Zotero

**Alternative: Microsoft Word**
- If team uncomfortable with LaTeX
- Springer provides Word template
- Trade-off: Less professional typography, manual reference management

---

### Figures: matplotlib (Python) or ggplot2 (R)

**matplotlib (Python)**:

```python
import matplotlib.pyplot as plt
import numpy as np

# Set publication quality
plt.rcParams['font.size'] = 10
plt.rcParams['font.family'] = 'serif'
plt.rcParams['figure.dpi'] = 300

# Okabe-Ito colors
colors = ['#0072B2', '#E69F00', '#009E73', '#D55E00']

# Create figure
fig, ax = plt.subplots(figsize=(8, 5))
platforms = ['Graphwise', 'Neptune', 'Stardog', 'Neo4j']
latencies = [45, 80, 120, 60]

ax.bar(platforms, latencies, color=colors)
ax.set_ylabel('Median Latency (ms)')
ax.set_xlabel('Platform')
ax.set_title('Query Performance Comparison')
ax.grid(axis='y', alpha=0.3)

plt.tight_layout()
plt.savefig('performance.pdf')  # Vector format
```

**ggplot2 (R)**:

```r
library(ggplot2)

data <- data.frame(
  platform = c('Graphwise', 'Neptune', 'Stardog', 'Neo4j'),
  latency = c(45, 80, 120, 60)
)

ggplot(data, aes(x=platform, y=latency, fill=platform)) +
  geom_bar(stat='identity') +
  scale_fill_manual(values=c('#0072B2', '#E69F00', '#009E73', '#D55E00')) +
  labs(x='Platform', y='Median Latency (ms)', title='Query Performance') +
  theme_minimal() +
  theme(text = element_text(size=10, family='serif'))

ggsave('performance.pdf', width=8, height=5, units='in', dpi=300)
```

**Alternative: Tableau**
- Easier for non-programmers
- Interactive dashboards
- Export to PDF/PNG for paper
- Trade-off: Less customization, not scriptable

---

### Bibliography: Zotero + Better BibTeX

**Zotero**:
- Free, open-source reference manager
- Browser plugin: Import papers with one click
- Organize into collections (folders)
- Sync across devices

**Better BibTeX Plugin**:
- Automatic BibTeX export
- Customizable citation keys (e.g., `sequeda2023benchmark`)
- Auto-update .bib file when Zotero updated

**Setup**:
1. Install Zotero: https://www.zotero.org/download/
2. Install browser connector
3. Install Better BibTeX: https://retorque.re/zotero-better-bibtex/
4. Create collection: "Graphwise Benchmark Paper"
5. Export: Right-click collection → Export → Better BibTeX → Keep updated
6. Use in LaTeX: `\bibliography{references.bib}`

**Workflow**:
1. Find paper on Google Scholar
2. Click Zotero browser icon (imports to Zotero)
3. .bib file auto-updates
4. Cite in LaTeX: `\cite{sequeda2023benchmark}`
5. BibTeX auto-generates bibliography

**Alternative: Mendeley**
- Similar features, owned by Elsevier
- Good PDF annotation
- LaTeX integration via BibTeX export

---

### Collaboration: Overleaf + GitHub

**Overleaf** (LaTeX editing):
- Real-time collaboration (multiple authors simultaneously)
- Version history (track changes)
- Rich text mode (for non-LaTeX users)
- Compile online (no local LaTeX installation)

**GitHub** (Code + Data):
- Version control (git)
- Issues (track tasks, bugs)
- Pull requests (code review)
- Releases (stable versions)
- GitHub Pages (host documentation)

**Integration**:
- Overleaf ↔ GitHub sync (push LaTeX to GitHub for backup)
- GitHub repo: Code, data, queries, analysis scripts
- Overleaf: Paper writing

**Alternative: Google Docs**
- If team prefers Word-like interface
- Real-time collaboration
- Comments and suggestions
- Trade-off: Less professional formatting, manual reference management

---

### Statistical Analysis: Python (scipy, pandas) or R

**Python** (scipy, pandas, statsmodels):

```python
import pandas as pd
from scipy import stats
import numpy as np

# Load data
df = pd.read_csv('results.csv')

# Descriptive statistics
print(df.groupby('platform')['latency_ms'].describe())

# Kruskal-Wallis test (non-parametric ANOVA)
platforms = df['platform'].unique()
groups = [df[df['platform']==p]['latency_ms'] for p in platforms]
h_stat, p_value = stats.kruskal(*groups)
print(f"Kruskal-Wallis: H={h_stat:.2f}, p={p_value:.4f}")

# Pairwise comparisons (Dunn's test)
from scikit_posthocs import posthoc_dunn
dunn_results = posthoc_dunn(df, val_col='latency_ms', group_col='platform', p_adjust='bonferroni')
print(dunn_results)

# Effect size (eta-squared)
# (Calculate manually or use statsmodels)
```

**R** (stats, ggplot2):

```r
library(dplyr)
library(ggplot2)

# Load data
df <- read.csv('results.csv')

# Descriptive statistics
df %>% group_by(platform) %>% summarise(
  median = median(latency_ms),
  iqr = IQR(latency_ms),
  n = n()
)

# Kruskal-Wallis test
kruskal.test(latency_ms ~ platform, data=df)

# Pairwise Dunn's test
library(FSA)
dunnTest(latency_ms ~ platform, data=df, method='bonferroni')
```

**Recommended**: Python (team already familiar, good for data pipelines)

---

### Reproducibility: Docker + Jupyter Notebooks

**Docker**:
- Containerize benchmark environment
- Ensures consistent setup across machines
- Dockerfile: Specifies all dependencies

**Example Dockerfile**:
```dockerfile
FROM python:3.10

# Install dependencies
RUN pip install pandas scipy matplotlib jupyter

# Copy benchmark code
COPY . /benchmark
WORKDIR /benchmark

# Run Jupyter
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--allow-root"]
```

**Jupyter Notebooks**:
- Interactive analysis (code + results + explanations)
- Publish on GitHub (rendered automatically)
- Include in supplementary materials

**Workflow**:
1. Develop analysis in Jupyter notebook
2. Generate figures, tables
3. Export key figures to PDF (for paper)
4. Publish notebook on GitHub (for reproducibility)

---

## Sources

### Academic Papers

1. Sequeda, J., Allemang, D., Jacob, B. (2023). A Benchmark to Understand the Role of Knowledge Graphs on Large Language Model's Accuracy for Question Answering on Enterprise SQL Databases. arXiv:2311.07509.

2. Angles, R., et al. (2020). The LDBC Social Network Benchmark. arXiv:2001.02299.

3. Bizer, C., Schultz, A. (2009). The Berlin SPARQL Benchmark. International Journal on Semantic Web and Information Systems, 5(2), 1-24.

4. Aluç, G., Hartig, O., Özsu, M. T., Daudjee, K. (2014). Diversified Stress Testing of RDF Data Management Systems. ISWC 2014.

5. Journal of Big Data (2021). An empirical study on the evaluation of the RDF storage systems.

6. MDPI Applied Sciences (2023). Experimental Evaluation of Graph Databases: JanusGraph, Nebula Graph, Neo4j, and TigerGraph.

### Conference & Journal Guidelines

7. ISWC 2024: Call for Papers. https://iswc.umbc.edu/

8. ESWC 2024: Resources Track Guidelines. https://2024.eswc-conferences.org/

9. Semantic Web Journal: Author Guidelines. https://www.semantic-web-journal.net/authors

10. Journal of Web Semantics: Guide for Authors. https://www.websemanticsjournal.org/

11. Springer LNCS: Author Instructions. https://www.springer.com/gp/computer-science/lncs

### Standards & Specifications

12. W3C (2013). SPARQL 1.1 Query Language. https://www.w3.org/TR/sparql11-query/

13. W3C (2012). OWL 2 Web Ontology Language. https://www.w3.org/TR/owl2-overview/

14. W3C (2017). Shapes Constraint Language (SHACL). https://www.w3.org/TR/shacl/

### Statistical Reporting

15. APA (2020). Publication Manual of the American Psychological Association (7th ed.).

16. Transparent Statistics Guidelines. https://transparentstats.github.io/guidelines/

17. Lakens, D. (2013). Calculating and reporting effect sizes to facilitate cumulative science. Frontiers in Psychology, 4, 863.

### Tools & Software

18. Overleaf. https://www.overleaf.com/

19. Zotero. https://www.zotero.org/

20. Better BibTeX for Zotero. https://retorque.re/zotero-better-bibtex/

21. matplotlib: Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. Computing in Science & Engineering, 9(3), 90-95.

22. seaborn: Waskom, M. (2021). seaborn: statistical data visualization. Journal of Open Source Software, 6(60), 3021.

### Data Repositories

23. Zenodo. https://zenodo.org/

24. Figshare. https://figshare.com/

25. GitHub. https://github.com/

### Industry Reports

26. Gartner (2024). Magic Quadrant for Cloud Database Management Systems.

27. Forrester (2023). The Forrester Wave: Knowledge Graphs for Enterprise Data Management.

28. DB-Engines Ranking. https://db-engines.com/en/ranking/graph+dbms

### Accessibility

29. Okabe-Ito Color Palette. https://jfly.uni-koeln.de/color/

30. WCAG 2.1 Guidelines. https://www.w3.org/WAI/WCAG21/quickref/

31. ColorBrewer. https://colorbrewer2.org/

### Reproducibility & Open Science

32. Open Science Framework (OSF). https://osf.io/

33. arXiv Submission Guidelines. https://info.arxiv.org/help/submit/index.html

34. Stodden, V., Seiler, J., Ma, Z. (2018). An empirical analysis of journal policy effectiveness for computational reproducibility. PNAS, 115(11), 2584-2589.

### Benchmarking Methodology

35. Gray, J. (Ed.). (1993). The Benchmark Handbook for Database and Transaction Systems (2nd ed.). Morgan Kaufmann.

36. TPC (Transaction Processing Performance Council). http://www.tpc.org/

37. LDBC (Linked Data Benchmark Council). https://ldbcouncil.org/

---

## Appendix: Sample Research Questions

**For Graphwise Project**:

### Research Question 1 (Performance)
**RQ1**: How do semantic layer platforms compare in query execution performance across analytical, navigational, and reasoning workloads at enterprise scale (10M-1B entities)?

**Sub-questions**:
- RQ1.1: What is the median query latency for analytical queries (aggregations, joins) by platform?
- RQ1.2: How does performance scale as dataset size increases from 10M to 1B entities?
- RQ1.3: What is the impact of reasoning (RDFS, OWL) on query latency?

### Research Question 2 (Expressiveness)
**RQ2**: What trade-offs exist between semantic expressiveness and implementation complexity across RDF-based and property graph approaches?

**Sub-questions**:
- RQ2.1: What percentage of enterprise semantic requirements (reasoning, constraints, schema) can be expressed natively in each platform?
- RQ2.2: How does modeling effort (lines of schema code) differ between RDF ontologies and property graph schemas?
- RQ2.3: What workarounds are required for property graphs to achieve semantic capabilities available in RDF?

### Research Question 3 (Enterprise Integration)
**RQ3**: To what extent do platform-specific features and enterprise integration complexity impact total cost of ownership for semantic layer deployments?

**Sub-questions**:
- RQ3.1: How does setup time (deployment to first query) differ across cloud-managed and self-hosted platforms?
- RQ3.2: What is the data loading time for 10M entities by platform?
- RQ3.3: How does tool ecosystem maturity (IDE support, libraries, visualization) vary across platforms?

---

**Document Complete**

This comprehensive guide provides all necessary academic standards for creating a publication-quality benchmarking paper for Graphwise. Use this as your roadmap from experiment design through publication.

**Next Steps**:
1. Review with team (align on scope, timeline)
2. Finalize research questions (RQ1, RQ2, RQ3)
3. Begin Phase 1: Literature review and planning
4. Set up infrastructure (AWS, Docker, platforms)
5. Design benchmark queries and datasets

**Questions? Reach out to academic advisor or consult specific conference/journal guidelines for latest requirements.**

---

**Document Metadata**:
- **Version**: 1.0
- **Last Updated**: November 1, 2025
- **Authors**: UW MSIM Team (Rahil, Mathew, Shreyas, Siddarth)
- **License**: CC BY 4.0 (for internal use and sharing with Graphwise)
