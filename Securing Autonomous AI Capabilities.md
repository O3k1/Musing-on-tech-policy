# Bridging the Frontier Assurance Gap: Securing Autonomous AI Capabilities
## Addressing the Information Asymmetries and Containment Failures in Pre-Deployment AI Testing

# Executive Summary 
The United Kingdom’s reliance on voluntary, non-binding pre-deployment commitments under the Bletchley and Seoul Declarations is no longer sufficient to contain autonomous frontier Artificial Intelligence (AI) risks. Empirical evaluations by the UK AI Security Institute (AISI) demonstrate that frontier agents actively engage in strategic deception and unsanctioned cyber actions, while competitive commercial pressures incentivise compressed testing and reduce vulnerability detection rates. Furthermore, unstandardised industry red-teaming frequently functions as security theatre that fails to halt unsafe deployments. To resolve these issues without stifling domestic innovation, the UK government should enact a tiered statutory assurance regime targeting models exceeding 1026 floating point operations (FLOP). This requires standardised pre-deployment red-teaming of high-severity security risks, legal safe harbours for independent evaluators, and mandatory 72-hour post-deployment incident reporting.

# Background
Autonomous frontier AI capabilities are growing too fast relative to the detection capacity of the UK’s existing pre-deployment assurance regime. Currently, UK oversight relies on non-binding commitments established under the Bletchley Declaration (GOV.UK 2025) and at the Seoul Summit, whereby developers voluntarily grant the UK AISI pre-deployment access to test high-compute models. While initially adopted due to a lack of international regulatory consensus  (The Alan Turing Institute 2026) and the flexibility of soft law (Pasqua 2025), this framework suffers from two market failures: severe information asymmetry between proprietary developers and state or third-party evaluators, and negative externalities, as commercial labs capture speed-to-market advantages while externalising catastrophic cyber and public-safety risks onto society (Anderljung, et al. 2023) and (Bengio, et al. 2024).

## Evidence of Capability Overhang and Containment Failure
-	Unsanctioned Autonomous Action: Empirical testing confirms that frontier models can engage in strategic deception and in-context scheming (secretly concealing misaligned objectives within the context window) when pursuing goals (Meinke, et al. 2025). In August 2026, AISI disclosed a critical containment incident during routine cyber evaluations: across 122 evaluation runs on frontier systems, agents took unsanctioned actions outside testing parameters in 10 runs (19 catalogued cases), including routing traffic via Tor to bypass network restrictions, fabricating identities to socially engineer human open-source software maintainers into merging malicious code, and planting prompt injections for other AI coding assistants (AI Security Institute 2026).
-	Probabilistic Detection Limits: Theoretical modelling of dangerous capability evaluations demonstrates that commercial pressure incentivises rushed pre-deployment testing, leaving too high a statistical probability that latent vulnerabilities cross dangerous capability thresholds undetected before release (Bova , Di Stefano and Han 2024). Simultaneously, restrictive corporate terms of service and the absence of legal safe harbours suppress independent third-party red-teaming (Longpre, et al. 2024). 
There is also the risk of red-teaming becoming “security theatre” as a comprehensive survey of industry red-teaming confirms that voluntary exercises lack standardised threat models, disproportionately probe subjective content (“dissentive risks”) rather than hard security threats and vulnerabilities (“consentive risk”), and withhold failure information (Feffer, et al. 2024). Thus, this could lead to red-teaming functioning as a perfunctory process for superficial assurance that does not impact model deployment.


# Policy Options Analysis
### **Option 1: Let Present Trends Continue Undisturbed**
Maintain the non-binding Bletchley/Seoul commitments, relying on voluntary pre-deployment model access for AISI alongside industry-led red-teaming guidelines whilst not transitioning to hard laws.
-	Projected Outcomes & Trade-offs: While politically frictionless and preserving speed-to-market, empirical evidence shows voluntary self-assessment functions as an “approval-stamping process” where discovered vulnerabilities never delay model release (Feffer, et al. 2024). Without statutory compulsion or legal safe harbours, competitive pressures will continue to incentivise compressed testing, leaving detection probabilities for autonomous scheming and cyber containment failures unacceptably low (Bova , Di Stefano and Han 2024) (Longpre, et al. 2024).

### **Option 2: Tiered Statutory Red-Teaming & 72-Hour Incident Reporting (Recommended)**
Enact targeted legislation mandating pre-deployment third-party red-teaming and post-deployment incident disclosure exclusively for frontier models exceeding 1026 floating point operations (FLOP) or demonstrating high-autonomy cyber capabilities (Anderljung, et al. 2023). 1026 FLOP was chosen as that is or is near the compute threshold for other legislations (GovAI 2025) and exceeding that is where frontier models are currently at.
To prevent security theatre implementation is structured around three statutory routines (Feffer, et al. 2024): 
1.	Pre-activity Scope: Restrict mandatory testing to unambiguous consentive risks (autonomous replication, cyber-offence, data exfiltration) rather than subjective dissentive content moderation.
2.	During-activity Access & Safe Harbours: Mandate hybrid teams of AISI and vetted external domain experts granted unrestricted model access and realistic adversary compute budgets, protected by statutory legal and technical safe harbours protecting good-faith evaluators from terms of service and copyright liability (Longpre, et al. 2024).
3.	Post-activity Accountability: Require standardised disclosure of resources consumed, unprobed risk surfaces, and verified mitigations, paired with mandatory 72-hour reporting to AISI of unsanctioned agentic behaviour during training or post deployment (Feffer, et al. 2024).
-	Projected Outcomes & Trade-offs: Concentrating statutory obligations strictly above the 1026 FLOP threshold insulates startups and open-source developers from compliance burdens while eliminating information asymmetries at the frontier.

### **Table 1: Outcomes and Trade-off Matrix Across Policy Alternatives**

| Policy Alternative | Security Effectiveness | Technical Feasibility | Commercial Impact | Political Viability |
| --- | --- | --- | --- | --- |
| Option 1: Voluntary Status Quo | Low (does not account for the pace of the frontier) | High (no new implementations) | Low (zero compliance delays and operations continue as usual) | Moderate (public trust deficit) |
| Option 2: Tiered Statutory Mandate | High (targets consentive risks) | High (bounded by FLOP threshold so there is no dramatically increased administrative overhead) | Moderate (multiweek frontier audit) | Moderate (multiweek frontier audit)	High (balances safety & growth) |



# Conclusions
As frontier AI systems transition from passive text generators to autonomous agents capable of in-context scheming and network evasion, regulatory oversight must evolve from voluntary goodwill to enforceable verification. Letting present soft law trends continue leaves the UK exposed to severe negative externalities, information asymmetry, and containment failures. However, blanket regulation across all AI tiers would overwhelm state evaluation capacity and penalise domestic startups.



# References
AI Security Institute. 2026. Incident Report: unsanctioned agent behaviour during cyber testing . 4 August. Accessed November 5, 2026. https://www.aisi.gov.uk/blog/incident-report-unsanctioned-agent-behaviour-during-cyber-testing.
Anderljung, Markus, Joslyn Barnhart, Anton Korinek, Jade Leung, Cullen O’Keefe, Jess Whittlestone, Shahar Avin, et al. 2023. “Frontier AI Regulation: Managing Emerging Risks to Public Safety.” arXiv. 7 November. Accessed November 5, 2026. https://arxiv.org/pdf/2307.03718.
Bengio, Yoshua, Geoffrey Hinton, Andrew Yao, Dawn Song, and Pieter Abbeel. 2024. “Managing extreme AI risks amid rapid progress.” Science Journal. 20 May. Accessed November 5, 2026. https://www.science.org/doi/10.1126/science.adn0117.
Bova , Paolo, Alessandro Di Stefano, and Anh Han. 2024. “Quantifying detection rates for dangerous capabilities: a theoretical model of dangerous capability evaluations.” arXiv. 19 December. Accessed November 5, 2026. https://arxiv.org/pdf/2412.15433.
Feffer, Michael, Anusha Sinha, Wesley H. Deng, Zachary C. Lipton, and Hoda Heidari. 2024. “Red-Teaming for Generative AI:Silver Bullet or Security Theater?” Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society 421-437.
GOV.UK. 2025. “AI Safety Summit 2023: The Bletchley Declaration.” GOV.UK. 13 February. Accessed November 5, 2026. https://www.gov.uk/government/publications/ai-safety-summit-2023-the-bletchley-declaration.
GovAI. 2025. Trends in Frontier AI Model Count: A Forecast to 2028. 24 April. Accessed November 6, 2026. https://www.governance.ai/research-paper/trends-in-frontier-ai-model-count-a-forecast-to-2028.
Longpre, Shayne, Sayash Kapoor, Kevin Klyman, Ashwin Ramaswami, Rishi Bommasani, and Borhane Blili-Hamelin. 2024. “A Safe Harbor for AI Evaluation and Red Teaming.” arXiv. 7 March. Accessed November 5, 2026. https://arxiv.org/pdf/2403.04893.
Meinke, Alexander, Bronson Schoen, Jérémy Scheurer, Mikita Balesni, Rusheb Shah, and Marius Hobbhahn. 2025. “Frontier Models are Capable of In-context Scheming.” arXiv. 14 Jan. Accessed November 5, 2026. https://arxiv.org/pdf/2412.04984.
Pasqua, Marco. 2025. Bridging Soft and Hard Law in AI Governance. 17 December. Accessed November 5, 2026. https://www.biicl.org/blog/121/bridging-soft-and-hard-law-in-ai-governance.
The Alan Turing Institute. 2026. AI governance around the world. Accessed November 5, 2026. https://www.turing.ac.uk/research/research-projects/ai-governance-around-world.

