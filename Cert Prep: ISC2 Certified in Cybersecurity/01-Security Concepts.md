# **Security Concepts**
## Confidentiality
1. Protect info from unauthorized
2. Concerns
    1. `Snooping` : Wanders around you workplace to gather information which is left out open
    2. `Dumpster Diving` : Look for sensitive information in trash that's why use paper shredder
    3. `EavesDropping` : Discuss sensitive info in closed space
    4. `Wiretapping` : Attacker get access to network and listen to it. Use encryption to secure wire.
    5. `Social Engineering` : Physicological Attack. Education can help avoid it.
## Integrity
1. Protect info from unauthorized `changes`
2. Concerns
    1. `Unauthorized modification` : Make changes without permission. Emp increasing his own salary in the system (give least privilege)
    2. `Impersonation`: Pretend to be someone else to change data, ask for access or request
    3. `Man in the middle`: Attacks take place in the middle of a communication session
    4. `Replay`: Attacks eavesdrop on logins and reuse the captured credentials.
3. The best defense for mitm and replay attack is use encryption to protect communication
4. For Example, Web traffic use TLS(Transport Layer Security) protocol to prevent an eavesdropper

## Availability
1. Protect authorized access to systems and data
2. Concerns
    1. `Denial of Service` : Attacker bombards a system with an overwhelming amount of traffic such that server unable to answer any request from legitimate users
    2. `Power Outages` 
        - Increased Demand can overwhelm the power grid
        - Natural Disaster
        - Generator or UPS protect the against power outage
    3. `Hardware Failures`
        - Have back up such that if one component fail there is another ready to pick up the slack
    4. `Destruction`
        - Could be physical damage or corruptions
        - Back up data centers in remote location or in the cloud that can keep running when our primary data is distrupted to protect against destruction
    5. `Service Outages`
        - Programming Errors. the failure of underlying equipment, or many other reasons
        - Resilient systems protect against  service outages
## Authentication and Authorization
- `Identification` involves making a claim of identity
- `Authentication` proving identity claim
- `Authorization` ensure that an action is allowed
- `Accounting` maintainss logs of user activity

## Password Security
- `Password`
      - Eight letters or more in some orgainsation
      - Pwd complexity
      - pwd expiration (organisaton forcing user to cahnge passwords every six months)
      - pwd history
      - pwd manager
  
## Multifactor Authentication
Three Different Authentication Factor
- > A
-
-

- PIN or Password
- Biometric
- Hardware or Software authentication token 
    - `Software` that responds with one time password
    - `Hardware` that act as key. Example: USB
    - 
## Non-repudiation
## Privacy
## Chapter Quiz
