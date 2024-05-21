# Business Continuity
##  Business Continuity planning
- **Business Continuity Planning**: The set of controls designed to keep business running in the face of adversity, whether natural or manmade
- The focus of Business Continuity Planning is to keep operations running in the face of adversity which is why sometimes its called `Continuity of Operation Planning` E.g small scale incidents like Single system failure, or major catastrophic situation
- Business Continuity planning is a core security concept because it's the primary control that supports availability of the system 
- **Defining the BCP scope**
  - What business activities will the plan cover?
  - What systems will it cover?
  - What controls will it consider?
- Continuity planners use a tool known as Business Impact Assessment(BIA) which identifies and prioritizes risks
- The BIA is a risk assessment that uses a quantitative or qualitative process. It begins by identifying the organization's mission essential functions and then traces those backwards to identify the critical IT systems that support those processes. Once planners have identified the affected IT systems, they then identify the potential risks to those systems and conduct their risk assessment
![image](https://github.com/D-Sensei/Prac/assets/74155862/2b75a08f-47eb-4c76-b7f8-74f7492e5425)
For example, if a $50,000 flood prevention system would reduce the risk of hurricane damage to the data center by 50%, purchasing that system is probably a good decision because it has an expected payback period of less than one year.

## Business Continuity controls
- IT professionals protect the availability of systems by ensuring that they're redundant.
- That simply means that they're designed in a way that a failure of a single component doesn't bring the entire system down.
![image](https://github.com/D-Sensei/Prac/assets/74155862/6dae7a89-cb28-44fe-8013-da07c3e2293c)
- Let's look at an example. Here we have a simple web based application, a web server protected by a firewall and connected to the internet. As we conduct a single point of failure analysis we might first notice that the web server itself is a single point of failure. If anything goes wrong with that server the web service will stop functioning. 
![image](https://github.com/D-Sensei/Prac/assets/74155862/6ec1a531-481f-440e-8bd8-918fb1ec41d8)
- We can correct the situation by replacing the single web server with a clustered farm of servers that are all designed to provide the same web service. The cluster is designed so that if a single server fails, the other servers will continue providing service without disruption. Once we've implemented the cluster, we've removed the server as a single point of failure

- Next, we might turn our attention to the firewall, another single point of failure. If the firewall goes down internet users will not be able to reach the web server, rendering the web service unavailable. Therefore the firewall is also a single point of failure. We can correct that situation by replacing the firewall with a pair of high availability firewalls, where one serves as a backup device, standing by to step in immediately if the primary firewall fails. By replacing the single firewall with a high availability pair, we've removed the firewall as a single point of failure.
![image](https://github.com/D-Sensei/Prac/assets/74155862/c7c58816-afb1-43e3-bacc-5ea4dd008e54)

- But we have still yet another single point of failure here, the internal and external network connections. As with the web server and firewall, we can address this single point of failure by introducing redundancy and having two separate network connections for each link.
![image](https://github.com/D-Sensei/Prac/assets/74155862/7ace0185-bbbc-4416-a21e-b6f4e0053693)

- Single Point Failure Analysis (SPOF) continues until the cost of addressing risks outweighs the benefits
- IT Contigency Scenario Example
    - Sudden bankruptcy of a key vendor
    - Insufficient storage or compute capacity
    - Failure of utility service  
## High Availability and fault tolerance
- There are two key technical concepts that improve the availability of systems
  - High Availability : Use multiple systems to protect against service failure
  - Fault Tolerance: Makes single system resilient against technical failure
- Load Balancing : Spread demand across the system
- **Common Point of Failure**
  - Power Supply
      - Contain moving part
      - have high failure rates
      - thats why server manufacturer often build dual power supplies into their server
      - when customer installs, they connect both of power supplies to power source. This way if one power supply fails the other will keep operataion uninterrupted
      - Uninterruptible Power Supplies (UPS) supply battery power to devices during brief disruption, they are served by generator to maintain long term backup power
  - Storage Media
      - Redundant Array of Inexpensive Disks (RAID) : designed to provide redundancy by having more disks than needed to meet business need
      - Two RAID techologies
        - Mirroring 
          - The most basic form of RAID, known as RAID level one is disk mirroring. In this approach, the server contains two disks. Each disk has identical contents and when the system writes any data to one disk, it automatically makes the same change to the other disk, keeping it as a synchronized copy, or mirror of the primary disk. If the primary disk fails, the system can automatically switch over to the backup disk and continue operating
        - Striping
            - The second major RAID technology is disk striping with parity, also known as RAID level five. In this approach, the system contains three or more disks and writes data across all of those disks, but it also includes additional data elements known as parity blocks that are spread across the disks. If one of the disks fails, the system can regenerate that disk's contents using the parity information. One important thing to remember, RAID is a fault tolerance strategy that's designed to protect against a single disk failure. It is not a backup strategy. You should still perform regular data backups to protect your organization's information in the event of a more catastrophic failure, such as the physical destruction of the entire server.
  - Networking
      -  Networking can also be a single point of failure. For this reason, organizations should consider implementing redundancy at different points in the network. This ranges from having multiple internet service providers entering a facility, to using dual network interface cards and critical servers, similar to the way that we use multiple power supplies. Using two or more network interface cards is known as NIC teaming. Within a network add redundancy to critical network pads as well. For example, the connection between servers and their storage is crucial to the operation of the data center. Multipath approaches create redundancy in those network connections and ensure continuous access to storage. 


## quiz
- What goal of security is enhanced by a strong business continuity program?
_availability_

- What is the minimum number of disk required to perform RAID level 5?
_3_

- What type of control are we using if we supplement a single firewall with a second standby firewall ready to assume responsibility if the primary firewall fails?
_high availability_
