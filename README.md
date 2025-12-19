# 30DaysOfGraph
A community learning challenge by GraphGeeks for people to learn about graphs

Welcome to **#30DayOfGraphChallenge**: a hands-on, learn-in-public challenge designed to help you understand graphs, knowledge graphs, and graph data modeling, from first principles to real-world applications.

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
3. Create a new branch for each day 
   ```bash
   git checkout -b day-01
   ```
4. Add your work for the day (notes, diagrams, queries, explanations)
5. Commit and open a Pull Requests
6. Share what you learned on linkedin using the following to get reposted:
   ```
      #30DayGraphChallenge #30DaysOfGraph #GraphGeeks @GraphGeeksOrg
   ```


# 📅 30 Day of Graph Challenge Plan 
### #30DayGraphChallenge 

## Phase 1: Graph Thinking & Foundations (Days 1–7)

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

## Phase 2: Graph Data Modeling (Shared Core) (Days 8–14)

Goal: learn modeling BEFORE technology

| Day | Name | Description | Activity |
|----:|------|-------------|----------|
| Day 8 | Graph Data Modeling Basics |- Entities vs relationships<br>- Cardinality<br>- Direction matters | Create a conceptual graph model (no tools) |
| Day 9 | Modeling Relationships | - Verb-based relationships<br>- Avoiding “has_*” anti-patterns<br> - Modeling Events vs facts | Refactor weak relationships into strong ones |
| Day 10 | Modeling Nodes | - What deserves its own node?<br>- When to split vs merge entities<br> - Super nodes & anti-patterns | Identify potential super nodes in your model |
| Day 11 | Normalization in Graphs | What normalization means for graphs <br><br> What applies from relational theory and does not apply<br><br>Why over-normalization hurts graphs | Normalize a flat dataset into a graph |
| Day 12 | Introducing LPG vs RDF (Conceptual) | Label Property Graphs vs RDF (triples) <br><br>Similarities and differences<br><br>Same graph, different representations | Map your conceptual model to LPG and RDF on paper |
| Day 13 | Choosing LPG or RDF | When LPG fits better <br><br> When RDF fits better <br><br> Trade-offs (Performance, reasoning, semantics)<br><br>Schema vs ontology | Decide which model fits your use case and why |
| Day 14 | Shared Dataset | Introduce challenge dataset (movies, books, research, etc.) <br><br> Understanding/Explain the domain & question you wish to answer | Write 5 questions you want to answer with the graph |

## Phase 3: LPG & RDF Paths (Days 15–20)

Goal: hands-on modeling & querying

| Day | Name | Description | Activity |
|----:|------|-------------|----------|
| Day 15 | LPG Modeling | Labels<br><br>Relationship types<br><br>Properties <br><br> Schema-less vs schema-guided | Model the dataset as a Label Property Graph |
| Day 16 | Cypher Basics | MATCH, CREATE, MERGE<br><br>Pattern matching<br><br>Traversals | Write 5 Cypher queries |
| Day 17 | RDF Modeling | Triples (subject–predicate–object)<br><br>URIs<br><br>Vocabularies | Model the same dataset as RDF triples |
| Day 18 | SPARQL Basics | SELECT & WHERE<br><br>Filters<br><br>Basic graph patterns | Write 5 SPARQL queries |
| Day 19 | LPG vs RDF Queries | Expressiveness<br><br>Verbosity<br><br>Readability | Answer the same question in Cypher and SPARQL |
| Day 20 | Semantics & Reasoning | What RDF gives you that LPG doesn’t (by default) <br><br> Ontologies<br><br>Inference | Add simple inference to your model (e.g subclass) |

## Phase 4: Graph Algorithms & Applications (Days 21–26)

Goal: extract value from graphs (You may implement this using a graph database or engine or networkX)


| Day | Name | Description | Activity |
|----:|------|-------------|----------|
| Day 21 | Introduction to Graph Algorithms | Why algorithms matter<br><br>Local vs global algorithms | Identify where algorithms add value |
| Day 22 | Centrality | Degree<br><br>Betweenness<br><br>PageRank | Find the most important nodes in your dataset |
| Day 23 | Communities & Similarity | Community detection(Clustering) <br><br>Node Similarity<br><br>Grouping | Detect communities in your graph |
| Day 24 | Path Finding | Shortest paths<br><br>Variable-length traversals | Find meaningful paths |
| Day 25 | Graph Analytics vs Transactions | OLTP vs OLAP<br><br>Transactional vs analytical graphs <br><br> When to use graph analytics engines | Classify your use case |
| Day 26 | Graph + ML / AI | Graph Embeddings<br><br>Graphs in recommender systems <br><br>knowledge graphs in AI <br><br> GraphRAG | Identify an AI use case for your graph |

## Phase 5: Real World & Wrap-Up (Days 27–30)

Goal: production mindset & inspiration

| Day | Name | Description | Activity |
|----:|------|-------------|----------|
| Day 27 | Data Quality iin Graphs | Duplicates<br><br>Rogue nodes<br><br>Inconsistent relationships | Find and fix bad data |
| Day 28 | Scaling Graphs & Performance | Indexing<br><br>Traversal depth<br><br> Modeling for performance | Optimize one slow query |
| Day 29 | Real-World Use Cases | Fraud<br><br>Recommendations<br><br>Knowledge graphs in enterprise | Map your graph to a real use case |
| Day 30 | Becoming a Graph Engineer / Scientist | Skills roadmap<br><br>Tooling ecosystem<br><br>Community | Share your final model and lessons learned |


##  Optional: Graph Analysis & Visualization

For participants interested in graph analytics and exploration, you may optionally use tools such as:

- **NetworkX** (Python)
  - Learning graph algorithms
  - Centrality and community detection
  - Small to medium graphs

- **Graph Visualization Tools**
  - For understanding and communicating insights
  - Useful for model validation and storytelling

These tools are optional and not required to complete the challenge.


## 🏆 Prizes & Recognition

We believe learning in public deserves recognition.


### Learning & Consistency Prizes

* Awarded to participants who:

* Consistently submit PRs

* Share learnings publicly

* Apply concepts thoughtfully

### Prizes include:

🌟 Spotlight on the GraphGeeks Website

🎤 Opportunity to give a GraphGeeks Community Talk

🎁 GraphGeeks SWAG

📘 A graph-related book to continue your journey


## 🤝 Contribution Guidelines

One PR per day

No “perfect” answers required

Diagrams and explanations encouraged

Be respectful and constructive

Help others learn