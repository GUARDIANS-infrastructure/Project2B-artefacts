# UMCCR Requirements: Discovery Phase

The following requirements were captured during discovery sessions with UMCCR and have been validated through a playback session with the partner to confirm shared understanding and alignment:


| ID   | Requirement | MoSCoW |
|------|-------------|-----------------|
| R01  | The AAI solution supports federated institutional logins, including those from AAF subscribers and eduGAIN-affiliated institutions, to accommodate internal users and affiliated researchers. | Must Have |
| R02  | The AAI solution supports social identity providers, such as Google and Microsoft, to enable access for visiting researchers and unaffiliated international collaborators. | Must Have |
| R03  | Multi-Factor Authentication (MFA) is supported and configurable per login pathway, with consideration for social or unaffiliated logins. | Should Have |
| R04  | The AAI solution integrates with GUARDIANS services Jupyter, Elsa, and REMS, providing centralised authentication. | Must Have |
| R05  | The AAI solution delivers a defined set of identity claims to UMCCR services to support local authorisation decisions within Jupyter, Elsa, and REMS. These claims must include name, email address, identifier (e.g., ePPN – eduPersonPrincipalName), and home organisation. | Must Have |
| R06  | AAF acts as the central identity provider for internal UMCCR users, ensuring consistent authentication across all GUARDIANS services. AAF identities must be linked to internal user identities using a stable, persistent identifier. | Should Have |
| R07  | The AAI solution asserts a persistent user identifier (e.g., eduPersonPrincipalName) which supports user identification across services and other GUARDIANS partners. | Should Have |
| R08  | The AAI solution supports organisation filtering to limit user access to services (e.g., Peter Mac, UoM). | Could Have |
| R09  | The AAI solution supports OpenID Connect (OIDC) as the protocol for service integrations. | Must Have |
| R11  | For non-AAF users, AAI onboarding supports identity validation and post-verification tagging/entitlement allocation. | Should Have |
| R12  | AAI solution interoperates with tools like htsget, which require fine-grained user-level access enforcement to specific genomic data slices. | Should Have |
