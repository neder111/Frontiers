# Deep learning approaches for Protecting IoT Devices in Smart Homes from MiTM Attacks
## Absctract
This paper presents an enhanced framework utilizing deep learning method as an Intrusion Detection and Prevention System (IDPS) to identify Man-in-the-Middle (MitM) attacks. The primary objective is to safeguard IoT devices against eavesdropping., ensuring the maintenance of data integrity, confidentiality, and privacy. The framework aims to verify the authenticity of communication parties, uphold overall system and network security within Software-Defined Networking (SDN) environments, and establish trust among users and stakeholders. The experimental analysis focuses on machine learning algorithms, specifically those associated with Intrusion Detection Systems (IDS) such as Naive Bayes (NB), k-Nearest Neighbors (kNN),  Random Forest (RF), and Convolutional Neural Network (CNN). The CNN algorithm exhibits superior performance on the training dataset, achieving an accuracy of 99.96\%, minimizing training time,  It also demonstrates favorable outcomes in terms of detection time, requiring only 1 second, and maintains a low false alarm rate (FAR) of 0.02\%. Subsequently, the proposed method was deployed on a testbed SDN framework to assess its detection performance across various network topologies. The results highlight its efficiency compared to other related works.

 ## Keywords: 
Man-in-the-Middle; ARP flooding; ARP spoofing; Software defined networking; Machine Learning; Internet of Things; Smart Home; Cybersecurity; Intrusion Detection System

## Dataset :
Our synthetic dataset comprises 16 features:
| **Feature Name**   | **Description**                                                                 |
|--------------------|---------------------------------------------------------------------------------|
| Timestamp          | Captures timing for packet traffic within an SDN network.                       |
| Datapath_ID        | Uniquely identifies a switch network device.                                    |
| In_port            | The port on a switch where a packet was received.                               |
| Out_port           | The port on a switch where a packet should be forwarded.                        |
| Src_mac            | The MAC address of the source device that originated the packet.                |
| Dst_mac            | The MAC address of the destination device to which the packet is being sent.    |
| Src_ip             | The IP (Internet Protocol) address of the source device.                        |
| Dst_ip             | The IP address of the destination device.                                       |
| Time_to_live       | Prevents packets from circulating indefinitely in the network.                  |
| Protocol           | Indicates the protocol used by the packet, such as TCP, UDP, or ICMP.           |
| Tp_src             | The source port number, typically used in TCP or UDP packets.                   |
| Tp_dst             | The destination port number, also typically used in TCP or UDP packets.         |
| Icmpv4_code        | Denotes the code associated with ICMP messages for error reporting or diagnostic purposes. |
| Icmpv4_type        | Specifies the type of ICMP message being sent, such as echo request or echo reply. |
| Packet_size_bytes  | Indicates the size of the packet in bytes.                                      |
| Label              | Tag for normal, ARP flood, and ARP spoof records, where 0 indicates normal, 1 indicates ARP flood attacks, and 2 indicates ARP spoof. |

 The dataset includes three label classes: 'normal' (0), 'ARP flood' (1), and 'ARP spoof' (2).
link to Download the dataset:https://drive.google.com/file/d/1rGNPRU77FEasfrq_7BLPhDBgT2d6DZ1Y/view?usp=sharing


