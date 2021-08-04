## Guild Operator Tool Suite

The Guild Operators suite of stake pool operator tools is a collection of tools and scripts for easy setup, management, and monitoring of a Cardano stake pool. It's the result of a community collaboration effort to bridge and fill the gap between the core cardano-node/cli software and the operator to help with the everyday tasks of running a Cardano node.

### Tools
- **CNTools**  
CNTools is like a swiss army knife for pool operators to simplify typical operations. It is a bash GUI menu-driven tool to create and manage wallets, sending Ada and tokens, and about every pool operation needed. In addition to this, the tool has been extended with additional features and improvements since its first official release together with the Cardano Shelley MainNet launch in July 2020.  
[CNTools @ Guild Operators](https://cardano-community.github.io/guild-operators/Scripts/cntools/)
- **Guild LiveView**  
Guild LiveView, or gLiveView, is a local bash CLI monitoring tool that offers an intuitive UI to monitor the node status. It connects to the locally running node using the provided EKG/Prometheus node endpoints to gather and display node metrics in real-time. The tool automatically detects if the node is launched as a relay or block producer and adapts output accordingly.  
[Guild LiveView @ Guild Operators](https://cardano-community.github.io/guild-operators/Scripts/gliveview/)