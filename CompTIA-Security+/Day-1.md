# Security Controls

## Controls Categories
**1. Technical Controls**
- These are controls impimented using sometype of tecchnical systems (e.g. Operating system controls, Firewalls and Anti-Virus)

**2. Managerial Controls**
- These are administrative controls associated with security design and implementation (e.g. Security policies)

**3. Operational Controls**
- These are controls implemented by people instead of systems (e.g. Security guards and awareness programs)

**4. Physical Controls**
- These ar controls that limit physical access (e.g. Guard shack, Fences, Locks, e.t.c)

## Control Types
**1. Preventive**
- These control type limits/blocks access to a resurce (Firewall rules, Follow security policy)

**2. Deterrent**
- This type of control discourages an intrusion attempt, it does not directly prevent access.

**3. Detective**
- This type of control identifies and logs an intrusion attempt, it may not prevent access.

**4. Corrective**
- This type of control applies a control after an event has been detected. It reverses the impact of an event thus allowing normal operation with minimal downtime.

**5. Compensating**
- Control using other means and maybe temporary.

**6. Directive**
- This type of control directs a subject towards security compliance. It is a relatively weak security control.

| Categories       | Preventive         | Deterrent      | Detective            | Corrective            | Compensating		              |Directive                       |
| -----------      | -----------        | --------       | -----------          | -----------           | --------                        | --------                       |
| **Technical**    | Firewall           | Splash Screen  | System logs 	        | Backup recovery		  | Block instead of Patch          | File storage policies |
|  **Manegerial**  | On-boarding Policy | Demotion	     | Review login reports | Policies for reporting issues | Separation of duties   	    | Compliance policies |
| **Operational** | Gaurd Shack	       | Reception Desk | Property patrols	  | Contact authorities		  | Require multiple security staff | Security policy training |
| **Physical**    | Door Lock	       | Warning Signs  | Motion detectors	  | Fire extinguisher		  | Power generator		    | Sign: Authorized Personnel Only |

# The CIA Triad
- The CIA triad refers to confidentiality, integrity and availability, describing a model designed to guide policies for information security (infosec) within an organization.

**1. Confidentiality** - Prevent disclosure of information to unathorized individuals or systems.
- Confidentiality can be achieved by encryption, access controls, Two-factor authentication.
**2. Integrity** - Messages can't be modified without detection.
- Inegrity can be achieved by hashing, digital signatures, certificates, Non-repudiation.
**3. Availability** - Systems and networks must be up and running.
- Availability can be achieved by redundancy, fault tolerance, patching.

# Non-repudiation
- Non-repudiation means a user cannot deny (repudiate) having performed a transaction. It combines authentication and integrity: non-repudiation authenticates the identity of a user who performs a transaction, and ensures the integrity of that transaction.
## Proof of integrity
- Proof of Integrity virifies that the data does no change and it remains accurate and consistent.
- This can be achieved by hashing.
## Proof of origin
- Proof of Origin proves the source of the message (Authentication)

# Authentication, Authorization, and Accounting (AAA framework)
1. **Identification** - Who you claim to be (Username)
2. **Authentication** - Prove you are who you say you are (Passwords, e.t.c)
3. **Authorization** - What access do you have based on your identification and authorization.
4. **Accounting** - Resources used: Login time, data sent and received, logout time, e.t.c.