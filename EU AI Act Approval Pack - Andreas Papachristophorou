# W7D2_LAB_EU_AI_ACT_Classify_your_product
- Week 7 / Day 2
- Student: Andreas Papachristophorou
- Course: AI Consulting & Integration 2026-07
- Date: 2026-08-18
---

# Phase 1 — Build the hidden client brief


## Private answer key — keep hidden from partner

| Case | Client brief for partner | Intended category in private answer key | Why you chose it |
| --- | --- | --- | --- |
| 1 | A pub chain wants an AI system for football match days that watches CCTV feeds and flags individual guests who are likely to become violent before any incident occurs. The system uses body language, facial expressions, movement patterns, clothing, and previous venue incident data to create a “violence risk” alert for security staff. Security guards receive the alert and may monitor, question, refuse service to, or remove the person. The people affected are ordinary customers and guests. A security guard can override the alert, but the AI warning strongly influences the decision. | Prohibited | The system predicts whether individual customers are likely to become violent based on CCTV profiling and behavioural signals before they have actually committed an offence, which risks unlawful predictive policing-style treatment and exclusion. |
| 2 | A port authority wants an AI traffic management system for a major passenger and cargo harbour. The system analyses live vessel locations, weather, tide conditions, cargo type, passenger volume, fuel status, and berth availability to recommend which ships may enter, dock, wait, or reroute. The output is used by harbour control officers to manage vessel movements, including ferries carrying passengers and ships transporting hazardous materials. The AI ranking is the main basis for operational decisions during busy periods. | High-risk | The system supports operational decisions in critical transport infrastructure by influencing vessel movements, docking priority, and routing for passenger and hazardous cargo ships, so approval should depend on strong safety controls, documentation, logging, and human oversight. |
| 3 | A cruise company wants to launch an AI chatbot on its booking portal to help passengers choose shore excursions. Customers type their preferences, budget, mobility needs, travel style, and available time, and the chatbot recommends excursions from the company’s existing catalogue. If no suitable option is found, the chatbot may suggest a custom self-guided itinerary. The people affected are cruise passengers making travel choices. The user can choose to allow automatic booking. The experience should be seamless, as if customers were chatting with a human travel advisor. | Limited risk | The system is an AI chatbot that interacts directly with customers and gives personalised travel recommendations, so the main AI Act obligation is to clearly inform users that they are interacting with AI. |
| 4 | A travel content creator wants an AI assistant that reviews their own travel itinerary, notes, photos, and draft captions to suggest more engaging social media posts. The system proposes caption ideas, hashtags, posting times, and optional edits to the creator’s own text. It does not automatically publish content. The creator reviews and edits every suggestion before posting. If other people appear in photos or interviews, the creator is responsible for consent and privacy checks. | Minimal risk | The system only helps a content creator draft and improve social media posts, with human review before publishing, and does not make decisions affecting people’s rights, safety, employment, education, essential services, or legal status. |


### Case 1

A pub chain wants an AI system for football match days that watches CCTV feeds and flags individual guests who are likely to become violent before any incident occurs. The system uses body language, facial expressions, movement patterns, clothing, and previous venue incident data to create a “violence risk” alert for security staff. Security guards receive the alert and may monitor, question, refuse service to, or remove the person. The people affected are ordinary customers and guests. A security guard can override the alert, but the AI warning strongly influences the decision.

### Case 2

A port authority wants an AI traffic management system for a major passenger and cargo harbour. The system analyses live vessel locations, weather, tide conditions, cargo type, passenger volume, fuel status, and berth availability to recommend which ships may enter, dock, wait, or reroute. The output is used by harbour control officers to manage vessel movements, including ferries carrying passengers and ships transporting hazardous materials. The AI ranking is the main basis for operational decisions during busy periods.

### Case 3

A cruise company wants to launch an AI chatbot on its booking portal to help passengers choose shore excursions. Customers type their preferences, budget, mobility needs, travel style, and available time, and the chatbot recommends excursions from the company’s existing catalogue. If no suitable option is found, the chatbot may suggest a custom self-guided itinerary. The people affected are cruise passengers making travel choices. The user can choose to allow automatic booking. The experience should be seamless, as if customers were chatting with a human travel advisor.

### Case 4

A travel content creator wants an AI assistant that reviews their own travel itinerary, notes, photos, and draft captions to suggest more engaging social media posts. The system proposes caption ideas, hashtags, posting times, and optional edits to the creator’s own text. It does not automatically publish content. The creator reviews and edits every suggestion before posting. If other people appear in photos or interviews, the creator is responsible for consent and privacy checks.

---

# Phase 2 — Review your partner as the consultant

## Consulting review table

| Case | Likely category | Why this is your first-pass call | Proposed AI architecture | Provider / deployer / vendor | Required obligations or controls | Decision |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | High-risk | AI strongly influences mortgage approval, affecting access to essential financial services. | AI scoring / decision-support tool; loan officer makes final decision; decision logs kept. | Provider: customer or developer, depending on branding and modification. Deployer: lender. Vendor: LLM/scoring model provider. | Human oversight, audit logs, fairness testing, explainability, data governance, risk management, technical documentation. | Approve with controls. |
| 2 | Limited risk / transparency | Customers interact directly with an AI chatbot, so they must be told clearly that it is AI. | Website chatbot answers shipment-tracking questions; escalation to human support available; conversations logged where needed. | Provider: consultant/software developer or client if branded/modified. Deployer: client. Vendor: LLM/chatbot platform provider. | Clear AI disclosure, no pretending to be human, limit to tracking questions, human handover, GDPR for personal data. | Approve with controls. |
| 3 | Minimal risk | AI only filters obvious spam comments and does not affect rights, safety, employment, finance, or essential services. | Background spam filter flags/hides suspicious reviews; moderators can review disputed cases; basic moderation logs kept. | Provider: system designer or vendor. Deployer: website owner. Vendor: spam-filtering platform provider. | Light operational controls, false-positive review process, basic logs, GDPR if user data is processed. | Approve with light controls. |
| 4 | Prohibited | The system creates a vague employee “loyalty score” using intrusive surveillance and may trigger harmful performance reviews. | No lawful architecture as proposed; redesign as a transparent job-related performance-support dashboard with human review. | Provider: consultant/vendor/developer. Deployer: employer. Vendor: camera analytics or AI platform provider. | Do not deploy as proposed, avoid social scoring and disproportionate surveillance, consult legal/HR/worker representatives, use only objective job-related metrics if redesigned. | Deny and redesign. |

---

# Phase 3 — Write the approval pack


## Executive summary and case-by-case approval review

## <b>Executive Summary</b>

The four proposed AI use cases create different levels of AI Act risk. The mortgage approval system is high-risk because it affects access to essential financial services. The customer support chatbot is limited risk because users interact directly with AI and must be clearly informed. The spam review filter is minimal risk because it only filters obvious spam comments and does not affect important rights or services. The employee loyalty scoring system should be denied and redesigned because it uses intrusive workplace surveillance and creates a vague behaviour-based score with possible harmful consequences for employees.

### Case 1

<b>Client request summary: </b>Our loan approval team is drowning in paperwork. We want an AI that takes a look at a customer's credit history, income, and background, and then automatically decides whether to approve or deny their mortgage application. Is that something your team can handle?

<b>Inferred AI Act category: </b>High Risk

<b>Why this category applies: </b>This is high-risk because it uses AI to make or strongly influence mortgage approval decisions. The system affects access to essential financial services and can significantly impact people’s lives. It is not prohibited by default, but it should not be launched as a fully automatic approval/denial tool without human oversight, audit logs, fairness testing, and explainability.

<b>Proposed architecture:</b>

- Business trigger:<b> Loan Approvals</b>
- Model or system behaviour:<b> Automated Scoring / Discission Support</b>
- Human review point<b>: Final decision </b>
- Record, logging, or disclosure layer:<b> Records tb kept for minimum 6 months</b>

<b>Role map:</b>

| Role | Who is it? | Why? |
| --- | --- | --- |
| Provider | Customer or software developer | Depends on who develops, modifies, brands, and places the system on the market. |
| Deployer | Customer | System User |
| Third-party vendor | LLM or scoring model provider |  |

<b>Compliance implications:</b>

1. Risk management system
2. Data and data governance
3. Technical documentation
4. Record-keeping and logging
5. Transparency and user information
6. Human oversight
7. Accuracy, robustness, and cybersecurity
8. Conformity assessment
9. EU declaration of conformity and CE marking
10. Registration
11. Post-market monitoring and serious incident reporting

<b>Decision: Approve with controls</b>

<b>Lawful redesign option: </b>The system should only be used as a decision-support tool. The final decision should rest with the loan officer and should not be automated. Compliance implications should be addressed, and procedures and processes should be implemented to ensure compliance.

### Case 2

<b>Client request summary: </b>Our customer support team is getting the same basic questions over and over. We want to put a smart chatbot on our website homepage to answer track-and-trace shipping questions. Is that a safe project to take on?

<b>Inferred AI Act category: </b>Limited risk / transparency

<b>Why this category applies: </b>Under the EU AI Act, when people interact directly with an AI system, they usually need to be <b>clearly informed</b> that it is AI, unless it is obvious from the context.<br />

<b>Proposed architecture:</b>

- Business trigger:<b> Client questions about shipment tracking</b>
- Model or system behaviour:<b> Automated Tracking Support</b>
- Human review point<b>: No routine review, but escalation to human support should be available.</b>
- Record, logging, or disclosure layer:<b> Log conversations where needed for quality and complaint handling.</b><br />

<b>Role map:</b>

| Role | Who is it? | Why? |
| --- | --- | --- |
| Provider | Consultant or software developer | This depends on who builds, modifies, hosts, and brands the system. If the system is significantly modified or placed on the market under the client’s name, the client may become the provider. |
| Deployer | Client | The client uses the chatbot on its website to support customers. |
| Third-party vendor | LLM or chatbot platform provider | A third-party vendor may provide the underlying model, hosting, chatbot platform, or integration tools. |

<b>Compliance implications: </b>Clearly label it as an AI chatbot.

<b>Decision: Approve with controls</b>

<b>If denied, lawful redesign option:</b>

- Clearly label it as an AI chatbot.
- Do not pretend it is a human agent.
- Offer handover to human support.
- Keep answers limited to shipping and tracking topics.
- Avoid giving legal, refund, or complaint decisions automatically.
- Follow GDPR if the chatbot uses personal data like tracking numbers, names, addresses, or order details.

### Case 3

<b>Client request summary: </b>Our website keeps getting hit with spam reviews that say 'Click here to win a prize.' We want a simple AI filter in the background that flags and hides those comments before they go live. Is that going to cause a regulatory headache for us?

<b>Inferred AI Act category: </b>Minimal risk

<p>
<b>Why this category applies:</b> AI is only filtering obvious spam comments before publication. It does not make decisions affecting people’s legal rights, employment, education, access to essential services, safety, or financial opportunities. 
</p>

<b>Proposed architecture:</b>

- Business trigger:<b> Spam review filtering </b>
- Model or system behaviour:<b> Automated filtering</b>
- Human review point<b>: Moderators can review flagged comments, especially if a user disputes the decision. </b>
- Record, logging, or disclosure layer: <b>Keep basic logs of flagged comments and moderation decisions for quality control and error correction.</b>

<b>Role map:</b>

| Role | Who is it? | Why? |
| --- | --- | --- |
| Provider | System Designer or Vendor | A simple tool purchase form a third party |
| Deployer | Client | System user |

<p>
<b>Compliance implications: </b>No major AI Act obligations 
</p>

<b>Decision: Approve - with light operational controls</b>

### Case 4

<b>Client request summary: </b> We want to build an internal tool that scans our office cameras and monitors employee keystrokes. It should give everyone a rolling 'loyalty score.' If their score drops too low, the system automatically triggers a review for performance. Can you build this?<br />

<p>
<b>Inferred AI Act category: </b>Prohibited 
</p>

<b>Why this category applies: </b>This looks like a form of <b>social scoring / behaviour scoring</b> in an employment context, with harmful consequences for the employee. Uses intrusive surveillance. Punish people through performance review. The score is vague and behaviour-based.

<b>Proposed architecture: </b>No lawful architecture should be approved for the proposed loyalty-scoring system. The design should be rejected and replaced with a narrower performance-support tool based on transparent, job-related metrics and human review.<br />

<b>Role map:</b>

| Role | Who is it? | Why? |
| --- | --- | --- |
| Provider | Consultant, Vendor, Software developer  | Supplier of the  system |
| Deployer | Client, employers  | User of the system |
| Third-party vendor | Camera analytics provider, AI platform provider | May provide surveillance, analytics, scoring, or platform |

<b>Compliance implications:</b>

- Do not deploy the proposed loyalty-scoring system.
- Avoid social scoring or vague behavioural scoring of employees.
- Avoid disproportionate employee surveillance.
- GDPR and employment law concerns are severe.
- If redesigned, use transparent, job-related performance indicators only.
- Ensure human review and employee information.
- Consult legal, HR, worker representatives, and data protection teams before any workplace monitoring.

<b>Decision: Deny and redesign</b>

<b>If denied, lawful redesign option:</b><br />Redesign the system as a transparent performance-support dashboard that uses objective, job-related metrics, such as completed tasks, missed deadlines, customer support tickets, or agreed productivity goals. Do not use cameras, keystroke monitoring, or loyalty scoring. The dashboard should only support managers, not automatically trigger disciplinary reviews. Employees should be informed, data collection should be minimised, and HR should conduct any review with human judgment.
