# Website Product & Design Specification
## Akki AI — Enterprise AI Data Intelligence & Operations

**Document status:** Version 1.0 — discovery and design brief  
**Audience:** Brand/design team, UX/UI designers, content writers, frontend/backend developers, sales and operations stakeholders  
**Repository:** `Alchemist432/Akki-AI-learning`  
**Working branch:** `feature/annotation-website-v1`  
**Current prototype:** `index.html`  
**Important:** “Akki AI” is a working brand name. Confirm the legal/business name, domain, contact details, service readiness, delivery locations, security posture, and all claims before launch.

---

## 1. Executive summary

Build a distinctive, enterprise-grade website for an AI data intelligence and managed data operations company. The business partners with AI/ML teams that need data collected, prepared, annotated, reviewed, evaluated, or transformed into reliable datasets. Projects may be delivered by trained in-house teams, vetted BPO/outsourcing partners, or a controlled hybrid delivery model, depending on project requirements, capacity, risk, language, domain expertise, and client approval.

The website must explain the full journey—not merely list annotation services:
1. A client explains the model/use case, data sources, task, volume, timeline, constraints, and intended output.
2. The company assesses feasibility, data readiness, task complexity, security requirements, and delivery options.
3. Both sides agree on scope, taxonomy/guidelines, acceptance criteria, pilot size, reporting, and delivery format.
4. A representative pilot is annotated and reviewed; disagreements and edge cases are resolved before scale-up.
5. The project is staffed, trained, and executed using approved tools and access controls.
6. Quality is measured throughout production using risk-based checks, reviewer/adjudication loops, defect tracking, and client feedback.
7. Validated outputs, metadata, quality reports, and agreed documentation are delivered through an approved channel.
8. Feedback and error analysis inform the next batch or iteration.

**Core promise:** Make complex AI data work understandable, measurable, and operationally dependable.

**Primary conversion:** “Discuss a project” / “Request a scoped pilot.” The website should attract serious buyers and give them enough detail to start a useful conversation without exposing sensitive datasets through a public form.

## 2. Business and positioning

### 2.1 Category
Enterprise AI data services, data annotation and labeling, data collection and enrichment, human-in-the-loop quality assurance, model evaluation, and managed AI data operations.

### 2.2 Target buyers
- Head/Director of Data Operations or AI Operations
- ML/AI engineering leaders and data science teams
- Product leaders developing computer vision, NLP, LLM, multimodal, speech, or physical AI systems
- Procurement, vendor management, and operations teams sourcing a delivery partner
- Research teams that need a pilot or specialized expert workflow
- Organizations with a large backlog or fluctuating volumes that need flexible delivery capacity

### 2.3 Buyer questions the website must answer
- Do you understand my use case and data types?
- Can you work with our data source, tools, schemas, and existing workflow?
- How do you define “correct” and demonstrate quality?
- How do you handle ambiguous instructions and edge cases?
- Who performs the work—in-house, outsourced, or hybrid—and how is access controlled?
- Can you start with a small pilot and scale only after acceptance?
- What happens to our data, and who can access it?
- How will we track progress, blockers, quality, and delivery?
- What formats and integrations can you support?
- What information do you need from me to estimate scope, cost, and timeline?

### 2.4 Differentiation to communicate
Do not compete on unsupported claims such as “best quality,” “world’s largest workforce,” or unverified accuracy percentages. Differentiate through a visible, practical operating model:
- Discovery and feasibility before committing
- A representative pilot before production scale
- Written annotation instructions and acceptance criteria
- Human review, adjudication, and clear escalation for ambiguous cases
- Transparent project reporting and delivery checkpoints
- Flexible staffing model selected for the project's risk and expertise needs
- Tool-agnostic collaboration where feasible
- Documented handoff: output files, schema/format validation, exceptions, and agreed quality summary
- A feedback loop to improve guidelines and reduce recurring errors

These are proposed capabilities and process commitments; operations leadership must confirm which can actually be delivered before they are stated as guarantees.

## 3. Research and competitive reference

The following public websites were reviewed as directional references. Use them to learn from information architecture, clarity, proof, and service packaging. Do not copy their wording, visual identity, illustrations, page layouts, or proprietary content.

### 3.1 iMerit — https://imerit.ai/
**Observed strengths:** Organizes solutions by AI domain and use case; explains generative AI, mobility, healthcare, robotics, data annotation, tooling, and expert-led workflows; supports claims with case studies and customer proof; connects platform, people, and operations.
**What to learn:** Buyers need use-case relevance, evidence, and an explanation of how expertise and technology work together.
**Opportunity for our website:** Show a simpler, highly visual “from raw data to accepted dataset” workflow, including client inputs, pilot gates, workforce model, QA checkpoints, and deliverables.

### 3.2 TELUS Digital — https://www.telusdigital.com/solutions/data-for-ai-training
**Observed strengths:** Positions services around training and improving AI; connects data collection, annotation, validation, people, platforms, security, and end-to-end delivery; describes different data modalities and flexible program sizes.
**What to learn:** Present the service as a connected data pipeline rather than isolated task types.
**Opportunity for our website:** Explain exactly how a new client project moves from inquiry to pilot, production, quality review, and handover, with no unsupported scale or compliance claims.

### 3.3 Appen — https://www.appen.com/ai-data
**Observed strengths:** Groups offerings around modern AI needs such as model alignment, agentic AI, multimodal data, speech/audio, physical AI, and model evaluation; explains collection and custom/off-the-shelf data options.
**What to learn:** Organize the content around buyer outcomes and model-development needs, not only traditional annotation categories.
**Opportunity for our website:** Make service discovery understandable to both technical and non-technical buyers, with concrete task examples and a “not sure what you need?” path.

### 3.4 iMerit solution overview — https://imerit.ai/solutions/
**Observed strengths:** Service pages are segmented by solution areas such as GenAI, computer vision, NLP, and content services.
**What to learn:** Dedicated pages support search visibility and give complex services room for detailed explanations.
**Opportunity for our website:** Use a scalable service-page template that explains inputs, tasks, workflow, QA, output formats, fit, and questions to scope a project.

### 3.5 Competitive conclusion
The common enterprise pattern is: articulate AI outcomes, show relevant capabilities, connect people + process + tooling, demonstrate quality/security, provide case studies or evidence, and make contacting an expert easy. Our distinctive angle should be **operational transparency**: the website should let a buyer understand what happens to their project at each stage and what decisions or evidence they will receive.

**Research note:** This is a review of publicly accessible marketing pages, not a complete technical audit, customer survey, or proof of competitors’ actual delivery performance. Recheck links and competitor positioning before final publication.

## 4. Brand and visual direction

### 4.1 Desired impression
Sophisticated, credible, technical, calm, human, precise, and operationally mature. The experience should feel custom-designed for enterprise AI buyers—not a generic “AI startup” template.

### 4.2 Current prototype direction
The current `index.html` uses a dark forest-green base, lime accent, Manrope typography, DM Mono metadata, grid lines, and an annotation-scene illustration. Treat this as a starting concept, not a locked design. Evaluate whether the lime accent and dark palette support readability and brand distinction across all pages.

### 4.3 Visual principles
- Strong typography and deliberate whitespace; avoid cramped grids.
- Use real interface concepts and explanatory diagrams rather than decorative AI stock imagery.
- Show the process: dataset intake, task schema, annotation, review, adjudication, validated export.
- Use restrained motion only when it clarifies hierarchy or progress.
- Build responsive layouts from mobile upward; ensure keyboard access and reduced-motion support.
- Avoid fake dashboards with invented metrics presented as real customer results.
- Avoid client logos, certifications, testimonials, customer names, or case studies without written permission and verification.
- Use a consistent icon system and meaningful visual language for data types and workflow stages.

### 4.4 Design system deliverables
Design team should define:
- Color tokens: page background, surface levels, text, muted text, borders, accent, focus, success, warning, error.
- Type scale and typography rules for desktop/tablet/mobile.
- Spacing, grid, container widths, breakpoints, border radii, shadows, and motion.
- Buttons, links, form controls, cards, accordions, tabs, badges, breadcrumbs, and navigation states.
- Data visualizations and workflow diagram conventions.
- Empty, loading, success, validation-error, and server-error states.
- Accessible contrast and focus indicators.
- Image/illustration art direction and responsive crop rules.

## 5. Information architecture and sitemap

### Launch-required pages
1. **Home** — clear positioning, outcomes, services, process, quality, workforce model, CTA.
2. **Services overview** — discover capabilities by task/data type and AI use case.
3. **Service detail pages** (launch with the services that operations can actually deliver):
   - Image and video annotation
   - Text, NLP, and language data
   - LLM / generative AI data and model evaluation
   - Audio and speech data
   - LiDAR, 3D, and spatial data (only if delivery capability is confirmed)
   - Data collection, enrichment, and validation (only if confirmed)
   - Managed annotation operations / QA
4. **How we work** — complete project lifecycle and client responsibilities.
5. **Quality framework** — quality definitions, review model, metrics, edge-case handling, and reporting.
6. **Workforce & delivery model** — in-house, approved BPO partner, hybrid; governance and suitability.
7. **Industries / use cases** — only domains where credible expertise exists.
8. **Security & responsible data handling** — accurate current controls, access model, retention, subprocessors, and escalation contact.
9. **Insights / resources** — educational content and practical guides; no thin filler content.
10. **About** — company story, leadership, delivery philosophy, and verified credentials.
11. **Contact / scope a project** — secure, accessible lead form and clear next steps.
12. **Privacy policy, cookie notice (if applicable), terms, accessibility statement** — reviewed for actual jurisdictions and practices.

### Later-phase pages
- Case studies and client stories (only with approved evidence)
- Technology/platform overview
- Careers / expert network
- FAQ and glossary
- Client portal (separate product and security scope; do not imply one exists unless built)
- Languages/regions if there is a real go-to-market need

### Primary navigation
Services | How We Work | Quality | Industries | About  
Primary CTA: **Discuss a Project**  
Secondary CTA: **Explore Our Process**

Keep navigation short. Put Security in the footer and in contextual links from process and contact pages.

## 6. Homepage requirements and suggested narrative

The homepage should tell a coherent story, not be a sequence of unrelated cards.

### Section 1 — Hero
**Purpose:** In 5–8 seconds, tell a buyer what the company does, who it helps, and what to do next.
**Content direction:** “AI-ready data, delivered with operational discipline.” Alternative: “From raw data to reliable AI training datasets.”
**Supporting message:** We help AI teams plan, annotate, validate, and deliver datasets using managed human expertise, clear workflows, and quality checks.
**CTAs:** “Discuss a Project” and “See How It Works.”
**Visual:** Interactive but lightweight data pipeline or annotation workspace illustration. Clearly label any sample interface as illustrative, not a live product.
**Avoid:** Unverified client logos, fabricated metrics, generic AI promises, or vague statements such as “unlock infinite intelligence.”

### Section 2 — Buyer problem and outcome
Show the real friction points: inconsistent labels, unclear guidelines, edge cases, slow review cycles, fragmented vendors, changing volumes, and difficult handoff. Pair each with a concrete process response. Do not claim guaranteed elimination of these problems.

### Section 3 — Capabilities
Show service families with a concise explanation, representative tasks, supported input types, output examples, and a link to the detail page. Clearly mark capabilities that require confirmation or specialized scoping.

### Section 4 — “From your data to a validated dataset”
Use a visual, numbered pipeline:
1. Define objective and data
2. Assess readiness and constraints
3. Agree taxonomy and guidelines
4. Run a representative pilot
5. Review and approve the pilot
6. Scale with production monitoring
7. Resolve edge cases and defects
8. Validate, package, and deliver
9. Review outcomes and improve
Allow a user to select a stage to reveal: client input, our activity, quality gate, and output.

### Section 5 — Workforce model
Explain the three possible models:
- **In-house delivery:** Suitable when the work requires close operational control, continuity, or specialized internal expertise.
- **Vetted delivery partner/BPO:** Suitable for approved work packages where capacity, language, geography, or operating hours are important, subject to client requirements and governance.
- **Hybrid:** A controlled combination of internal project leadership/QA and partner execution where appropriate.
Show how a model is selected: skill, sensitivity, complexity, language, volume, timeline, location/data residency, client policy, and cost. Do not suggest every project uses every model. Never hide subcontracting if the client contract requires disclosure or approval.

### Section 6 — Quality framework
Show quality as a lifecycle, not a single final inspection:
- Define labels, inclusion/exclusion rules, examples, and acceptance criteria.
- Train and calibrate contributors on a representative sample.
- Use pilot annotations to test instruction clarity and identify ambiguity.
- Apply risk-based review, sampling, double annotation, or adjudication as appropriate to the task.
- Track defect types, disagreements, corrections, and recurring root causes.
- Validate schema, file structure, required fields, and export integrity.
- Share agreed quality reports and obtain client feedback.
Explain metrics only when meaningful and defined. Possible measures: precision/recall or IoU for suitable vision tasks, inter-annotator agreement, adjudication rate, defect rate, rework rate, schema validation pass rate, and on-time delivery. Metric selection depends on task and ground-truth availability. Never promise a fixed accuracy without a scoped methodology and contractual basis.

### Section 7 — Industries and use cases
Use a compact set of confirmed focus areas. Examples to validate with leadership:
- Computer vision and mobility
- Retail/catalog intelligence
- Conversational AI and language models
- Speech and multilingual systems
- Geospatial analysis
- Healthcare or other regulated domains only if specialized expertise and controls exist
Each use-case card should describe the problem and relevant data tasks, not make unsupported domain-performance claims.

### Section 8 — Evidence and credibility
Use a combination of:
- A sample, clearly labeled workflow
- A sample annotation guideline excerpt
- An illustrative quality report with synthetic/demo data clearly marked
- A delivery checklist
- Approved case studies with context, baseline, method, measured result, and permission
- Verified leadership/experience and genuine certifications, where applicable
Until real evidence is available, prioritize transparent process over fake social proof.

### Section 9 — Security and governance
Summarize only verified controls. Link to the detailed page. Explain that project access, data handling, storage, retention, and partner access are agreed during scoping. Do not claim SOC 2, ISO 27001, HIPAA, GDPR compliance, or other certification/attestation unless the organization can substantiate the exact scope and status. Do not imply certification by association with a vendor or tool.

### Section 10 — Final conversion CTA
Headline direction: “Have a dataset or AI workflow to improve?”  
CTA: “Scope a Project.”  
Explain the next step: a discovery conversation, feasibility review, and—if appropriate—a pilot proposal. Avoid promising an instant quote if human scoping is required.

## 7. End-to-end client workflow: functional and content specification

### Stage 1 — Project discovery
**Client provides:** business/model objective, data type, approximate volume, desired labels/evaluation task, current workflow/tool, timeline, languages/domains, output schema, target quality criteria, sensitive-data constraints, and known edge cases.
**Our team does:** clarify the goal, assess fit, identify unknowns, discuss risks and dependencies, and determine whether collection, preparation, annotation, review, or evaluation is needed.
**Output:** discovery summary and list of open questions; no commitment before feasibility is checked.

### Stage 2 — Data source and readiness assessment
The site must explain that client data may come from different approved sources. Examples:
- Secure client upload or managed file transfer
- Client-controlled cloud storage or bucket, where integration is agreed
- Client API or database export, where supported
- Existing annotation/labeling platform export
- Approved data collection plan when data does not yet exist
- A small, non-sensitive sample for feasibility, if permitted
The exact methods depend on architecture, permissions, size, formats, and contract. The public marketing site must not accept confidential files or credentials. Use a secure channel only after scope and access controls are agreed.

**Readiness checks:** file types and schema; sample completeness; data volume; corrupt/duplicate records; language/modality; label availability; class imbalance; privacy/consent/licensing/provenance where relevant; metadata; access rights; storage/region requirements; and whether the data can lawfully be processed for the stated purpose.
**Output:** readiness findings, risks, prerequisites, and recommended delivery plan.

### Stage 3 — Scope, taxonomy, and annotation design
Agree:
- Objective and intended downstream use
- Task definitions, label taxonomy, ontology, and hierarchy
- Positive/negative examples, exclusions, and ambiguous/edge-case rules
- Annotation tool and workflow, including client-owned tooling if supported
- Annotation instructions, versioning, and change control
- Required output schema and sample export
- Roles and responsibilities
- Pilot size, timeline, acceptance criteria, review method, reporting cadence, and escalation path
- Security, access, retention, partner, and data-transfer conditions
**Output:** approved project brief, annotation guidelines, acceptance plan, and pilot proposal.

### Stage 4 — Pilot and calibration
Start with a representative sample, not an arbitrary sample that hides difficult cases. Include normal cases and likely edge cases.
- Train a small, suitable group.
- Collect annotations and reviewer feedback.
- Measure agreed task-appropriate quality indicators.
- Record disagreements, unclear instructions, missing labels, and tooling friction.
- Hold calibration/adjudication with the client when necessary.
- Revise the guidelines and repeat a pilot slice if needed.
- Obtain explicit acceptance of the pilot or document the remaining issues.
**Gate:** Do not scale production until the agreed pilot acceptance conditions are met or an authorized exception is documented.

### Stage 5 — Staffing and controlled production setup
Choose in-house, approved partner, or hybrid delivery according to project requirements. Define roles such as project/delivery manager, subject-matter lead, annotator, reviewer/QA, adjudicator, and technical/tooling support as applicable.
- Verify required skills and language/domain fit.
- Provide project-specific training and qualification.
- Limit access to approved people and required data.
- Use approved tools, workspaces, and communication channels.
- Set throughput expectations based on pilot evidence.
- Establish backup, continuity, and escalation plans where appropriate.
**Output:** production readiness checklist and approved team/workflow.

### Stage 6 — Production and monitoring
Show how ongoing work is managed:
- Work batches, assignment, status, and due dates
- Progress and volume reporting
- QA sampling/review according to risk and agreed plan
- Defect categories, rework, and root-cause tracking
- Edge-case queue and adjudication
- Client questions and guideline change requests
- Change log and versioned instructions
- Early warning when quality, data readiness, capacity, or timeline deviates
**Output:** agreed progress updates and issue/escalation visibility. Do not imply that a live client dashboard exists unless it is implemented.

### Stage 7 — Final validation and delivery
Validate according to contract and agreed specification:
- Required fields, schema, data types, and output format
- Completeness and expected record counts where applicable
- Label/value validity and internal consistency
- Agreed QA acceptance criteria and unresolved exception list
- File integrity, naming, versioning, and delivery manifest
- Required metadata and annotation guideline version
- Quality summary and known limitations
**Output:** deliverables through an agreed secure channel, a delivery manifest, quality summary, and documented exceptions/acceptance. Formats may include JSON/JSONL, CSV, XML, COCO, YOLO, or tool-specific formats only where the team can support them.

### Stage 8 — Feedback and iteration
Review client feedback, model performance signals when supplied, disputed examples, recurring defects, and changing requirements. Agree whether to update guidelines, retrain, relabel a batch, expand the taxonomy, or start another iteration. Document scope and cost/time impact for changes.

## 8. Service-page template

Every service detail page should include:
1. Plain-language definition and the AI outcome it supports.
2. Who typically needs the service.
3. Data inputs and representative task types.
4. What the client provides.
5. What the team does.
6. Example of the annotation/review workflow.
7. Quality approach and relevant metrics (task-dependent).
8. Example output schema or deliverable, using synthetic data.
9. Supported tools/formats/integrations, only if verified.
10. Typical project variables that affect scope, cost, and timeline.
11. Security considerations relevant to the data type.
12. FAQs and common edge cases.
13. CTA to scope a project.
14. Links to related services and the quality/process pages.

### Initial service taxonomy (confirm actual delivery readiness)
- **Image/video:** classification, bounding boxes, polygons, segmentation, keypoints, tracking, frame-level labels, video event/action labels.
- **Text/NLP:** classification, named entity recognition, intent, sentiment, entity linking, document tagging, linguistic review, transcription validation.
- **LLM/GenAI:** response evaluation, preference ranking, rubric-based assessment, supervised examples, safety evaluation, red-team tasks, expert review. Chain-of-thought or sensitive reasoning data must only be handled when legally, contractually, and operationally appropriate; do not imply access to private model reasoning.
- **Audio/speech:** transcription, diarization, speaker attributes where permitted, language/dialect tags, acoustic event labels, speech quality review.
- **3D/spatial:** point clouds, cuboids, tracking, sensor fusion, spatial labeling—only with appropriate expertise and tools.
- **Data operations:** collection, cleaning, deduplication, normalization, validation, data enrichment, project management, and QA—only as confirmed capabilities.

## 9. Workforce, outsourcing, and governance page

The website must be clear that the business can organize delivery through in-house personnel, external BPO partners, or a hybrid model. Explain the controls and decision logic rather than using “large workforce” as a vague selling point.

Include:
- What determines the delivery model: skill, task complexity, data sensitivity, geography/language, volume, time zone, client policy, budget, and timeline.
- Who owns client communication and delivery accountability.
- How annotators/reviewers are trained and calibrated.
- How project access is approved and revoked.
- How partner access is disclosed and authorized when required.
- How instructions, review standards, and escalation rules remain consistent across teams.
- How partner performance is assessed and how issues are corrected.
- How work is reassigned or contained if a team fails to meet requirements.
- How confidentiality, contractual obligations, data transfer, and retention are handled.
- Which details are confirmed at proposal stage rather than assumed on the website.

Do not state that every BPO partner is certified, audited, or approved unless records support the claim. The client should not be surprised by subcontracting arrangements.

## 10. Quality framework page

### Quality principles
- Define correctness before production.
- Match review effort to error impact and task complexity.
- Test instructions on representative and difficult examples.
- Use human review where it adds value; automation can assist but should not be presented as infallible.
- Record and resolve disagreements rather than silently choosing labels.
- Use recurring errors to improve instructions and training.
- Validate output structure separately from semantic annotation quality.
- Make exceptions and limitations visible to the client.

### Candidate metrics (select per task)
- Agreement between annotators or reviewers
- Precision/recall, IoU, or other task-specific measures where ground truth and definitions support them
- Reviewer rejection/defect rate
- Rework rate
- Adjudication and escalation rate
- Schema/format validation pass rate
- Completeness and coverage
- Throughput and cycle time
- On-time delivery
- Defect recurrence after guideline updates

Explain metric definitions, denominator, sample, and measurement window. Never display illustrative values as company performance. Demo data must be labeled “illustrative.”

### Sample quality report
Provide a downloadable or interactive example using fictional data. Include project/batch ID, guideline version, sample size, reviewed count, issue categories, severity, correction status, exceptions, and next actions. Label it as a sample—not a real client result.

## 11. Security, privacy, and responsible handling

This page must be reviewed by the business/legal/security owner before publication. It must describe the current, provable state, not an aspirational roadmap as if it were already live.

Cover, where applicable and verified:
- Data ownership and permitted use
- Approved transfer mechanisms and storage locations
- Access control and least-privilege principles
- Identity, device, and workspace controls
- Confidentiality and staff/partner obligations
- Subprocessor/partner disclosure and client approval requirements
- Encryption in transit/at rest if actually implemented
- Retention and secure deletion process
- Incident reporting and escalation process
- Data residency and cross-border transfer considerations
- Personal, sensitive, regulated, or licensed data restrictions
- Use of third-party AI tools and whether client data may be used to train models
- Security questionnaire and DPA/NDA process where applicable

**Prohibited without evidence:** claims of SOC 2, ISO 27001, HIPAA compliance, GDPR compliance, TISAX, “military-grade security,” “zero risk,” or any certification/attestation that has not been verified for the exact legal entity and scope. Use precise wording and obtain legal review.

## 12. Lead-generation and project-scoping experience

### 12.1 Form goals
Capture enough information to route and qualify an inquiry without overwhelming the visitor or requesting confidential data too early.

### 12.2 Suggested form fields
**Required:** name, work email, company, project summary, desired service/data type, and consent/privacy acknowledgement where legally required.
**Optional:** role, approximate data volume range, target timeline, preferred contact method, current tool/platform, input formats, languages, output format, sensitive-data constraints, and “other / not sure yet.”
Use progressive disclosure: reveal additional questions based on selected service. Provide “I’m not sure yet” options.

### 12.3 Do not collect in the public form
- Passwords, API keys, access tokens, credentials
- Confidential production datasets
- Personal or sensitive data samples
- Unnecessary identity documents
Provide instructions to share sample data through an approved secure channel after initial triage.

### 12.4 Form behavior
- Clear field labels and inline validation
- Accessible error summary and focus management
- Server-side validation and spam/rate-limit protection
- Success state with clear next steps
- Failure state that preserves safely entered information where possible
- Privacy notice and consent handling appropriate to jurisdiction
- Confirmation email only after a working email service is configured
- CRM integration only after credentials, permissions, and privacy requirements are approved
- Analytics events should not contain form text, emails, or confidential project details

### 12.5 Lead routing
Route by service type, language/domain, expected volume, urgency, security requirements, and geography if operationally supported. Establish an internal owner and response SLA before promising one publicly.

## 13. Interactive experiences

Build interactions that help a buyer understand the operation—not motion for motion’s sake.

### Priority A
1. **Clickable workflow explorer:** each stage shows client input, team action, quality gate, and output.
2. **Project scope wizard:** asks a few non-sensitive questions and produces a project brief summary for the contact team; it should not fabricate a quote or guarantee feasibility.
3. **Quality loop diagram:** illustrates annotation → review → disagreement resolution → guideline improvement.
4. **Delivery model comparison:** in-house / approved partner / hybrid with suitability factors and governance notes.
5. **Service explorer:** filter by data type, AI use case, and task.
6. **Illustrative annotation viewer:** switch between raw sample, annotation overlay, reviewer correction, and final structured output using synthetic/demo data.

### Priority B
- Sample quality report explorer
- FAQ accordion and searchable glossary
- Downloadable project brief checklist
- Case study filters once approved stories exist
- Optional language/region selector if there is a genuine localization plan

### Interaction requirements
- Every interactive element must work on keyboard, touch, and screen reader where appropriate.
- Add focus states, loading, empty, error, and success states.
- Honor reduced-motion preferences.
- Avoid autoplay video and heavy effects that harm performance.
- Ensure content remains understandable when animation is disabled.

## 14. Content tone and copy rules

### Voice
Direct, precise, confident, technically literate, and human. Explain jargon in context. Speak to enterprise buyers as partners; avoid hype.

### Good content pattern
**Claim → how it works → evidence/qualification → next step.**

Example:
“We design annotation workflows around your model objective and acceptance criteria. We start with a representative pilot, review ambiguous cases, and agree the production quality plan before scaling.”

### Avoid
- “Best in the world,” “100% accurate,” “guaranteed perfect,” “infinite scale,” “instant results”
- Unverified volume, headcount, country, language, customer, revenue, or accuracy statistics
- Fake testimonials, client logos, or fabricated case studies
- Generic AI buzzword walls
- Overpromising tool integrations or delivery formats
- Claiming a client portal or real-time dashboard exists before it does
- Treating all data types or regulated domains as interchangeable

### Evidence hierarchy
1. Verified customer-approved case studies and measured outcomes
2. Verified credentials and documented operating controls
3. Demonstrable sample workflow and synthetic examples
4. Clear descriptions of proposed process
5. Aspirational statements (avoid presenting these as current capabilities)

## 15. Technical and non-functional requirements

### Architecture
The existing prototype is a single HTML file with embedded CSS and JavaScript. The team should first decide whether to retain a lightweight static site or migrate to a maintainable framework based on expected page count, CMS needs, deployment target, integrations, and team skills. Do not introduce a framework just for fashion.

### Requirements
- Responsive, mobile-first implementation
- Semantic HTML and accessible navigation/forms
- WCAG 2.2 AA as the design target, including contrast, keyboard, focus, labels, and error handling
- SEO-friendly page titles, meta descriptions, canonical URLs, Open Graph metadata, sitemap, robots policy, and structured data only where accurate
- Good Core Web Vitals; compress and size images, minimize JavaScript, lazy-load below-the-fold media, avoid layout shifts
- Progressive enhancement and graceful behavior if animation or JavaScript fails
- Secure headers and deployment configuration appropriate to the hosting platform
- HTTPS and a real custom domain before production
- Environment-specific configuration for analytics, CRM, and form handling; no secrets in frontend code or repository
- Basic automated checks for links, HTML, accessibility, responsiveness, and form validation
- Analytics that measure conversion without collecting sensitive information
- Content management approach documented if non-developers need to edit pages
- Privacy/cookie behavior configured only as required by the actual analytics, tools, and jurisdictions

### Accessibility and responsive checks
Test keyboard-only navigation, visible focus, mobile menu state, headings, form errors, contrast, zoom/reflow, reduced motion, screen-reader labels, and touch target sizes. Do not rely on color alone to convey status.

## 16. SEO and content strategy

Create distinct pages for buyer-intent searches rather than repeating the same keyword on every page. Potential topic clusters:
- AI data annotation services
- Image and video annotation
- LLM data annotation and model evaluation
- Text/NLP annotation
- Audio and speech annotation
- LiDAR and 3D point cloud annotation (if supported)
- Data quality assurance for AI training data
- Managed annotation operations
- Human-in-the-loop AI data workflows
- AI training data quality and annotation guidelines

Publish practical, original resources such as:
- “What to include in an annotation project brief”
- “How to design annotation guidelines for edge cases”
- “How to run a useful annotation pilot”
- “Choosing quality metrics for different annotation tasks”
- “What a delivery manifest and quality report should contain”
- “Questions to ask an AI data annotation partner”

Every article should provide real guidance and be reviewed by a qualified person. Do not generate thin pages solely to target keywords.

## 17. Analytics and success measures

Track meaningful website outcomes:
- Qualified project inquiries
- Form start and completion rates
- CTA clicks by page
- Service-page engagement
- Workflow explorer engagement
- Project scope wizard completion
- Resource downloads
- Mobile vs desktop conversion
- Referral source and campaign where consent/privacy rules allow

Define a qualified lead with sales/operations. Do not optimize only for traffic or clicks. Do not capture raw form content or sensitive data in analytics. Establish baseline metrics after launch before setting numerical targets.

## 18. Launch scope and prioritization

### Phase 0 — Confirm fundamentals
- Confirm brand/legal name, domain, contact email, and target markets.
- Confirm the service catalogue and delivery readiness for each service.
- Confirm staffing and partner governance model.
- Confirm quality methods and what can be promised.
- Confirm actual security, privacy, data transfer, retention, and compliance posture.
- Gather approved proof, or decide to launch without customer logos/case studies.
- Decide hosting, form destination, analytics, and CMS needs.

### Phase 1 — High-quality launch
- Home
- Services overview
- 3–4 service pages for confirmed capabilities
- How we work
- Quality framework
- Workforce/delivery model
- Security and responsible handling
- About
- Contact/project scope form
- Privacy/terms/accessibility essentials as applicable
- Working responsive navigation, interactions, analytics, SEO metadata, and error states

### Phase 2 — Evidence and deeper engagement
- Case studies and approved testimonials
- Interactive quality report and sample dataset examples
- Resource center
- More service pages and industry pages
- CRM and operational lead routing
- Optional localization

### Phase 3 — Productized client experience
Only if approved as a separate product scope:
- Authenticated client portal
- Secure dataset intake
- Project status and batch tracking
- Guideline versioning and approvals
- Deliverable downloads and audit history
- Role-based access and security testing

A public marketing site is not a secure data-transfer platform. Do not build or imply a client portal in Phase 1.

## 19. Deliverables expected from the design team

1. Discovery summary and unresolved business questions
2. Sitemap and navigation model
3. Buyer personas and key user journeys
4. Competitive reference/mood board with original design direction
5. Brand and design system
6. Low-fidelity wireframes for desktop and mobile
7. High-fidelity responsive designs for all Phase 1 pages
8. Homepage visual prototype and interactive states
9. Workflow diagram and service visual system
10. Form field map, validation/error/success states, and data-handling notes
11. Content outline and copy deck with claims requiring business approval clearly flagged
12. Accessibility annotations and responsive behavior
13. Asset list with license/source records
14. Developer handoff: components, spacing/tokens, breakpoints, interaction specs, and acceptance criteria
15. QA checklist and cross-browser/device test plan

## 20. Acceptance criteria

The website is ready for stakeholder review only when:
- A new enterprise visitor can identify the offering, target audience, and next action within the first screen.
- The website explains how a project moves from data source/discovery to pilot, production, QA, and delivery.
- It clearly explains in-house, partner/BPO, and hybrid delivery without obscuring outsourcing or overstating controls.
- Each launch service page identifies inputs, tasks, workflow, QA approach, outputs, and scoping variables.
- A buyer can understand what information to provide without uploading confidential data publicly.
- The contact form validates input, displays accessible errors and success/failure states, and sends submissions to an approved destination.
- Every CTA and navigation link works; there are no placeholder emails, dead links, fake dashboard controls, or misleading live-product claims.
- All metrics, logos, testimonials, certifications, and customer examples are verified or clearly marked as illustrative.
- Security and compliance copy is reviewed and accurate for the actual organization.
- Pages are responsive and pass agreed accessibility, browser, performance, and SEO checks.
- Analytics are configured with privacy safeguards and do not capture sensitive project details.
- The team has reviewed the experience using representative enterprise-buyer scenarios.

## 21. Questions the business owner must resolve

These are decisions, not assumptions for the design team to invent:
1. Is “Akki AI” the final public brand, and what legal entity will contract with clients?
2. Which services can be delivered today versus later?
3. Which industries/domains can the team credibly support?
4. What is the initial geographic market and working language set?
5. Will delivery be in-house, BPO, or hybrid—and what partner disclosures/approvals are required?
6. Which annotation tools/platforms are available, and can client-owned tools be used?
7. Which data sources, formats, and transfer methods can actually be supported?
8. What are the current security controls, certifications, retention policies, and approved hosting locations?
9. Who owns sales inquiries and what response time can be met?
10. Which evidence can be published: prior work, case studies, testimonials, team experience, client names, metrics?
11. What are the likely project sizes and commercial model (fixed scope, per-unit, time/materials, pilot)?
12. Where should the lead form submit, and which CRM/email system is approved?
13. What hosting, domain, CMS, analytics, and privacy/cookie requirements apply?
14. Is a client portal part of this website project or a future, separately scoped product?

## 22. Recommended next step

Before polishing every page, the business owner and design lead should hold a short discovery workshop to answer Section 21 and mark each proposed capability as:
- **Available now**
- **Available after scoping**
- **Roadmap / not yet available**
- **Not offered**

Then create the sitemap and homepage wireframe around verified capabilities. Build the homepage and one representative service page first, review them against the acceptance criteria, and only then extend the design system across the rest of the site.

---

## Reference links
- iMerit — https://imerit.ai/
- iMerit solutions — https://imerit.ai/solutions/
- TELUS Digital, Data for AI Training — https://www.telusdigital.com/solutions/data-for-ai-training
- TELUS Digital, Data Annotation Services — https://www.telusdigital.com/solutions/data-for-ai-training/data-annotation-services
- Appen, AI Data — https://www.appen.com/ai-data

*This specification is an original product/design brief informed by publicly visible competitor positioning. It is not legal advice, a security certification, or a claim that every listed service/control is already available. Business, security, legal, and operations owners must approve public claims before launch.*
