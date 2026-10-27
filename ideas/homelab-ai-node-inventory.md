# Homelab / AI Node Inventory & Decision Log

**Purpose and information boundary**  
Record high-level roles, goals, constraints, and decisions to help choose future projects.  
Generic functional labels only. No machine identifiers, network details, credentials, configurations, versions, or combinations of clues.

## 1. Roles

| Generic role                       | Purpose or goal                                      | High-level constraint                  |
|------------------------------------|------------------------------------------------------|----------------------------------------|
| Primary AI assistant host          | General AI assistance and coordination of selected services | Prefer local models for routine tasks; physical space and power limits |
| Network edge                       | Primary firewall and traffic control                 | Must stay reliable; limited hands-on maintenance preferred |
| Resilience / maintenance support   | Support resilience and high-level maintenance planning | Secondary role; should not become a single point of failure |
| Future less-trusted device policy  | Apply safety policies for less-trusted devices       | Keep isolated from main management paths |

## 2. Key decisions and constraints

| Decision or constraint                                      | Reason or trade-off                                      | Status   | Revisit if…                                      |
|-------------------------------------------------------------|----------------------------------------------------------|----------|---------------------------------------------------|
| Prefer local models for routine AI tasks                    | Privacy, latency, and reduced external dependency        | Current  | Cloud-only features become essential or available capacity is reached |
| Dedicated network-edge role                                 | Separation of concerns and reliability                   | Current  | Network-edge role becomes a maintenance burden or fails repeatedly |
| Functional roles instead of hardware mapping                | OPSEC and easier long-term tracking                      | Current  | A clear need arises to track specific hardware lifecycles |
| Avoid exposing management paths to less-trusted segment     | Reduce attack surface                                    | Current  | Less-trusted devices require tighter integration  |

## 3. Open experiments and next low-risk steps

**Experiment: Clarify primary vs. secondary AI role boundaries**  
- What we want to learn: Which tasks stay on the primary AI host vs. move to the resilience/maintenance support role.  
- Why it matters: Keeps the system simple and avoids accidental single points of failure.  
- Safe first step: List 3–5 current or planned AI tasks using only generic names and assign each to a role at the functional level only.  
- Boundary or stop condition: Stop if any assignment requires mentioning specific hardware, private workflows, services, data sources, IPs, or configurations.  
- Outcome: (to be filled after review)
