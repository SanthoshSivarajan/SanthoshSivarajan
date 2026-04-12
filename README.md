## Identity Visualization and Mapping Platform

This concept, set of ideas, and tools are designed to provide clarity, visibility, and understanding of identity systems across on-premises and cloud environments.  

Each tool is implemented as a single PowerShell script and produces a self-contained HTML output. There are no external dependencies or additional components required, which differentiates these tools from many traditional solutions.

The platform is organized into two primary tool series: the **Canvas Series** and the **Atlas Series**.  

Additional tools and content are continuously being migrated from my personal site (https://portal.sivarajan.com/) to GitHub, where they will be maintained and enhanced over time.

---

## Platform Overview

- **Canvas Series**  
  Focused on understanding and analysis. Canvas tools provide structured visibility into identity systems, highlighting relationships, configurations, and areas that require attention.

- **Atlas Series**  
  Focused on structure and mapping. Atlas tools generate clear, point-in-time representations of environments, providing an accurate view of how systems are configured without interpretation or scoring.

---

## Key Difference

- **Canvas** → Understand the environment  
- **Atlas** → See the environment  

Canvas helps interpret and analyze identity systems.  
Atlas provides a direct, unfiltered view of structure and configuration.

---

## Getting Started

Each tool in the Canvas and Atlas series is designed to be used independently.

1. Select the area you want to explore (Active Directory, Entra ID, Microsoft 365, etc.)  
2. Choose the appropriate tool:  
   - Use **Canvas** tools for analysis and insight  
   - Use **Atlas** tools for mapping and structure  
3. Run the tool in your environment  
4. Review the generated output (HTML reports, visualizations, or structured data)

## The "Canvas" Tool Series

A set of tools and concepts designed to provide clarity, visibility, and structured understanding of identity systems across on-premises and cloud environments.

- **ADCanvas**  -   Visualize Active Directory environments, including structure, relationships, and operational context.

- **EntraIDCanvas**  -   Visualize Microsoft Entra ID environments, focusing on identities, roles, and access relationships.

- **DelegationCanvas**  -   Visualize delegated permissions across Active Directory organizational units, including identification of explicit access and potential risks.

- **ZeroTrustCanvas**  -   Visualize Zero Trust architecture within identity systems, highlighting access boundaries, controls, and policy enforcement.

- **NHICanvas**  -   Visualize Non-Human Identities (service accounts, applications, and automation identities), focusing on access, usage, and security posture.

- **AttackPathCanvas** -   Visualize identity attack paths in Active Directory, mapping privilege escalation routes, lateral movement risks, and credential exposure chains.

- **M365Canvas**  -   Visualize Microsoft 365 environments, including Exchange Online, SharePoint, OneDrive, Teams, and security configurations such as DLP policies and sensitivity labels.

- **DefenderCanvas**  -   Visualize Microsoft Defender security posture across Endpoint, Identity, Office 365, and Cloud Apps, including threat policies and detection coverage.

- **IntuneCanvas**  -   Visualize Microsoft Intune environments, including device policies, compliance status, application deployments, configuration profiles, and enrollment settings.

## The "Atlas" Tool Series

A set of tools designed to generate clear, point-in-time maps of identity and infrastructure systems, focusing on structure, relationships, and configuration without analysis or scoring.

- **ADAtlas**  -   Map Active Directory environments, including forest structure, domains, sites, trusts, and supporting services in a single, self-contained view.

- **EntraAtlas**  -   Map Microsoft Entra ID environments, including tenants, identities, roles, applications, and access relationships.

- **M365Atlas**  -   Map Microsoft 365 environments, including Exchange Online, SharePoint, OneDrive, Teams, and service configurations.

- **DefenderAtlas**  -   Map Microsoft Defender environments across Endpoint, Identity, Office 365, and Cloud Apps, including security configuration and coverage.

- **IntuneAtlas**  -   Map Microsoft Intune environments, including device configuration, compliance policies, application deployments, and enrollment structure.

- **PKIAtlas**  -   Map Active Directory Certificate Services (ADCS), including certificate authorities, templates, trust stores, and issuance structure.

- **IdentityAtlas**  -   Map identity systems across on-premises and cloud environments, providing a unified structural view of identities, roles, and relationships.
