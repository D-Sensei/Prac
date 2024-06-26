# Risk Management
## Understanding Risk
- Two types Risk
  - `Internal` arise within organisation e.g fraud
    - You can often address internal risk by adding internal controls
    - In accounting, adding two person control to the issuance of checks might reduce the risk of fraud
  - `External` arise from outside of organisation
    - E.g: Ransomware attack
- `Multiparty` risk affect more than one organisation
  - For Example, Software as a service provider is compromised, that a multiparty risk because that compromise a risk to all of the customers of the service provider
- Legacy System pose: older OS risk
- Intellectual property theft : risk to info based organisation
- Software license compilance issue risk fines and legal action
____
## Risk Assessment
- Risk Assesments identifies and triages risks based on liklihood of their occurance and their expected impact on the information
- Common Language
  - `Threats` are external forces that jeopardize security
    - Can be natural (huricane, flood) or manmade (hacking or terrorism)
    - `Threat vector` are methods used by attackers. This maybe hackertoolkit, social engineering or even physical intrusion
  - `Vulnerabilites` are weaknesses in your security controls
    - Compromise CIA of the system
    - These might include missing patches, promiscous firewall rules or other security misconfiguration
  - `Risk` are the combination of threat and Vulnerability. Risks occur when your environment contains both a vulnerability and a corresponding threat that might exploit that vulnerability. 
    - For example, if you haven't updated your antivirus signatures recently and hackers release a new virus upon the internet, you then face a risk. You're vulnerable because you're missing a security control. And there is a threat, the new virus. 
    - There is no risk of either the threat or vulnerability factor is missing
- We rank risks by `likelihood` and `impact`
    - `likelihood` is the probability that risk will occur
    - `Impact` is the amount of damage a risk will cause
- `**Qualitative Risk**` Assesment uses subjective ratings to evaluate risk of likelihood and impact
![image](Image/QualitativeRiskAssesment.png)

- `**Quantitative Risk**` Assesment uses numeric ratings to evaluate risk of likelihood and impact
  - Will know as position go higher



_____
## Risk Treatment
- `Risk Treatment` analyzes and implements possible responses to control risk
  - 4 basic Option too address a situation
      - **Risk Avoidance** : Change busimess practices to make a risk irrelevant. Eg Relocate data facility to a place where thrir is no risk
      - **Risk Transference** : Transferring a risk attempts to shift the impact of a risk from your organization to another organization.. E.g Insurance policy
        - Many organizations are now considering the purchase of cyber security insurance policies to protect against the financial damage caused by hackers and identity theft. It's important to remember, however, that you can't always transfer a risk completely. For example, you can purchase insurance to cover the financial damage caused by a security breach but no insurance policy can repair your business' reputation in the eyes of your customers.
      
      - **Risk Mitigation**: Reduces the likelihod or impact of a risk likelihood. For Example: If we wanted to mitigate the risk of our data center flooding, we might engage a flood control specialist to install systems that are designed to divert water away from our facility.
      - **Risk Acceptance**: The choice to continue operations int the face of the risk. 
        - In our flooding scenario, we might conclude that all of the other risk management options are just too costly and then decide to continue operations in our current facility as is and deal with the aftermath of a flood if it occurs.
- An organisation `risk profile` is the set of risks that it faces

### Inhert , Residual and Control Risk
1. The initial level of risk that exists in an organization before any controls are put in place is the organization's inherent risk. Then controls are applied to reduce that risk. But of course, not every risk can be completely eliminated. 
2. The risk that remains after the inherent risk is reduced by controls is known as the residual risk. And controls themselves may introduce some new risks. For example, if you install a firewall as a risk management control, that may reduce your risk substantially but it also adds a new risk that the firewall itself may fail. That new risk that results from adding controls is known as control risk.
![image](https://github.com/D-Sensei/Prac/assets/74155862/5b20e133-2394-4f9c-b3ea-b3987cb9133e)

-  `Risk tolerance` is the level of risk an organisation is willing to accept

______
## Selecting Security Controls
- Security Controls reduce the likelihood or impact of a risk and help identify issue.
- Control Purpose
  - `Preventive` stop a security issue
  - `Detective` identify security issue requiring investigation
  - `Recovery` remediate securiy issue that have occured
- Example
![image](https://github.com/D-Sensei/Prac/assets/74155862/82f144a6-f886-4810-ab7a-fc02ef7aa60d)

- Control Mechanism
  - `Technical or logical` use to technology to achieve control objective E.g Firewall, IDS, encryption, data loss prevention and  antivirus software
  - `Administrative` use processes to achieve control objective E.g Access Review, log monitoring, perforimg background checks and security awareness training
  - `Physical` impact the physical world. E.g lock to prevent, camera and guard to monitor
----
## Configuration Management
-  `Configuration Management` tracks specific device settings and the inventory of software installed on device
-  `Baselines` provide a configuration snapshot at a given point at time. Sys Admin's check runnning system to baseline to identify changes to the system
-  `Versioning` assigns numbers to each version
  - Versioning assigns each release of a piece of software an incrementing version number that may be used to identify any given copy. These numbers are frequently written as three part decimals 
    - with the first number representing the major version of the software, 
    - the second number representing a major update, 
    - and the third number representing minor updates. 
  - For Example, Apple's iOS uses this scheme along with many other software products. For example, iOS 14 is a major version of the iPhone and iPad operating system. When apple periodically releases major updates to iOS, they add a second number to the version string, such as iOS 14.1. Then if they make small updates to iOS 14.1 prior to the release of iOS 14.2, they add a third digit such as iOS 14.1.2
- Configuration Artifacts : help understand how is system is designed to configure in case of time senstive troubleshooting and investigation
![image](https://github.com/D-Sensei/Prac/assets/74155862/e8746294-d589-400b-9fb6-6171bac20f78)
- **Standardize Device Configuration**
  - naming convention
  - IP Scheme

## Chapter Quiz
Purchasing an insurance policy is an example of which risk management strategy?
`risk transference`

What two factors are used to evaluate a risk?
`likelihood and impact`

What term best describes making a snapshot of a system or application at a point in time for later comparison?
`baselining`

What type of security control is designed to stop a security issue from occurring in the first place?
`preventive`

What term describes risks that originate inside the organization?
`internal`
