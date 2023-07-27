
Previous Work:

The previous work in the field of identifying influential nodes in complex networks has been diverse and has tackled several problems. Researchers have explored various methods and algorithms to understand the importance of nodes in different types of networks. Some of the key areas of research and approaches include:

Centralities Measures: Researchers have extensively studied centrality measures such as Degree Centrality, Betweenness Centrality, Closeness Centrality, and Eigenvector Centrality. These measures have been applied to various types of networks to identify nodes that play crucial roles in information flow, influence, or disease spread.

Critical Node Detection Problem (CNDP): This optimization problem focuses on finding the set of nodes whose removal would have the most significant impact on a network's connectivity. Different variants and algorithms have been proposed to solve this problem in diverse application domains.

Dynamic Social Networks: The identification of influential nodes in dynamic social networks has gained attention due to the ever-changing nature of real-world social networks like Facebook and Twitter. Algorithms that can adapt to network evolution and time-varying interactions have been explored.

Multi-Criteria Decision Making: Techniques like TOPSIS have been widely used in business and decision-making contexts. Applying such methods to identify influential nodes in complex networks offers a way to handle multiple criteria and trade-offs in node selection.

Project Description:

The goal of this project is to address the challenge of efficiently and accurately identifying influential nodes in complex networks. With the continuous growth of network scale and complexity, this becomes crucial for predicting and controlling network systems effectively.

The project focuses on implementing three key algorithms: TOPSIS, w-TOPSIS, and AHP. TOPSIS is a multi-criteria decision-making method used to compare alternatives based on predefined criteria. The project aims to leverage TOPSIS in the context of complex networks to identify influential nodes effectively.

The network data used for the implementation is the "Ego-Facebook" dataset, which represents user-to-user friendships on Facebook. This directed network contains 2900 nodes, where each node represents a user, and the edges represent friendship connections.

The project is implemented using Python, utilizing libraries such as Numpy, Pandas, MatplotLib, NetworkX, and Math to handle data processing, visualization, and network analysis tasks.

By combining the insights from previous research on centrality measures and optimization algorithms with the TOPSIS method, the project aims to offer a comprehensive approach to identify influential nodes in complex networks. The evaluation will likely demonstrate the effectiveness of the proposed algorithm in comparison to traditional centrality measures, showcasing its advantages in challenging scenarios such as highly dynamic networks or networks with diverse criteria for node importance.
