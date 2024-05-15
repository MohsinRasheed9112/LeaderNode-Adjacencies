

### Blockchain Network Node Connection Frequency Analysis

### Introduction

This project aims to analyze the frequency of occurrence of nodes as connections to leader nodes in a blockchain network. By aggregating this data, we can identify how many times a specific node gets connected to a leader node or how many leader nodes are connected to the same node. This information provides valuable insights into the network's structure and potential centralization risks.


### Results

The project successfully identifies the count of leader nodes and the frequency of connections between each leader node and other nodes in the network. Additionally, it calculates the frequency of nodes being connected to a specific number of leader nodes.

The output includes:
1. The total number of leader nodes in the network
2. For each leader node:
   - The ID of the leader node
   - The list of nodes connected to that leader node
   - The count of nodes connected to that leader node
3. The frequency of nodes being connected to a specific number of leader nodes (e.g., Node A is connected to 3 leader nodes, Node B is connected to 5 leader nodes, etc.)

