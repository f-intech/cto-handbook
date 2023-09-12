# Tech Strategy Questions

This is a list of questions to ask yourself/the team when developing your overall tech strategy.

Additional pages can be linked to each question with a breakdown of considerations.

Some of these questions will have different answers for different applications or functions. That is ok.

## Organisational
1. Where does the product org sit?
2. How do product squads manage cost (including infrastructure)?
3. What is your communications plan?
4. Who are your most important stakeholders?
5. How are projects managed?

## User Interfaces
1. Mobile application or responsive web only (if applicable)?
2. Customer-facing web application?
3. Internal web application?
4. Any thick clients?

## Application Technology Stack
1. Which languages are recommended?
2. Which languages are allowed?
3. ["Full stack cloud" or cloud agnostic approach to application building?](full_stack_vs_cloud_agnostic.md)
4. What degree of granularity for microservices (if at all)?
5. Functions as a service ("serverless") or Docker based?
6. Are low/no-code interfaces feasible?
7. What API gateway to use?
8. What identity provider to use?
9. How will you conduct A/B experiments?
10. Centralized content management system vs separate for marketing vs platform?

## Infrastructure Technology Stack
1. Which cloud or hosting provider?
2. Which physical regions to use?
3. How are the infrastructure accounts structured (domain, environment, etc)?
4. "Full stack cloud" or cloud agnostic approach to infrastructure provisioning?
5. Which Infrastructure as Code provider?
6. What is your tagging policy/nomenclature?
7. Which core server OS to build on?
8. What is the backup policy and tool?
9. Multi-tenanted or single-tenanted?

## Data Stack
1. What is your operational database stack?
2. What is your data warehouse/lake stack?
3. How will you feed data to your data warehouse?
4. What feed quality/timeliness checks will you include?
5. How will the data dictionary be maintained?

## DevSecOps
1. Which application CI/CD pipeline to use?
2. Which security scanning tool to use?
3. Which open source vulnerability scanner/manager to use?
4. Which secrets/keys scanner to use?
5. Which mobile deployment/release management tool to use?
6. Which build tools to use?
7. What is the patch management policy, and which tool to use?
8. What is the branching/code review strategy?
9. How will automated testing be integrated?
10. How are keys & secrets managed?

## Security & Compliance
1. What is your security risk appetite?
2. What compliance standards and regulations will you adhere to?
3. How often will you run pen tests?
4. What automated intrusion tests will you run?
5. What SIEM tool will you use (if any)?
6. What cloud misconfiguration checker will you use?
7. Can staff and vendors access systems without VPN/VDI?
8. What is the key/secret rotation policy?
9. What tool are you using for privileged access management (if any)?
10. What is your change management process?
11. What is your data classification policy and retention for each?

## Alerting & Monitoring
1. Which centralised logging tool?
2. Which alerting/escalation tool?
3. What will you monitor?

## Business Continuity
1. What are your Recovery Time Objective, Recovery Point Objective and Maximum Tolerable Downtime metrics?
2. Will blue/green deployments be used for maintaining uptime?

## Developer Experience
1. Which IDEs are allowed?
2. Which AI-assistants are allowed from a security perspective?

## IT
1. Will you support hybrid or remote work?
2. What tools to manage distributed assets?
3. What policies are agreed and what's the review process?
4. How are assets budgeted for?
5. How are assets managed and procured?
6. How will you manage, mitigate and eliminate shadow IT?
