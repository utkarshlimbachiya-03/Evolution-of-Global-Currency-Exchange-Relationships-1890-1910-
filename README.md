# Evolution-of-Global-Currency-Exchange-Relationships-1890-1910-
**Overview:**

This project applies under academic research on the network analysis and analyze the evolution of the global foreign exchange network.

**Dataset:**

Flandreau & Jobst (2005)- Network Analysis of the International Currencies 1890-1910.
Link: https://eh.net/database/international-currencies-1890-1910/
Nodes: There are 45 Nodes that are representing countries involved in currency exchange.
Edges: 1980 Edges-indicates the the presence of foreign exchange trading between two countires.
Graph Properties: Directed, unweighted, with metadata and temporal attributes.

**Attributes:**

Economic Indicators: Real GDP (Gross Domestic Product), GDP per cpita, debt burden, interest rates (short and long term).
Political Factors: Democracy index and colonial relationships.
Glod Standard: Binary indicator of whether a country adhered to the gold standard.

**Objective:**

Model foreign exchange networks as directed graphs. Analyze basic staistics and Network construction. Identify the communities performing currency exchange. Compare the sub-network by gold standard adherence and political system.

**Tasks and Methods**

*Task 1: Network construction and basic statistics*
Perform directed networks with the help NetworkX for 1890,1900,1910.
Computed degree distribution (in-degree and out-degree), clustering coeffiecent and centrality measures (Degree, Betweenness, Eigenvector).

*Task 2: Small-world and structural analysis*
To measure the samll-world properties calculated theavergae shortest path and clustering coeefficent and compared with random networks with sames nodes and edges.
Detected community using Infomap and Leicht-Newman to get the modularity of the particular year.

*Task 3: Economic and political influence*
Created sub-networks like Golad standard vs Non-Golad standard, Democratic vs Non-Democratic.
Analyzed correlation of GDP, interest rate, debt with centrality measures. Used scatter plots for visualization.

*Tas 4: Network Resilience and crisis Propagation*
Simulated Tragete vs Random node removals, crisis spread using Susceptible-Infected (SI) model.




