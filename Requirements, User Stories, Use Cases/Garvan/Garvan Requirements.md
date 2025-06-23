# Garvan Requirements: Discovery Phase

The following requirements were captured during discovery sessions with Garvan and have been validated through a playback session with the partner to confirm shared understanding and alignment:

| ID   | Requirement Description | MoSCoW |
|------|--------------------------|-----------------|
| R13  | The AAI solution supports single sign-on (SSO) for Garvan services – REDCap, CTRL, REMS, RDDP (long-term/stretch goal). | Must Have |
| R14  | The AAI solution support OpenID Connect (OIDC) as the protocol for service integrations. | Must Have |
| R15  | The AAI solution support federation with a mix of institutional and non-institutional identity providers, including AAF subscribers, eduGAIN institutions, Google, Microsoft, GitHub, ORCID. | Must Have |
| R16  | The AAI solution use a persistent, non-email-based identifier (e.g., ePPN or another stable unique ID) that is consistent across services and resilient to changes in user email addresses. | Must Have |
| R17  | The AAI solution supports portable identifiers. Users retain identity continuity when moving institutions; Identity is be re-established under the new institution to meet ethics and audit obligations tied to data ownership by the host organisation. | Won't Have |
| R18  | The AAI solution supports MFA signalling, with enforcement configurable per integrated service. | Must Have |
| R19  | The AAI solution delivers a defined set of identity claims to downstream services, including name, email address, Identifier (ePPN – eduPersonPrincipalName), and home organisation. | Must Have |
| R20  | The AAI solution supports self-registration for non-AAF users, allowing them to select from approved identity providers. Each integrated service should support service-specific onboarding, including terms & conditions acceptance. | Must Have |
| R21  | The AAI solution supports Auth0 as an identity provider. | Could Have|
| R22  | Administrative access to the AAI platform is provided, allowing approved admins to track, monitor, and audit user access. | Should Have|
| R23  | The AAI platform exposes backend APIs, allowing integration with internal databases or external service workflows. | Could Have|
| R24  | The AAI platform provides access to authentication logs, enabling audit trails and security monitoring as needed by participating services. | Could Have|
