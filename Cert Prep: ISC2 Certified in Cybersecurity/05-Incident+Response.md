# Incident Response
## Build an incident response program
- Incident Response plan describes the polices and procedures governing cybersecurity incidents
- Prior planing leads to strong incident response
- Failure to conduct advance planning is a disaster
- What Should Incident Response Describe?
  - **Statement of Purpose:** Outlines reasons for creating an incident response plan and its scope.
  - **Scope:** Covers various incidents, including cybersecurity and loss of sensitive information.
  - **Strategies and Goals:** Prioritizes containment, outlines roles, and emphasizes communication.
  - **Organization's Approach:** Defines incident handling roles, responsibilities, and authority.
  - **Communication:** Details internal and external communication protocols.
  - **Approval:** Requires senior management endorsement for authority and credibility.
- Consult NIST SP 800-61 as you develop your plan or You could take reference like Carnegie Mellon Information Security Office Incident Response
    
## Create an incident response team
- Incident Response Teams must have personnel available for 24/7
- Building an IR team
  - **Management:** Provide oversight, authority, and executive support
  - **Information Security Personnel:** Responsible for security monitoring, analysis, and response
  - **Technical Subject Matter Experts:**
    - Database Administrators
    - Developers
    - System Engineers 
    - Virtualization Experts
  - **Legal Counsel:** Provide legal guidance and representation if needed
  - **Public Affairs and Marketing Staff:** Handle external communications and public relations
  - **Human Resources:** Assist with employee-related matters
  - **Physical Security Team:** Coordinate with physical security aspects
- As you build out your incident response team, you may find that your organization lacks some of the capacity to handle security incidents. For example, you might discover that you don't have the forensic capabilities within your team to conduct investigations and supportive incident response efforts. In those cases, you may wish to consider retaining an external incident response provider to assist. Now, one important tip. You don't want to try and locate and negotiate a contract with a provider in the middle of an incident. Plan ahead and get the paperwork in place to use a provider immediately when you discover a problem.

## Incident Communication Plan
- Communication plans ensure that all participants have timely accurate information
- Limit external communication to trusted parties
- If there is a threat to safety, it is recommended to notify law enforcement as they have greater authority in evidence gathering. However, a drawback is the potential risk of your data becoming public.
- But in above scenario also involve organisation's legal team
- Your Communication plan should not only consist to whom you should communicated but as well how you in secure mannner you will communicate

## Incident Identification
**Incident Data Sources**
- IDS/IPS
- Firewalls
- Authentication Systems
- Integrity monitors
- Vulnerability Scanners
- System event log
- Netflow records
- Antimalware packages

- **SIEM Technology in Incident Response:**
  - Security Incident and Event Management (SIEM) systems serve as centralized log repositories and analysis solutions.
  - SIEM systems assist in analyzing security-related logs, detecting possible incidents based on rules and algorithms, and providing a centralized information source for investigators.

- **Incident Identification:**
  - Security teams may detect incidents internally through monitoring systems or externally from reports by employees, customers, or external organizations.
  - The incident response team should establish a consistent method for receiving, recording, and evaluating external reports.
  - The first reports of an incident may come from external source like user cant login, client data on web

- **First Responder Responsibilities:**
  - First responders play a crucial role in incident response by acting quickly to contain damage.
  - Their primary task is to isolate potentially compromised systems from the network to prevent further damage and communication with attackers but keep it running to keep evidence
  - Remember, the highest priorty of first responder must be containing damage through isolation
# Quiz
- Which one of the following individuals would not normally be found on the incident response team?
_CEO_

- 
