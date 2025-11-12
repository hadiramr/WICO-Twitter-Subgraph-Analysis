# WICO-Twitter-Subgraph-Analysis
This project analyzes two real Twitter subgraphs from the WICO Graph Dataset:

Malicious Cluster: 5G_Conspiracy_Graphs (misinformation community)
Benign Cluster: Non_Conspiracy_Graphs (normal / non-misinformation community)
The goal is to compare structural, behavioral, and visual properties of both networks to understand how misinformation spreads differently from normal discussions.

**Tools & Environment**

Tool:Gephi

Data Format:.gexf 

Metrics Computed:Degree Centrality

Betweenness Centrality

Average Clustering Coefficient

Modularity (Q)

Community Detection 

**Analysis Tasks**

1- Individual Graph Analysis

2- Comparative Analysis

**Visualization Plan**

Both networks visualized in Gephi using:

ForceAtlas2 Layout
Node Size: Degree Centrality
Node Color: Community (Louvain modularity class)
Edge Thickness: Interaction strength (edge weight)
Labels: Top 10 most influential nodes

**After running Gephi analyses**

the report discuss:
How structure affects trust and misinformation spread.
Differences in community behavior between misinformation vs. normal users.
Role of bridge users in connecting or fragmenting discussions.
Real-world implications for misinformation detection and mitigation.
