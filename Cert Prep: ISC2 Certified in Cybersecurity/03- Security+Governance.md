# Security Governance
## Regulations and laws
- We must identify the laws and regulation which are applied to us
- Now, while that might sound straightforward at first glance, thequestion of which jurisdictions have authority to regulate data is actually quite complicated.
- Imagine that we have a company with all of their operations located in the state of California. It's clear in this case that California state law applies to them, as does federal law written at the national level in the United States. But what if they have a customer located in New York? Does New York law now apply as well? And if you're using a cloud provider located in Texas, does Texas law govern that data? If that cloud provider outsources to a data center provider in Florida, then what? And the issue becomes even more complicated when we expand internationally. The European Union says that their General Data Protection Regulation, `GDPR, applies to the personal information of all EU residents wherever they may be located.`
- PCI DSS for credit card compilance

## Security policy framework
- The Security policy framework includes four types of document
  - `Policies` describe an organisation security expectations
    - `_Weak Policy Statements_`
      > _1. All Sensitive information must be encrypted with AES-256 encryption_ <br>
      > _2. Store all emp records in Room 225_
    - `_Strong Policy Statements_`
      > _1. Sensitive information must be encrypted using approved technology_ <br>
      > _2. Store all emp records in room approved by HR_
    - Compilance is must
  - `Standards` describe specific security control
    - Includes things like company approved encryption algorithm, record storage location, configuration parameters and other technical & operational details
    - compilance is must
  - `Guidelines` is where security practicer's advise the organisation
    - E.g Use of encryption, While Out of office emp provide safe VPN connection
    - Following guidelines or compilance with guidelines is not necessary
  - `Procedure` are step-by-step instructions
    - Like incase of incident response: text the team, activating a video conference and informing resp manager
    - Depending on the organisation Compilance may be mandotory or optional
## Best Practice security policies
- Every organization is going to need a different set of security policies, but there are some common themes found in most organizations. 
- **Acceptable Use Policy (AUP)** describe authorized use of technology
    - For example, AUPs often address whether personal use of computers and systems is permitted, and how much
personal use is considered acceptable. 
    - The AUP also normally contains language that tells users that they may not attempt to access information or systems that they aren't authorized to access and the consequences that will occur if they violate the policy.
 - **Data handling policies** describe how to protect sensitive information
    - They define the types of information that the organization considers sensitive, and describe how employees must safeguard digital and paper records that contain that sensitive information. 
- **Password policies** cover the protection and use of passwords in the organization
    - Organizations may put in place, such as password expiration, complexity, and length requirements.
    - The password policy is where all of those requirements get documented
- **Bring Your Own Device (BYOD policy)** cover use of personal devices with company information
    - Employees to use their own smartphones, tablets, and computers to access company information.
    - Security control must be in place and the type of information must be processed
- **Privacy Policies** cover the use of personal identifiable information
    - Privacy policies are an important way to communicate with employees, customers, and other individuals about what information the organization retains about them and the ways that the organization will store, process, transmit, and maintain that data.
    - Privacy policies are often posted on an organization's website, and may be enforced by national, state, and local authorities.

- **Change Management Policies** cover the documentation approval, and rollback of technology changes
    - The change management policy should include the procedures that the team should follow for the documentation, approval, and implementation of any technology changes that will occur.
    - The change management process should also include the development of rollback plans that can restore the previous configuration if something goes wrong during or after the change.
    - Strong change management procedures are one of the most important characteristics of a mature IT environment.
## Quiz
Which element of the security policy framework includes suggestions that are not mandatory?
`guidelines`

What law applies to the use of personal information belonging to European Union residents?
`GDPR`

What type of security policy normally describes how users may access business information with their own devices?
`BYOD policy`
