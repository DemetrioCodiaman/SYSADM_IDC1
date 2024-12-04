

|  SCHOOL OF INFORMATION AND TECHNOLOGY |  |  |
| ----- | :---- | :---: |
| NAME: Codiaman, De Leon | DATE PERFORMED: 12/04/2024 | /50  |
| Section:IDC1 | DATE SUBMITTED: 12/04/2024 |  |

1. # **SYSADM1 – Capacity Management & Planning**

## **Part 1\. A Simulated Dataset for Capacity Planning Exercise**

**Scenario:** A mid-sized e-commerce website is expecting a significant surge in traffic due to an upcoming holiday sale.

### Projected Traffic Increase

* **Expected Peak Traffic:** 5x the normal peak traffic  
* **Peak Time:** 12:00 PM \- 3:00 PM on the sale day

  ### System Specifications

* **Server Count:** 5  
* **CPU Cores per Server:** 8  
* **RAM per Server:** 32GB  
* **Network Bandwidth per Server:** 1Gbps

  ### Additional Considerations

* **New Product Launch:** A highly anticipated product will be released during the sale.  
* **Marketing Campaign:** A major marketing campaign will be launched to promote the sale.  
* **Potential Cyber Threats:** Increased traffic can attract malicious actors.

Tasks:

1. Review the provided server performance data and identify potential bottlenecks  
2. Brainstorm possible solutions to address the identified bottlenecks. Propose potential solutions considering hardware and software-based solutions.   
3. Discuss the pros and cons of each proposed solution by filling out the table below. 

| Proposed Solution |  Pros Cons  | Cost | Complexity | Potential impact on system performance |
| :---- | :---- | :---- | :---- | :---- |

Grading Rubric:

| Criteria | Excellent | 10pts | Good | 7pts | Needs Improvement | 4pts |
| ----- | :---- | :---- | :---- |
| **Problem Identification**  | Accurately identifies the primary problem and provides a detailed explanation. | Identifies the main problem and provides a basic explanation. | Identifies a problem but lacks clarity or accuracy. |
| **Solution Proposal**  | Proposes multiple relevant solutions and provides detailed explanations, including potential drawbacks and benefits. | Proposes one or two relevant solutions but lacks detailed explanation. | Proposes a solution but lacks feasibility or relevance. |
| **Evaluation of Solutions**  | Provides a thorough evaluation of the proposed solutions, considering factors like cost, complexity, and potential impact. | Provides a basic evaluation of the proposed solutions, but lacks depth. | Does not evaluate the proposed solutions or provides a superficial evaluation. |
| Score: |  |  |      /30 |

**Part 2\. Network Scalability Analysis**

Recall the e-commerce website scenario we discussed earlier. Given the expected surge in traffic, analyze the provided network topology diagram. Identify potential bottlenecks and areas where scalability might be a concern. Propose specific strategies to improve the network's scalability and performance to ensure a seamless user experience during the peak traffic period. Consider factors such as increased user demand, new applications, and security threats.

- The core switch acts as a single point of failure and may become overwhelmed under high traffic loads, while the edge router might lack the bandwidth or processing power to manage increased demand effectively. Inter-VLAN communication could cause congestion and latency, especially during peak periods, and the servers might become overloaded without sufficient scaling mechanisms. Additionally, the network is vulnerable to security threats like DDoS attacks, which could exploit the surge in traffic. To address these challenges, upgrading network hardware is essential, such as replacing the core switch with a higher-capacity Layer 3 switch and enhancing the edge router for better throughput and QoS capabilities. Load balancers can be deployed to distribute traffic evenly across servers, while introducing redundant core switches and configuring link aggregation will improve fault tolerance. Optimizing VLAN design by using Layer 3 switches for inter-VLAN routing and segmenting traffic with ACLs can enhance efficiency. Scalability can be further improved by integrating cloud-based solutions, SDN for dynamic traffic management, and increasing internet bandwidth to accommodate traffic spikes. Security measures such as firewalls, IDS/IPS systems, and DDoS protection should also be implemented alongside robust network monitoring tools to ensure real-time traffic analysis and proactive issue resolution. These strategies collectively enhance the network’s ability to scale, maintain performance, and ensure reliability during peak periods.


![Screenshot 2024-12-04 091653](https://github.com/user-attachments/assets/787f4eec-d3d7-4c3f-b561-8a2d82b4cd43) 

![][image1]

| Criteria | Excellent | 10pts | Good | 7pts | Needs Improvement | 4pts |
| ----- | :---- | :---- | :---- |
| **Network Analysis**  | Accurately identifies potential bottlenecks, security risks, and capacity limitations. | Identifies key network components and some potential bottlenecks. | Identifies some basic network components but lacks a comprehensive analysis. |
| **Scalability Planning**   | Proposes multiple relevant solutions and provides detailed explanations, including potential drawbacks and benefits. | Proposes some relevant scalability strategies but lacks detail. | Proposes limited scalability strategies. |
| **Evaluation of Solutions**  | Proposes comprehensive scalability strategies, including specific recommendations for hardware upgrades, software configurations, and network optimizations. | Provides a basic evaluation of the proposed solutions, but lacks depth. | Does not evaluate the proposed solutions or provides a superficial evaluation. |
| **Proposed Design**  | Provides a detailed and well-justified design, including network diagrams, configuration details, and implementation plans. | Provides a basic design but lacks specific details and justifications. | Does not provide a clear and detailed design. |
| **Evaluation and Justification**  | Provides a thorough evaluation of the proposed solutions, considering factors like cost, complexity, and potential impact. | Provides a basic evaluation of the proposed solutions, but lacks depth. | Does not evaluate the proposed solutions or provides a superficial evaluation |
| Score: |  |  |      /50 |

[image1]: 
