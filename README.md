# Reducing Leader Recovery Time in Distributed Architectures Using Zookeeper Atomic Broadcast
* Author: Naveen Srikanth Pasupuleti
* Published In : International Journal for Multidisciplinary Research (IJFMR)
* Publication Date: August 2023
* E-ISSN: 2582-2160
* Impact Factor: 9.24
* Link: [Read the paper](https://www.ijfmr.com/research-paper.php?id=46802)
***
**Abstract**:\
Virtual Replication (VR) systems provide fault tolerance by maintaining data copies across multiple nodes and electing a new leader upon failure. However, leader failure recovery time increases significantly with cluster size due to communication overhead and synchronization delays. The complex leader election process and state validation among replicas contribute to extended downtime, especially under heavy load. This paper proposes using Zookeeper Atomic Broadcast (ZAB) to optimize leader failure recovery, reducing coordination delays and improving system availability. The approach aims to enhance recovery efficiency in large-scale distributed VR systems.

**Recovery Time**:\
Recovery time is the duration it takes to return to a normal or baseline state after a disturbance, event, or process.
 
**Key Contributions:** 
* **Algorithm Development** \
  Designed and optimized leader failure recovery time using zookeeper atomic broadcast.
* **Performance Comparison** \
  Conducted bench marking between VR Leader Failure Recovery Time and ZAB Leader Failure Recovery Time.
* **Research Leadership** \
  Led the research and technical implementation , focusing on advancing distributed database through algorithm innovation.

**Relevance & Real-World Impact**
* **Distributed system resilience:**\
Improves performance and fault tolerance in replicated environments by minimizing leader recovery delays during failure scenarios.

* **Leader recovery optimization:**\
By implementing Zookeeper Atomic Broadcast (ZAB), the proposed approach streamlines coordination and state synchronization, resulting in faster leader re-election and reduced downtime under heavy system load.

* **Academic recognition:**\
Widely referenced in academic discussions and technical explorations addressing recovery mechanisms and coordination techniques in fault-tolerant distributed systems.

* **Educational relevance:**\
Serves as a key reference in advanced distributed systems coursework, promoting critical understanding of consensus mechanisms, failure handling, and availability in high-scale computing environments.

***
**Experimental Results (Summary)**


| Cluster Size (Nodes) | VR Leader Failure Recovery Time (ms) | ZAB Leader Failure Recovery Time (ms) | Improvement (%) |
| ---------------------| ------------------------------------ | ------------------------------------- | ----------------|
| 3                    | 550                                  | 280                                   | 49.1            |
| 5                    | 950                                  | 450                                   | 52.6            |
| 7                    | 1100                                 | 670                                   | 39.1            |
| 9                    | 1300                                 | 850                                   | 34.6            |
| 11                   | 1700                                 | 1100                                  | 35.3            |

**Citation**
* **Reducing Leader Recovery Time in Distributed Architectures Using Zookeeper Atomic Broadcast**
*   Naveen Srikanth Pasupuleti
*   International Journal for Multidisciplinary Research
*   E-ISSN-2582-2160

**License**
* This research is shared for academic and research purposes. For commercial use, please contact the author.

**Resources**
* [IJFMR Website](https://www.ijfmr.com/)

**Author Contact** 
  * LinkedIn: https://www.linkedin.com/in/naveensrikanth/ | Email: connect.naveensrikanth@gmail.com

