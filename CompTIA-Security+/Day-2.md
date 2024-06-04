# Gap Analysis
- Gap analysis is the study of where we are compared to where we are supposed to be.
- It may require extensive research and can take weeks or months.
- It involves data gathering and technical research.

## Choosing the Framework
1. Work towards a known baseline. This can be an internal set of goals.
2. Determine the end goal.
3. Evaluate people and processes
	- Get a baseline of employees i.e. Their formal experience, current training or knowledge of security policies and procedures.
	- Examine the current IT systems by researching existing IT systems or evaluating existing security plicies.
4. Compare and Contrast
	- Evaluate existing systems (The comparison).
	- Identify weaknesses.
	- Create a detailed analysis that examines broad security categories.
5. The analyis and report
	- Create the final comparison that details baseline objectives and shows a clear view of the current state.
	- Detail steps to get from the current security to the goal. Includes money, time and lots of change controls.
	- Create the final gap analysis report that formally describes the current state and has recommendations for meeting the baseline.

# Zero Trust
- Zero Trust security means that no one is trusted by default from inside or outside the network, and verification is required from everyone trying to gain access to resources on the network.

## How to implement zero trust (Planes of operation)
1. Split the network into functional planes.
2. Data plane
	- Process the frames, packets and network data.
	- Processing, forwarding, trunking, encrypting, NAT
3. Control plane
	- Manages the actions of the data plane.
	- Define policies and rules.
	- Determine how packets should be forwarded.
	- Routing tables, session tables, NAT tables.

## Controlling trust
1. Adaptive identity - Examining the identity of an individual and applying security controls based on the information gathered.
	- Consider the source and the requested resources.
	- Multiple risk indicators - Relationship to the organization, physical location, type of connection, IP address, etc.
	- Make the authentication stronger if needed.
2. Threat scope reduction -Decrease the number of possible entry points.
3. Policy-driven access control - Combine the adaptive identity with a predefined set of rules.

## Security zones
- Used to know where one is connected from.

## Policy enforcement point
1. Subjects and systems - End users, applications, non-human entities.
2. Allow, monitor and terminate connections.

## Applying trust in the planes
1. Policy Decision Point - There's a process for making an authentication decision.
2. Policy engine - Evaluates each access decision based on policy and other information sources. Grant, deny or revoke.
3. Policy Administrator - Communicates with the policy enforcement point.
	- Generates access tokens or credentials.
	- Tells the PEP to allow or disallow access.

# Physical Security
1. Barricades/Bollards - Prevent access.
2. Access control vestibules - A room you must pass through to gain access to the other rooms.
3. Fencing
4. Video Surveillance
5. Guards and access badges
6. Lighting
7. Sensors

# Deception and Distruption
1. Honeypots - Attract attackers and trap them there.
2. Honeynets
3. Honeyfiles
4. Honeytokens - Track the malicious actors.
