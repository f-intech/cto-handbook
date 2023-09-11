# Tech Strategy Questions

This is a list of questions to ask yourself/the team when developing your overall tech strategy.

Additional pages can be linked to each question with a breakdown of considerations.

Some of these questions will have different answers for different applications or functions. That is ok.

## Organisational
1. Where does the product org sit?
2. How do product squads manage cost (including infrastructure)?

## User Interfaces
1. Mobile application or responsive web only (if applicable)?
2. Customer-facing web application?
3. Internal web application?
4. Any thick clients?

## Application Technology Stack
1. Which languages are recommended?
2. Which languages are allowed?
3. "Full stack cloud" or cloud agnostic approach to application building?
4. Functions as a service ("serverless") or Docker based?
5. Are low/no-code interfaces feasible?

## Infrastructure Technology Stack
1. Which cloud or hosting provider?
2. Which physical regions to use?
3. How are the infrastructure accounts structured (domain, environment, etc)?
4. "Full stack cloud" or cloud agnostic approach to infrastructure provisioning?
5. Which Infrastructure as Code provider?
6. What is your tagging policy/nomenclature?
7. 

## Data Stack
1. What is your operational database stack?
2. What is your data warehouse/lake stack?
3. How will you feed data to your data warehouse?
4. What feed quality/timeliness checks will you include?

## DevSecOps
1. Which application CI/CD pipeline to use?
2. Which security scanning tool to use?
3. Which mobile deployment/release management tool to use?
4. Which build tools to use?

## Security & Compliance
1. What is your security risk appetite?
2. How often will you run pen tests?
3. What automated intrusion tests will you run?
4. What SIEM tool will you use (if any)?
5. What cloud misconfiguration checker will you use?
6. Can staff and vendors access systems without VPN/VDI?
7. How are keys & secrets managed?
8. What is the key/secret rotation policy?

## Alerting & Monitoring
1. Which centralised logging tool?
2. Which alerting/escalation tool?

## Business Continuity
1. What are your Recovery Time Objective, Recovery Point Objective and Maximum Tolerable Downtime metrics?
