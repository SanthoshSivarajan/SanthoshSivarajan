## Identity Visualization and Mapping Platform

This concept, set of ideas, and tools are designed to provide clarity, visibility, and understanding of identity systems across on-premises and cloud environments.

Each tool is implemented as a single PowerShell script and produces a self-contained HTML output. There are no external dependencies or additional components required, which differentiates these tools from many traditional solutions.

The platform is organized into four tool series: the **Outline Series**, the **Atlas Series**, the **Canvas Series**, and the **Lens Series**.

Additional tools and content are continuously being migrated from my personal site (<https://portal.sivarajan.com/>) to GitHub, where they will be maintained and enhanced over time.

---

## Platform Overview

- **Outline Series**  
**Current-state documentation.** Outline tools answer the question "what is actually configured here, right now?" and write the answer down as a single file. No interpretation, no scoring, no recommendations — a record you can hand to an auditor, an acquirer, an incoming team, or your own successor.

- **Atlas Series**  
Focused on structure and mapping. Atlas tools generate clear, point-in-time representations of environments, providing an accurate view of how systems are configured without interpretation or scoring.

- **Canvas Series**  
Focused on understanding and analysis. Canvas tools provide structured visibility into identity systems, highlighting relationships, configurations, and areas that require attention.

- **Lens Series**  
Focused on change over time. Lens tools compare two points in time and report what moved, so drift becomes visible rather than assumed.

---

## Key Difference

| Series | Question it answers |
|---|---|
| **Outline** | *What do we have?* — Document the current state |
| **Atlas** | *What does it look like?* — See the environment |
| **Canvas** | *What does it mean?* — Understand the environment |
| **Lens** | *What changed?* — Track how it changes |

Outline writes down the facts.  
Atlas provides a direct, unfiltered view of structure and configuration.  
Canvas helps interpret and analyze identity systems.  
Lens shows what changed between two points in time.

The four are designed to be used in that order, but each stands on its own. Every tool is read-only, runs as a single PowerShell script, produces one self-contained HTML file, and sends nothing anywhere.

---

## Getting Started

Each tool in the Outline, Atlas, Canvas, and Lens series is designed to be used independently.

1. Select the area you want to explore (Active Directory, Entra ID, Microsoft 365, etc.)
2. Choose the appropriate tool:
   - Use **Outline** tools to record and document the current state
   - Use **Atlas** tools for mapping and structure
   - Use **Canvas** tools for analysis and insight
   - Use **Lens** tools to compare two points in time
3. Run the tool in your environment
4. Review the generated output (HTML reports, visualizations, or structured data)

## The "Outline" Tool Series

Active Directory and identity systems are often the oldest and least documented parts of an estate — upgraded, merged and inherited across decades and staff changes, until nobody can fully describe what is there. That gap becomes expensive during an acquisition, a migration, an audit, or a handover.

Outline tools close it. They produce a written record of how an environment is configured at a single point in time, in a form a non-specialist can read. No scoring, no grading, no remediation advice — they document what exists and leave the judgement to an assessment.

- **ADOutline** - Current-state documentation for an Active Directory forest: topology, object populations, identity platform integrations, security-relevant configuration, and forest lineage. 47 sections and 11 diagrams in one self-contained HTML file, produced in about twenty seconds. Requires no RSAT and collects from a non-domain-joined machine.

## The "Atlas" Tool Series

A set of tools designed to generate clear, point-in-time maps of identity and infrastructure systems, focusing on structure, relationships, and configuration without analysis or scoring.

- **ADAtlas** - Map Active Directory environments, including forest structure, domains, sites, trusts, and supporting services in a single, self-contained view.

- **EntraAtlas** - Map Microsoft Entra ID environments, including tenants, identities, roles, applications, and access relationships.

- **M365Atlas** - Map Microsoft 365 environments, including Exchange Online, SharePoint, OneDrive, Teams, and service configurations.

- **DefenderAtlas** - Map Microsoft Defender environments across Endpoint, Identity, Office 365, and Cloud Apps, including security configuration and coverage.

- **IntuneAtlas** - Map Microsoft Intune environments, including device configuration, compliance policies, application deployments, and enrollment structure.

- **PKIAtlas** - Map Active Directory Certificate Services (ADCS), including certificate authorities, templates, trust stores, and issuance structure.

- **IdentityAtlas** - Map identity systems across on-premises and cloud environments, providing a unified structural view of identities, roles, and relationships.

## The "Canvas" Tool Series

A set of tools and concepts designed to provide clarity, visibility, and structured understanding of identity systems across on-premises and cloud environments.

- **ADCanvas** - Visualize Active Directory environments, including structure, relationships, and operational context.

- **EntraIDCanvas** - Visualize Microsoft Entra ID environments, focusing on identities, roles, and access relationships.

- **DelegationCanvas** - Visualize delegated permissions across Active Directory organizational units, including identification of explicit access and potential risks.

- **ZeroTrustCanvas** - Visualize Zero Trust architecture within identity systems, highlighting access boundaries, controls, and policy enforcement.

- **NHICanvas** - Visualize Non-Human Identities (service accounts, applications, and automation identities), focusing on access, usage, and security posture.

- **AttackPathCanvas** - Visualize identity attack paths in Active Directory, mapping privilege escalation routes, lateral movement risks, and credential exposure chains.

- **M365Canvas** - Visualize Microsoft 365 environments, including Exchange Online, SharePoint, OneDrive, Teams, and security configurations such as DLP policies and sensitivity labels.

- **DefenderCanvas** - Visualize Microsoft Defender security posture across Endpoint, Identity, Office 365, and Cloud Apps, including threat policies and detection coverage.

- **IntuneCanvas** - Visualize Microsoft Intune environments, including device policies, compliance status, application deployments, configuration profiles, and enrollment settings.

## The "Lens" Tool Series

A set of tools designed to compare an environment against an earlier record of itself, so configuration drift is reported rather than assumed.

- **ADLens** - Track how an Active Directory forest changes over time, comparing two point-in-time records and reporting what moved.
