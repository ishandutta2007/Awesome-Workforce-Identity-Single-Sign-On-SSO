# Awesome-Workforce-Identity-Single-Sign-On-SSO

## Top Workforce Identity & Single Sign-On (SSO) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Identity Providers, SSO Federation & Self-Hosted IAM*  

**Last updated: October 2026**



This repository tracks notable **commercial workforce identity platforms** and **open-source projects** that manage employee identities, enforce single sign-on across applications, and secure access to workforce resources. These tools handle authentication, authorization, MFA, and directory integration for enterprises.



**Examples** include AWS IAM Identity Center, Okta Single Sign-On, Microsoft Entra ID, Ping Identity, JumpCloud, OneLogin, Duo Security, CyberArk Identity, WorkOS, and Frontegg (the category leaders).



**Open-source emphasis**: Workforce identity is one of the strongest open-source domains. **Keycloak**, **Zitadel**, **Authentik**, **Ory**, and **Casdoor** collectively provide production-grade identity providers with SSO, MFA, and OIDC/SAML support. **Apache Syncope** handles identity governance, while **WSO2 Identity Server** brings enterprise-grade IAM. **Authelia** and **Pomerium** provide forward-auth and identity-aware proxies. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  

  **The enterprise SSO standard** — cloud identity and access management with conditional access, MFA, and integration with 10,000+ SaaS apps. **Free tier with Microsoft 365**; Premium P1/P2 for advanced features. **The reference for enterprise identity** .



- **[Okta Single Sign-On](https://www.okta.com/products/single-sign-on/)**  

  **The market-leading independent IdP** — SSO, MFA, lifecycle management, and API access management. **The most widely integrated workforce identity platform** .



- **[AWS IAM Identity Center](https://aws.amazon.com/iam/identity-center/)**  

  AWS's workforce SSO — centralized access to AWS accounts and applications. **Best for AWS-centric organizations** .



- **[Ping Identity](https://www.pingidentity.com/)**  

  Enterprise identity platform — SSO, MFA, and identity governance. **Best for large enterprises** with complex requirements.



- **[JumpCloud](https://jumpcloud.com/)**  

  **The cloud directory platform** — SSO, directory services, device management, and LDAP. **Free for up to 10 users** . **Best for SMBs wanting AD替代** .



- **[OneLogin](https://www.onelogin.com/)**  

  Workforce identity — SSO, MFA, and directory integration. **Best for mid-market enterprises** .



- **[Duo Security](https://duo.com/)**  

  **The leading MFA platform** (now Cisco) — two-factor authentication for SSO and remote access. **The standard for MFA** .



- **[CyberArk Identity](https://www.cyberark.com/)**  

  Workforce identity — SSO, MFA, and privileged access management. **Best for security-focused enterprises** .



- **[WorkOS](https://workos.com/)**  

  **The modern enterprise SSO platform** — SSO, SCIM directory sync, and audit logs for B2B SaaS. **Best for B2B SaaS companies** wanting enterprise features.



- **[Frontegg](https://frontegg.com/)**  

  **The customer identity platform** — SSO, MFA, and user management for B2B SaaS. **Best for product-led SaaS companies** .



## Open-Source GitHub Projects



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  **The most widely adopted open-source identity provider**, Apache-2.0 licensed with **36,000+ GitHub stars** . **Supports OAuth 2.0, OIDC, SAML, LDAP, and social login** . Features **SSO, MFA, user federation, identity brokering, and admin console** . **The de facto open-source SSO solution** — used by enterprises, governments, and startups worldwide . **Best for organizations wanting a full-featured, battle-tested IdP** .



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  **Identity infrastructure with multi-tenancy and API-first design**, Apache-2.0 licensed . **OIDC, OAuth2, SAML2, passkeys/FIDO2, and SCIM 2.0** . **The most modern open-source IdP** — clean UI, API-first, and multi-tenant native . **Best for modern applications wanting a developer-friendly IdP** .



- **[Authentik](https://github.com/goauthentik/authentik)**  

  **Flexible open-source identity provider**, MIT/GPL licensed with **10,000+ GitHub stars** . **OAuth2, SAML, LDAP, and proxy support** . **Flow-based authentication customization** — visual editor for login flows . **Best for organizations wanting customization flexibility** .



- **[Ory](https://github.com/ory)**  

  **Open-source identity infrastructure** — Kratos (identity management), Hydra (OAuth2), Keto (authorization), and Oathkeeper (access proxy) . Apache-2.0 licensed . **API-first, cloud-native design** . **The most modular open-source identity stack** . **Best for developers building custom identity solutions** .



- **[Casdoor](https://github.com/casdoor/casdoor)**  

  **UI-first identity and access management platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **OAuth2, OIDC, SAML, LDAP, and CAS support** . **Built-in admin console and extensive SDKs** . **Best for organizations wanting a UI-driven IAM platform** .



- **[WSO2 Identity Server](https://github.com/wso2/product-is)**  

  **Enterprise-grade open-source IAM**, Apache-2.0 licensed . **SSO, MFA, adaptive authentication, and identity governance** . **The most enterprise-focused open-source IAM** . **Best for large enterprises needing comprehensive identity management** .



- **[Apache Syncope](https://github.com/apache/syncope)**  

  **Open-source identity governance and administration (IGA)**, Apache-2.0 licensed . **User provisioning, de-provisioning, and access certification** . **The leading open-source IGA solution** . **Best for identity governance and compliance** .



- **[Authelia](https://github.com/authelia/authelia)**  

  **Open-source authentication and authorization server**, Apache-2.0 licensed with **20,000+ GitHub stars** . **2FA, SSO, and forward-auth for reverse proxies** . **The best lightweight SSO for self-hosted applications** . **Best for securing self-hosted services** .



- **[Pomerium](https://github.com/pomerium/pomerium)**  

  **Identity-aware access proxy**, Apache-2.0 licensed with **4,000+ GitHub stars** . **BeyondCorp-style access with SSO integration** . **Best for securing internal applications with zero trust** .



- **[Dex](https://github.com/dexidp/dex)**  

  **Open-source OIDC identity provider**, Apache-2.0 licensed . **Federated identity for Kubernetes and cloud-native applications** . **The standard for Kubernetes OIDC** . **Best for Kubernetes authentication** .



- **[Gluu](https://github.com/GluuFederation)**  

  **Open-source IAM platform**, Apache-2.0 licensed . **SSO, MFA, and identity federation** . **Best for organizations wanting a comprehensive IAM suite** .



- **[FusionAuth](https://github.com/FusionAuth/fusionauth)**  

  **Open-source identity and access management**, Apache-2.0 licensed . **SSO, MFA, and user management** . **Best for developers wanting a simple, self-hosted IdP** .



- **[Bouncer](https://github.com/bouncer-app/bouncer)**  

  **Open-source SSO platform** (formerly SuperTokens) — **simple, self-hosted SSO** . **Best for teams wanting lightweight SSO** .



- **[Kanidm](https://github.com/kanidm/kanidm)**  

  **Modern open-source identity management platform in Rust**, MPL-2.0 licensed . **Fast, secure, and memory-safe** . **Best for Rust enthusiasts and modern infrastructure** .



### Additional Strong Open-Source Options



- **LLDAP** — Lightweight LDAP server for self-hosted identity .

- **OpenLDAP** — The standard open-source LDAP directory .

- **FreeIPA** — Identity management for Linux/Unix environments .

- **Samba AD** — Active Directory compatible domain controller .

- **Apache Directory** — LDAP server and directory tools .

- **389 Directory Server** — Enterprise-class LDAP server from Red Hat .

- **OpenDJ** — LDAP directory services (ForgeRock) .

- **OpenAM** — Access management and federation .

- **Shibboleth** — Federated identity for education and research .

- **SimpleSAMLphp** — SAML 2.0 identity provider and service provider .



**Frameworks for building custom workforce identity solutions**: Combine **Keycloak** for the most battle-tested open-source IdP with SSO, MFA, and federation . Use **Zitadel** for modern, API-first identity with multi-tenancy . Deploy **Authentik** for flexible flow-based authentication . Choose **Ory** for modular, cloud-native identity stack . Integrate **Authelia** for lightweight SSO on self-hosted services . Use **Apache Syncope** for identity governance and compliance . Note that true enterprise workforce identity with global availability, advanced threat protection, and vendor-supported SLAs (Okta, Entra ID, Ping) remains primarily commercial territory; open-source stacks provide strong SSO, MFA, and federation foundations that require operational expertise for complete identity management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity providers control access to sensitive organizational resources. Self-hosted solutions require proper security hardening, regular patching, MFA enforcement, and compliance with data privacy regulations.

- **Identity is the new security perimeter** — a compromised IdP grants access to everything. Harden Keycloak/Zitadel deployments with MFA, rate limiting, and monitoring .

- **Open-source IAM requires operational expertise** — certificate management, key rotation, backup, and high availability are ongoing responsibilities. Commercial platforms provide managed SLAs and support .

- **SCIM provisioning** is critical for lifecycle management — ensure your chosen IdP supports SCIM for automated user provisioning and de-provisioning .

- The open-source ecosystem provides strong SSO, MFA, and federation foundations, but **global availability, advanced threat protection, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for identity architects, security engineers, and organizations seeking identity sovereignty.**  

Let's make workforce identity and SSO more open, transparent, and accessible.
