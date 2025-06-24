# CCI Requirements: Discovery Phase

The following requirements were captured during discovery sessions with CCI and have been validated through a playback session with the partner to confirm shared understanding and alignment:

| ID   | Requirement | MoSCoW |
|------|--------------------------|-----------------|
| R25  | The AAI solution supports access to the CCI Data Discovery Portal for a broad user base, including AAF researchers, non-AAF researchers, external clinicians, and public users, through federated authentication. | Must Have |
| R26  | The AAI solution supports authentication via multiple Identity Providers (IdPs), including AAF, eduGAIN, Google, and Microsoft. ***Microsoft & Google IdP Not Required*** | Must Have |
| R27  | The AAI solution integrates with both the Data Discovery Portal and Beacon, and supports tiered access control, with different levels of access (public, restricted, sensitive) tied to user authentication. | Should Have|
| R28  | BioCommons will setup an instance of REMS (on behalf of CCI), which integrates with the AAI solution to support access request workflows and authorisation decisions. | Must Have|
| R29  | The AAI solution enables new users (particularly non-AAF) to self-register and complete onboarding without invitations. | Must Have|
| R30  | The AAI solution login flow supports user terms & conditions acceptance. | Must Have|
| R31  | The AAI solution supports assigning entitlements to users once data access requests are approved. | Could Have |
| R32  | The AAI solution supports additional identity validation steps (e.g. institutional vetting) as part of the data access workflow. | Could Have |
| R33  | The AAI solution enables CCI internal users to continue to be managed via Azure EntraID, while AAI will federate external users. | Could Have |
| R34  | The AAI solution has the functionality for admin to lock individuals out of accessing GUARDIANS services. | Could Have |
