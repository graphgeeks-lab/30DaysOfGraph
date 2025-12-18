# 30DaysOfGraph
A community learning challenge by GraphGeeks for people to learn about graphs

Welcome to **#30DaysOfGraph** — a hands-on, learn-in-public challenge designed to help you understand **graphs, knowledge graphs, and graph data modeling**, from first principles to real-world applications.

This challenge is organized by **GraphGeeks** and is open to:
- Graph beginners
- Data engineers & analysts
- Software engineers
- Knowledge graph practitioners
- Anyone curious about graph thinking

---

## Goal

By the end of 30 days, you will:
- Think in graphs, not tables
- Understand **knowledge graphs**
- Model data using **graph-native approaches**
- Work with **Label Property Graphs (LPG)** and **RDF**
- Apply **graph algorithms**
- Share your learning publicly

---

## How This Challenge Works

- 📆 **30 days, 1 topic per day**
- 🧩 Concept-first, tool-second
- 📂 Daily folders in this repo
- 🔁 One Pull Request (PR) per day
- 🌍 Share your learning on LinkedIn using **#30DaysOfGraph**

---

## How to Participate

1. **Fork this repository**
2. **Clone your fork**
   ```bash
   git clone https://github.com/<your-username>/30DaysOfGraph.git
   ```


## 📅 30 Day of Graph Challenge Plan 
### #30DayGraphChallenge 

Phase 1: Graph Thinking & Foundations (Days 1–7)

Goal: rewire how people think about data

| Day | Name | Description | Activity |
|----:|------|-------------|----------|
| Day 1 | What is Graph Engineering? | - What problems graphs solve <br>- Graph engineer vs data engineer vs data scientist <br> - Real-world examples (fraud, recommendations, knowledge graphs) | Write 3 problems you’ve seen that involve relationships |
| Day 2 | Graph Thinking | - Thinking in relationships instead of tables <br> - Nodes vs Joins <br>- Paths as first-class citizens | Take a real-world problem and describe it as nodes and relationships |
| Day 3 | Graph Theory (Just Enough) | What is a graph?<br>Nodes, edges, paths, cycles<br>Directed vs undirected graphs | Draw the same graph once as directed and once as undirected |
| Day 4 | Properties & Attributes | What are nodes properties?<br> What are relationship properties?<br>When data belongs on nodes vs edges? | Add properties to your Day 3 graph |
| Day 5 | Types of Graphs | You will learn the difference between: <br> - Directed vs undirected<br>- Weighted graphs<br> - Bipartite graphs <br> - Multigraphs | Identify which graph type best fits your use case |
| Day 6 | What is Linked Data |- URIs <br> - Global identifiers <br> - Linking across datasets | Find 3 real-world identifiers (ISBN, ORCID, Wikidata ID) |
| Day 7 | What is a Knowledge Graph? | - Definition <br> - How knowledge graphs differ from “just graphs”<br> - Semantics, meaning, context (Knowledge graphs in search & AI) | Explain a knowledge graph in one paragraph (non-technical) |

Phase 2: Graph Data Modeling (Shared Core) (Days 8–14)

Goal: learn modeling BEFORE technology

| Day | Name | Description | Activity |
|----:|------|-------------|----------|
| Day 8 | Graph Data Modeling Basics |- Entities vs relationships<br>- Cardinality<br>- Direction matters | Create a conceptual graph model (no tools) |
| Day 9 | Modeling Relationships | - Verb-based relationships<br>- Avoiding “has_*” anti-patterns<br> - Modeling Events vs facts | Refactor weak relationships into strong ones |
| Day 10 | Modeling Nodes | What deserves its own node?<br>When to split vs merge entities<br> Super nodes & anti-patterns | Identify potential super nodes in your model |
| Day 11 | Normalization in Graphs | What applies from relational theory<br><br>What does not apply<br><br>Why over-normalization hurts graphs | Normalize a flat dataset into a graph |
| Day 12 | LPG vs RDF (Conceptual) | Label Property Graphs<br><br>RDF & triples<br><br>Same graph, different representations | Map your model to LPG and RDF on paper |
| Day 13 | Choosing LPG or RDF | Trade-offs<br><br>Performance vs semantics<br><br>Schema vs ontology | Decide which model fits your use case and why |
| Day 14 | Shared Dataset | Understanding the domain<br><br>Asking graph-native questions | Write 5 questions you want to answer with the graph |
| Day 15 | LPG Modeling | Labels<br><br>Relationship types<br><br>Properties | Model the dataset as a Label Property Graph |
| Day 16 | Cypher Basics | MATCH, CREATE, MERGE<br><br>Pattern matching<br><br>Traversals | Write 5 Cypher queries |
| Day 17 | RDF Modeling | Triples (S–P–O)<br><br>URIs<br><br>Vocabularies | Model the dataset as RDF triples |
| Day 18 | SPARQL Basics | SELECT & WHERE<br><br>Filters<br><br>Basic graph patterns | Write 5 SPARQL queries |
| Day 19 | LPG vs RDF Queries | Expressiveness<br><br>Verbosity<br><br>Readability | Answer the same question in Cypher and SPARQL |
| Day 20 | Semantics & Reasoning | Ontologies<br><br>Inference<br><br>What RDF adds | Add simple inference to your model |
| Day 21 | Graph Algorithms | Why algorithms matter<br><br>Local vs global algorithms | Identify where algorithms add value |
| Day 22 | Centrality | Degree<br><br>Betweenness<br><br>PageRank | Find the most important nodes |
| Day 23 | Communities | Clustering<br><br>Similarity<br><br>Grouping | Detect communities in your graph |
| Day 24 | Path Finding | Shortest paths<br><br>Variable-length traversals | Find meaningful paths |
| Day 25 | Graph Workloads | OLTP vs OLAP<br><br>Transactional vs analytical graphs | Classify your use case |
| Day 26 | Graph + AI | Embeddings<br><br>Recommendations<br><br>ML + graphs | Identify an AI use case for your graph |
| Day 27 | Data Quality | Duplicates<br><br>Rogue nodes<br><br>Inconsistent relationships | Find and fix bad data |
| Day 28 | Scaling Graphs | Indexing<br><br>Traversal depth<br><br>Performance modeling | Optimize one slow query |
| Day 29 | Real-World Use Cases | Fraud<br><br>Recommendations<br><br>Knowledge graphs | Map your graph to a real use case |
| Day 30 | Becoming a Graph Engineer | Skills roadmap<br><br>Tooling ecosystem<br><br>Community | Share your final model and lessons learned |
