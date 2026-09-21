# Graph Algorithms in Neo4j (Cypher): Adapted and Updated Examples

Cypher implementations of core graph algorithms, following chapters 1-6 of
*Graph Algorithms: Practical Examples in Apache Spark and Neo4j*
(Mark Needham and Amy E. Hodler, O'Reilly, 2019).

Much of the original code no longer runs on current Neo4j releases, so I
modified and patched it to work on **Neo4j 4.2.2**. The notebooks were
built as step-by-step teaching material for a graph-mining workshop.

## What is covered

Files are numbered in the order they should be run.

| Topic | Algorithms / steps | Files |
|---|---|---|
| Data import | Transport network, social network, and small-world (SW) datasets: nodes and relationships | `1.0.0`, `1.0.1`, `1.0.9`, `1.1.0`, `1.2.0`, `1.2.1` |
| Pathfinding and search | Shortest path, BFS, minimum spanning tree | `1.0.2` - `1.0.6` |
| Centrality | Degree (in/out), closeness, betweenness, PageRank | `1.0.7`, `1.0.8`, `1.1.1`, `1.1.3`, `1.1.9` |
| Graph projections | Named graphs, undirected graphs, joining disconnected components | `1.1.2`, `1.1.4` - `1.1.8`, `1.2.2` |
| Community detection | Triangle count, local clustering coefficient, strongly/weakly connected components, label propagation, Louvain | `1.2.3` - `1.2.8` |

## Requirements

- Neo4j 4.2.2
- Neo4j Graph Data Science / Graph Algorithms library: [version]
- Datasets: from the book's companion material: [link]

## How to run

1. Start a Neo4j 4.2.2 instance and install the graph algorithms plugin.
2. Place the CSV files from the book's companion repository in Neo4j's
   `import` folder.
3. Run the files in numeric order, starting with the data-import files.

## What I changed

Many parts of the original code were deprecated, so I modified and
patched them to work on Neo4j 4.2.2.

[Optional: list 2-3 concrete changes you actually made, e.g. which
procedure calls or syntax you replaced.]

## Credits

The examples and datasets originate from the book above. This repository
is my adapted and patched version, created for learning and teaching.
Please refer to the book for the original text and full explanations.

