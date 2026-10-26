# Enterprise AI Data Intelligence Website — Product & Design Specification

**Document status:** Design-team handoff draft  
**Version:** 1.0  
**Working brand:** Akki AI (provisional; confirm final business name before public launch)  
**Website type:** Enterprise B2B marketing, education, and lead generation  
**Primary audience:** AI/ML companies, model developers, enterprise AI teams, data science leaders, and procurement/security stakeholders  
**Repository:** `Alchemist432/Akki-AI-learning`  
**Implementation branch:** `feature/annotation-website-v1`  
**Current prototype:** `index.html`

---

## 1. Executive summary

Build a distinctive, enterprise-grade website for an AI data intelligence and managed data operations company. The company helps AI teams turn raw or weakly structured data into carefully annotated, validated, evaluated, and delivery-ready datasets. Work may be delivered by a trained in-house workforce, approved business process outsourcing (BPO) partners, or a hybrid model, depending on project requirements.

The website must make the service tangible. Prospective clients should be able to understand:

1. What data work the company can take on.
2. How a project moves from initial conversation to accepted delivery.
3. How the team learns a client's taxonomy, guidelines, edge cases, and quality expectations.
4. How annotators, team leads, QA reviewers, subject-matter experts, and project managers work together.
5. How in-house and BPO delivery can be governed under one operating model.
6. How data access, confidentiality, security, and partner access will be controlled.
7. What the client receives, how quality is measured, and how exceptions are resolved.
8. How to submit a project brief and start a low-risk pilot.

This is **not** a self-service annotation SaaS product at launch. The primary business model is a managed service: the client provides a project and data or approved access to data; the company scopes the work, assembles the delivery model, performs annotation and quality control, and delivers outputs to the client's agreed specifications. Do not imply a functioning customer portal, proprietary annotation platform, automated data ingestion, or integrations unless those are actually available.

### Strategic proposition

**Working message:** Human expertise, structured operations, and measurable quality for AI-ready data.

The brand should feel like a capable operational partner to technical AI teams—not a generic outsourcing agency and not an unproven AI software product.

### Primary conversion

Get a qualified AI data project inquiry, with enough information to understand the data modality, scope, quality requirements, volume, timeline, and security constraints.

### Secondary conversions

- Request a discovery call.
- Request a pilot or sample-work discussion.
- Download a future capability statement (only when approved and fact-checked).
- Explore service, quality, delivery, and security information.
- Ask a technical or procurement question.

---

## 2. Competitive research and design principles

The following public company websites were reviewed for patterns and ideas. The purpose is to learn from their information architecture, service framing, trust-building, and workflow explanations—not to reproduce their copy, visual identity, proprietary diagrams, or branded terminology.

### Reference set

- **Sama** — https://www.sama.com/ and https://www.sama.com/data-annotation-solution  
  Useful patterns: outcomes-led positioning, human-verified data, dedicated service descriptions, explicit annotation strategy, guideline development, calibration, and case-study storytelling.
- **TELUS Digital AI** — https://www.telusdigital.com/solutions/data-for-ai-training/data-annotation-services  
  Useful patterns: broad data modalities, flexible workforce models, AI-assisted workflows, security messaging, end-to-end service coverage, and explanations of human-in-the-loop review.
- **Scale AI** — https://scale.com/data-engine and https://scale.com/blog/data-quality  
  Useful patterns: connect data quality to model outcomes; distinguish task-level, dataset-level, and contributor-level quality; cover generation, annotation, evaluation, and iterative improvement.
- **iMerit** — https://imerit.ai/  
  Useful patterns: connect domain expertise, managed workforce, annotation tools, complex modalities, GenAI work, and case studies into one coherent story.
- **Invisible Technologies** — https://invisibletech.ai/data-lab  
  Useful patterns: position data work as an operational partner across annotation, training, and evaluation; make the relationship to model-building workflows clear.
- **Labelbox** — https://labelbox.com/ and https://docs.labelbox.com/docs  
  Useful patterns: connect data, experts, evaluation, workflow tooling, and customer outcomes. The website's current broader product direction is not a template to copy; take only the principle of explaining the end-to-end job.
- **CloudFactory** — https://www.cloudfactory.com/  
  Useful patterns: translate operational complexity into outcomes such as reliable data, validation, oversight, and scalable delivery.

### What to adopt

1. **Outcome before jargon.** Start with the client's problem and the result they need. Then explain task types and technical details.
2. **Make the workflow visible.** Clients should see the path from discovery to pilot, calibration, production, QA, delivery, and iteration.
3. **Treat quality as a system.** Explain guidelines, qualification, calibration, review, adjudication, sampling, error analysis, and acceptance criteria.
4. **Show people and operations.** Make clear who is doing the work, who reviews it, who resolves ambiguity, and who is accountable to the client.
5. **Explain flexible scale honestly.** In-house and approved BPO delivery can support capacity needs, but only with consistent training, access control, QA, and accountability.
6. **Build trust through evidence.** Use real process diagrams, sample deliverables, approved case studies, actual policies, and verified credentials—not invented metrics.
7. **Give buyers useful detail.** Technical users need modality, output formats, edge cases, and quality definitions; procurement needs scope, delivery model, security, and commercial next steps.
8. **Use strong, specific calls to action.** “Discuss your dataset” or “Scope a pilot” is more informative than “Learn more” everywhere.

### What not to copy

- Competitor slogans, distinctive phrasing, page copy, graphics, iconography, layouts, diagrams, or brand colors.
- Competitor statistics, client logos, certifications, case-study outcomes, or workforce claims.
- Claims such as 99% accuracy, billions of labels, global workforce size, named customers, or security certifications without substantiated evidence belonging to this company.
- A fake platform interface presented as an actual product.
- Generic AI imagery that doesn't help explain data work.

The final site should have its own information architecture, copy, examples, visual system, and brand personality. Treat competitive sites as research references, not templates.

---

## 3. Business positioning and audience

### 3.1 Positioning statement

Akki AI (working name) is a managed AI data services partner that helps AI teams prepare, annotate, validate, and evaluate datasets through trained people, clear workflows, and quality processes tailored to the client's use case.

### 3.2 Value proposition pillars

- **Clear scope:** shared definitions, taxonomy, annotation guidelines, edge-case rules, and acceptance criteria.
- **Human expertise:** trained annotators, reviewers, team leads, and specialists matched to task complexity.
- **Operational control:** project management, progress visibility, issue escalation, and documented delivery.
- **Quality throughout:** calibration before scale, layered checks during production, and evidence-based acceptance.
- **Flexible delivery:** in-house, approved BPO partner, or hybrid model when suitable and contractually approved.
- **Client ownership and collaboration:** agreed deliverables, review cycles, feedback incorporation, and clear data handling expectations.

Do not claim the company already possesses all of these capabilities at scale. Treat them as target operating principles; the business owner must confirm what can be operationally delivered before the site is published.

### 3.3 Primary buyer personas

**Persona A — Head of AI / ML Engineering**
- Wants training or evaluation data that improves a model or supports a specific experiment.
- Needs technical fit, dataset consistency, edge-case handling, predictable delivery, and feedback loops.
- Primary content: service capabilities, workflow, output examples, quality model, pilot CTA.

**Persona B — Data Operations / Data Science Lead**
- Owns a backlog of labeling, review, or evaluation work.
- Needs throughput planning, instructions, reviewer coverage, error reporting, and reliable handoffs.
- Primary content: delivery process, QA, reporting, workforce model, sample deliverables.

**Persona C — Procurement / Vendor Management**
- Needs a credible vendor, clear scope, staffing model, commercial process, contractual boundaries, and evidence.
- Primary content: engagement models, project governance, security questionnaire contact, terms for BPO/subcontractor disclosure.

**Persona D — Security / Legal / Privacy**
- Needs to understand where data goes, who can access it, retention/deletion, subcontractor access, incident escalation, and applicable contractual safeguards.
- Primary content: security and responsible data handling. Never promise certifications or legal compliance that are not verified.

**Persona E — Startup Founder / Product Lead**
- Needs an approachable partner to test feasibility, run a pilot, and scale if successful.
- Primary content: simple service explanations, pilot process, required inputs, CTA.

### 3.4 Likely client objections the website must answer

- “Will you understand our use case and annotation taxonomy?”
- “How do you know whether a label is correct?”
- “What happens when annotators disagree?”
- “Can you work with our tools and export formats?”
- “Can you scale without quality collapsing?”
- “Will our data be handled by third-party BPO staff?”
- “Who owns the labeled data and derived deliverables?”
- “How will we see progress and resolve blockers?”
- “Can we begin with a small pilot before committing to volume?”
- “What exactly do we receive at the end?”

Each objection should be answered somewhere in the site—not only through a sales call.

---

## 4. Website objectives and success criteria

### Business objectives
1. Generate qualified project inquiries.
2. Establish credibility with technical and enterprise buyers.
3. Explain managed annotation and AI data operations without requiring a sales call to understand the basics.
4. Reduce repetitive pre-sales explanations through useful process and quality content.
5. Make the company’s in-house / BPO / hybrid delivery model clear and responsibly governed.
6. Provide a scalable structure for adding services, case studies, industries, resources, and recruiting content later.

### User objectives
- Identify whether the company supports their modality and task.
- Understand the engagement process, quality controls, and delivery options.
- Evaluate fit before sharing sensitive project details.
- Request a consultation or pilot discussion easily.

### Initial measurable website metrics
Instrument these once analytics and consent requirements are agreed:
- Qualified inquiry submissions.
- Inquiry conversion rate by landing page and CTA.
- Contact form completion and abandonment.
- Clicks on email / booking CTA.
- Visits to service, quality, delivery model, and security pages.
- Organic traffic to service pages.
- Qualified lead rate (measured in the CRM or sales process, not inferred from page views alone).

Do not set arbitrary conversion targets until traffic, analytics, and the sales baseline exist.

---

## 5. Sitemap and page requirements

### Launch sitemap

1. Home
2. Services overview
   - Image and video annotation
   - Text, NLP, and document annotation
   - LLM data, human feedback, and model evaluation
   - Audio and speech data (only if deliverable)
   - 3D / LiDAR / sensor data (only if deliverable)
   - Data validation and QA
   - Managed data operations
3. How We Work
4. Quality Framework
5. Delivery Model: In-house, BPO, and Hybrid
6. Industries / Use Cases
7. Security and Responsible Data Handling
8. About Us
9. Contact / Scope a Project
10. Privacy Policy and Terms (legal review required)

### Phase 2 pages (after capabilities and evidence are ready)
- Case studies / customer stories.
- Resources / guides.
- Careers / contributor recruitment.
- Downloadable capability statement.
- A client portal only if a real portal is built and secured.

Navigation should stay focused. Do not place every service as a top-level nav item; use a Services menu or grouped page.

---

## 6. Detailed page specifications

## 6.1 Home page

**Goal:** Communicate what the business does, why it matters, how delivery works, and how to start a project within the first screen and first few scrolls.

### Required section order

1. **Navigation**
   - Brand mark and wordmark.
   - Services, How We Work, Quality, Delivery Model, About.
   - Primary CTA: “Discuss a project” or “Scope a pilot.”
   - Mobile menu with accessible open/close state.

2. **Hero**
   - Outcome-led headline, e.g. “High-quality data for teams building AI.”
   - Supporting copy: managed annotation, validation, and model data operations with trained human teams and structured QA.
   - Primary CTA: “Discuss your dataset.”
   - Secondary CTA: “See how we work.”
   - Distinctive visual showing data moving through annotation, review, and structured output—not generic glowing brain artwork.
   - Avoid unsupported performance statistics.

3. **Capability summary**
   - 4–6 core service categories.
   - Each links to a meaningful detail page.
   - Use language a technical buyer recognizes.

4. **The data challenge**
   - Raw data can be inconsistent, ambiguous, imbalanced, incomplete, or difficult to label consistently.
   - Explain why guidelines, review, and exception handling matter.
   - Do not imply every client has every problem.

5. **End-to-end workflow**
   - Discover → Define → Pilot → Calibrate → Produce → Validate → Deliver → Improve.
   - Show client touchpoints and approval gates.
   - Link to the full process page.

6. **How quality is engineered**
   - Guideline development.
   - Annotator qualification and project training.
   - Calibration / gold tasks.
   - In-task checks and reviewer sampling.
   - Adjudication and edge-case escalation.
   - Dataset-level checks and acceptance reporting.
   - Explain that metrics and thresholds are agreed per project.

7. **Flexible delivery model**
   - In-house team, approved BPO partners, hybrid.
   - One delivery owner and common SOPs / QA framework.
   - Clearly state that third-party delivery is disclosed and governed under the agreed contract.
   - Do not hide subcontracting or imply all work is done in-house if that is not true.

8. **Use cases / industries**
   - Choose only those the company can actually support.
   - Potential examples: computer vision, mobility, retail/catalog, geospatial, conversational AI, document intelligence.
   - Healthcare, financial, safety-critical, or regulated work requires validated capability and appropriate safeguards before being advertised.

9. **Proof / evidence**
   - Launch with process evidence: anonymized sample workflow, sample output schema, example QA report, or a clearly labeled illustrative project.
   - Later replace/add verified case studies, client testimonials, logos, and approved outcome metrics.
   - Never fabricate proof.

10. **Security and responsible handling**
    - Short summary linking to a detailed page.
    - Explain access restrictions, approved environments, data minimization, retention, deletion, and partner controls only to the extent the company actually implements them.

11. **Final CTA**
    - “Tell us about your data project.”
    - State what happens next: discovery conversation, scope review, and possible pilot proposal.
    - Do not promise response times unless operationally agreed.

## 6.2 Services overview

**Goal:** Help clients map their problem to the correct service and understand what inputs and outputs to expect.

Every service page must use a consistent structure:
- Client problem / intended outcome.
- What the service includes.
- Supported task types and data modalities.
- Example use cases.
- Typical input data.
- Typical output / deliverables.
- Workflow and human review.
- Quality considerations and common edge cases.
- What the client needs to provide.
- Relevant integrations / formats only if confirmed.
- FAQ.
- CTA to discuss a project.

### Service definitions

**Image and video annotation**
- Possible tasks: image classification, object detection, bounding boxes, polygons, semantic / instance segmentation, keypoints, tracking, video event labels.
- Input examples: images, video, class taxonomy, object definitions, edge-case rules.
- Outputs: agreed schema and formats, annotation exports, QA report, exception log.
- Must confirm tooling, file formats, video frame policies, and available expertise before launch.

**Text, NLP, and document annotation**
- Possible tasks: named entity recognition, text classification, intent, sentiment, document classification, extraction, transcription review.
- Outputs: labeled records, schema validation, guideline decisions, exception log.
- Do not advertise language coverage until confirmed.

**LLM data and model evaluation**
- Possible tasks: response rating, preference comparisons, rubric-based evaluation, instruction-following evaluation, factuality checks, safety/policy evaluations, supervised fine-tuning data creation, red-team tasks where appropriate.
- Must document rubrics, evaluator qualifications, disagreement handling, and escalation.
- Avoid implying the business can perform advanced reasoning or specialist-domain evaluation without qualified reviewers.

**Audio and speech data (conditional)**
- Possible tasks: transcription, diarization, speech classification, audio event labeling, quality review.
- Confirm language/dialect coverage, audio tooling, consent and privacy requirements.

**3D / LiDAR / sensor data (conditional)**
- Possible tasks: point-cloud segmentation, 3D boxes, tracking, sensor-fusion labels.
- Only publish if actual trained staff, tooling, and delivery capability are available.

**Data QA and validation**
- Annotation guideline conformance.
- Schema and format validation.
- Sampling-based or full review as agreed.
- Inter-annotator agreement / disagreement analysis where suitable.
- Defect categorization, corrective action, and rework.
- Dataset-level checks such as duplication, missing fields, class distribution, and coverage where relevant.
- Never represent a sample-based QA plan as a 100% review.

**Managed data operations**
- Project setup, work breakdown, staffing plan, training, throughput monitoring, issue management, change control, status reports, and delivery coordination.
- Clarify the boundary between managed services and software products.

## 6.3 How We Work page

**Goal:** Make the engagement lifecycle concrete, predictable, and collaborative.

### Stage 1 — Discovery and feasibility
**Client provides:** use case, data modality, approximate volume, intended model/task, target date, known constraints, security requirements.  
**Company does:** assess fit, clarify ambiguity, identify risks, discuss staffing and tools, identify missing inputs.  
**Gate:** agree whether to proceed to detailed scoping.

### Stage 2 — Scope and solution design
**Company defines:** work breakdown, label taxonomy, proposed guidelines, tooling assumptions, staffing model, QA approach, milestones, reporting, dependencies, and commercial assumptions.  
**Client approves:** scope, acceptance criteria, deliverables, access method, and review responsibilities.  
**Gate:** signed scope / order and approved data-handling terms before production data access.

### Stage 3 — Data and access readiness
- Confirm data source, transfer method, permissions, environment, approved storage, file structure, schema, and test samples.
- Verify that data access is authorized.
- Confirm sensitive-data restrictions, location requirements, retention/deletion expectations, and subcontractor permissions.
- Use a representative, authorized sample first when possible.
- Do not ask clients to upload confidential production data through a generic public web form.

### Stage 4 — Guidelines and calibration
- Create or refine taxonomy and annotation guidelines.
- Include positive examples, negative examples, boundary cases, exclusions, and escalation rules.
- Train assigned annotators and reviewers.
- Use agreed gold tasks / calibration samples.
- Review disagreement and update instructions.
- Obtain client sign-off on pilot results and acceptance criteria before scaling.

### Stage 5 — Pilot
- Run a representative, limited batch.
- Measure agreed metrics, review error patterns, estimate throughput, and confirm output compatibility.
- Capture unresolved questions and process risks.
- Share pilot results with the client.
- **Gate:** client approves pilot or requests revisions; do not scale automatically without agreed authorization.

### Stage 6 — Production
- Allocate trained people to tasks.
- Use role-based task assignment and appropriate access restrictions.
- Track throughput, backlog, defect trends, blockers, and changes to guidelines.
- Run regular calibration sessions and targeted refreshers.
- Escalate ambiguous or sensitive cases instead of guessing.
- Communicate material deviations from scope or schedule.

### Stage 7 — Quality assurance and adjudication
- Task-level self-checks and automated/schema checks where available.
- Independent reviewer checks at an agreed rate or coverage level.
- Gold-task / calibration checks where suitable.
- Adjudication for disagreements and ambiguous cases.
- Root-cause analysis for recurring errors.
- Dataset-level checks for completeness, consistency, duplicates, class distribution, and other agreed risks.
- Share QA findings and corrective actions.

### Stage 8 — Delivery and acceptance
- Deliver agreed output files, schema, version / batch information, QA summary, known limitations, exception log, and change notes as scoped.
- Validate transfer integrity and output format.
- Client reviews against the agreed acceptance criteria.
- Correct defects within the agreed remediation process.
- Obtain written acceptance or document open issues.

### Stage 9 — Retrospective and iteration
- Review quality, throughput, blockers, guideline gaps, and rework.
- Agree changes for the next batch.
- Update guidelines and versions under change control.
- Apply retention/deletion commitments at the end of the engagement.

### Process diagram requirement
Design a clear diagram showing:
- **Client inputs:** data, task definition, model/use case context, acceptance criteria, feedback.
- **Company workflow:** scope, prepare, train, annotate, review, adjudicate, validate, package.
- **Quality gates:** guideline sign-off, pilot approval, production QA, delivery acceptance.
- **Outputs:** annotated dataset, agreed exports, QA summary, exception log, delivery report.
- **Feedback loop:** client review → guideline change / rework → next batch.

The diagram must be understandable without reading a paragraph. Provide a desktop version and a mobile stacked version.

## 6.4 Quality Framework page

**Goal:** Show that quality is defined, measured, and improved rather than asserted as a vague promise.

### Required content

1. **Quality starts with a definition**
   - Establish label rules, edge cases, severity levels, sampling plan, acceptance thresholds, and ownership of final decisions.
2. **Contributor readiness**
   - Task-specific screening or qualification where appropriate.
   - Training and guideline comprehension checks.
   - Access granted only to people assigned to the project.
3. **Calibration**
   - Representative tasks and gold examples.
   - Compare annotator results against agreed references.
   - Discuss disagreements and revise instructions.
4. **Production checks**
   - Automated validation where tooling supports it.
   - Self-checks, reviewer checks, sampling or full inspection according to the contract.
   - Targeted review for high-risk labels or edge cases.
5. **Adjudication**
   - Route disputed cases to an assigned lead or subject-matter expert.
   - Record the final decision and update the guideline if the case reveals ambiguity.
6. **Dataset-level review**
   - Completeness, schema conformance, duplicates, class imbalance, coverage, and consistency where relevant.
   - Distinguish data quality from model performance; annotated data alone does not guarantee a specific model result.
7. **Corrective action**
   - Defect taxonomy, root cause, rework, retraining, and prevention.
8. **Reporting**
   - Agree a dashboard/report cadence and metrics per project.

### Candidate metrics (not universal promises)
- Label accuracy against an approved reference set.
- Reviewer rejection / rework rate.
- Inter-annotator agreement where meaningful.
- Gold-task pass rate.
- Schema / format validity.
- Coverage and completeness.
- Throughput and turnaround time.
- Defects by type and severity.
- Acceptance rate at client review.

Define every metric before using it. Specify denominator, sampling method, severity, exclusions, and reporting period. Do not use a single “accuracy” percentage without methodology. Some subjective tasks require rubric agreement rather than one objectively correct label.

### Visual requirement
Create an original layered diagram:
- Layer 1: task / annotation checks.
- Layer 2: independent review and adjudication.
- Layer 3: dataset consistency and coverage.
- Layer 4: contributor qualification and ongoing calibration.
- Feedback loop to guidelines and training.

Do not copy a competitor's diagram or proprietary labels.

## 6.5 Delivery Model page: in-house, BPO, and hybrid

**Goal:** Explain capacity and staffing flexibility without making outsourcing feel opaque or uncontrolled.

### Required model options
- **In-house delivery:** work assigned to internal teams when capability and capacity fit.
- **Approved BPO partner delivery:** defined tasks may be delivered by an approved third-party partner under explicit contractual and operational controls.
- **Hybrid delivery:** work distributed across internal and partner teams, with common standards and a designated delivery owner.

### Operating principles to communicate
- One accountable project / delivery lead.
- Common client-approved guidelines and training.
- Consistent QA methodology and acceptance criteria.
- Role-based access and least-privilege permissions.
- Partner onboarding and capability assessment.
- Contractual confidentiality, data-use restrictions, and permitted processing scope.
- Partner access only when client terms and applicable law permit it.
- Approved work locations / access environments based on contract and data sensitivity.
- Clear escalation, incident reporting, and corrective action.
- Visibility into who performs work, at the level agreed with the client.
- Change control if staffing location or subcontractor model changes.

### Required disclosure
Before the site goes live, the business owner and legal counsel must confirm how BPO partners will be disclosed and approved. Never imply that all annotators are employees if some are third-party personnel. Never claim a partner is certified or audited unless verified.

### Visual requirement
An original responsibility matrix showing:
- Client: task context, source data permissions, acceptance criteria, feedback.
- Delivery lead: accountable coordination, risk and scope management.
- Annotators: execute documented labeling tasks.
- QA / reviewers: inspect, adjudicate, report defects.
- BPO partner lead (if applicable): staffing, training, adherence to agreed controls.
- Security / legal contacts: access, incident, contractual questions.

## 6.6 Security and Responsible Data Handling page

**Goal:** Help buyers understand the data handling model and know whom to contact before transferring sensitive data.

This page must be reviewed by the actual security owner and legal counsel before publication. Publish only controls that are implemented and evidenced.

### Topics to cover
- Data ownership and permitted use.
- Data classification and project-specific restrictions.
- Data transfer and approved storage locations.
- Role-based access, least privilege, and access removal.
- Authentication and account management practices.
- Approved annotation tools / environments.
- Rules for local downloads, removable media, screenshots, copying, and onward sharing.
- BPO / subcontractor approval and access boundaries.
- Data retention and verified deletion process.
- Incident reporting and escalation contact.
- Backup and recovery practices, if applicable.
- Applicable privacy and contractual obligations.
- Security questionnaires / due diligence process.
- AI usage policy: whether client data may be sent to third-party AI tools or used for model training; default should be no such use without explicit authorization and a documented policy.

### Important limits
- Do not claim SOC 2, ISO 27001, GDPR compliance, HIPAA compliance, or other certification/compliance status without a verified basis and approved wording.
- Do not state “100% secure,” “zero risk,” or equivalent absolutes.
- Do not expose security-sensitive details publicly.
- Provide a secure, controlled channel for exchanging confidential files after initial qualification.
- Avoid placing a generic file-upload field on the public contact form.

## 6.7 Industries / Use Cases page

**Goal:** Help buyers recognize their use case without pretending the company has deep experience in every industry.

Each use-case card should explain:
- Typical AI problem.
- Relevant data types.
- Example annotation / evaluation tasks.
- Quality considerations.
- Relevant service link.

Potential categories (publish only when operationally supported):
- Computer vision and object recognition.
- Mobility / autonomous systems.
- Retail, ecommerce, and catalog intelligence.
- Geospatial and mapping.
- Conversational AI and LLM evaluation.
- Document intelligence.
- Audio and speech systems.

Use “use cases we can support” rather than claiming client experience. Regulated, sensitive, or safety-critical use cases require additional review and substantiation.

## 6.8 About Us page

**Goal:** Present a credible company identity and its operating philosophy.

Required sections:
- Mission and reason for the business.
- Approach to human expertise and AI data quality.
- How delivery teams are organized.
- Leadership bios only with approved, factual details.
- Locations and workforce footprint only if confirmed.
- Company values translated into observable practices.
- CTA.

Do not invent founders' credentials, years in business, employee count, office locations, customer list, or social-impact claims.

## 6.9 Contact / Scope a Project page

**Goal:** Gather enough information to qualify a lead without making the first step feel like a procurement form.

### Recommended fields
Required:
- Name.
- Work email.
- Company.
- What kind of help is needed (multi-select).
- Short project description.
- Consent / privacy acknowledgement where legally required.

Optional:
- Role.
- Data modality.
- Approximate volume range.
- Desired start date / timeline.
- Current tooling or preferred output format.
- Need for in-house / BPO / hybrid / guidance.
- Security or data residency constraints (high-level only; no sensitive details).
- Budget range, only if the sales team wants to ask it at this stage.

### Form behavior
- Clear labels, accessible validation, meaningful errors, and success state.
- Spam prevention and server-side validation.
- Privacy notice and retention policy.
- No sensitive file uploads on the public form.
- Route the inquiry to an owned and monitored business inbox / CRM only after configured.
- The current `hello@akki.ai` email in the prototype is a placeholder; verify ownership before launch.
- Provide a fallback email or contact route if submission fails.
- Define expected follow-up response time only after the business can meet it.

### Suggested success message
“Thanks for sharing your project. Our team will review the information and follow up using the contact details you provided.” Do not promise a specific response time unless approved.

---

## 7. The end-to-end operating workflow

This workflow is the operational source of truth that the website should reflect. Business operations must validate it before publication.

### Workflow at a glance

1. Inquiry received.
2. Lead qualification and discovery.
3. Feasibility assessment.
4. Scope, deliverables, assumptions, and acceptance criteria agreed.
5. Contract, data processing terms, and any BPO approvals completed.
6. Data access and tooling readiness confirmed.
7. Guidelines and taxonomy authored / refined.
8. Annotators and reviewers selected, trained, and qualified.
9. Calibration and pilot run.
10. Client review and pilot approval.
11. Production batches assigned and executed.
12. QA checks, adjudication, defect analysis, and corrective actions.
13. Batch reporting and client feedback.
14. Final output validation and delivery.
15. Client acceptance and remediation, if required.
16. Retrospective, retention/deletion actions, and next-batch planning.

### Roles and responsibilities

| Role | Primary responsibility |
|---|---|
| Client project owner | Business context, data authorization, requirements, feedback, acceptance |
| Account / solution lead | Discovery, fit assessment, scoping, assumptions, commercial coordination |
| Project / delivery manager | Schedule, staffing, dependencies, status, blockers, change control |
| Annotation lead | Taxonomy, instructions, training, ambiguity and escalation handling |
| Annotator | Execute assigned tasks using the approved guidelines |
| QA reviewer | Inspect output, record defects, validate rules, recommend rework |
| Adjudicator / subject-matter expert | Resolve difficult disagreements and document decisions |
| BPO partner lead (where applicable) | Partner staffing, training, adherence to contract and SOPs |
| Security / privacy owner | Approve data access, environments, controls, and incident escalation |
| Client acceptance owner | Review delivered batches against agreed criteria |

One person may hold multiple roles in a small project, but accountability must still be explicit.

### Workflow statuses for a future client reporting model
- Intake
- Discovery
- Scoping
- Awaiting client inputs
- Access / data readiness
- Guideline preparation
- Calibration
- Pilot in progress
- Awaiting pilot approval
- Production
- QA / adjudication
- Awaiting client review
- Rework
- Accepted / delivered
- Closed

These are suggested operational statuses, not a promise that the website currently includes a live project-tracking portal.

---

## 8. Brand and visual design system

### 8.1 Desired creative direction

**“Precision meets human intelligence.”**

The design should feel:
- Enterprise-grade and trustworthy.
- Contemporary and technology-forward.
- Confident but not boastful.
- Human-led without generic stock photography.
- Technical enough for AI teams, clear enough for non-technical buyers.
- Distinctive and editorial, with a considered use of space and a recognizable visual system.

### 8.2 Visual identity

The current prototype uses a dark forest-green background and lime accent. Treat this as a starting direction, not a locked brand decision. The design team should explore 2–3 tightly art-directed variations and select one before expanding all pages.

Possible palette:
- Deep ink / near-black green for the foundation.
- Warm off-white for primary text.
- Muted neutral green-gray for secondary text.
- Restrained acid-lime accent for actions and active data markers.
- Additional colors only when they convey a meaning in diagrams or annotation examples.

Use strong contrast and test all text against WCAG 2.2 AA targets. Accent colors should not carry meaning alone.

### 8.3 Typography
- Use a high-quality modern sans-serif for headings and body text.
- Use a restrained mono font for labels, workflow states, data metadata, and technical details.
- Use a deliberate hierarchy: oversized but readable headline, concise body copy, clear section headings, compact eyebrow labels.
- Avoid excessive uppercase text, tiny body copy, and long lines.
- Body text target: approximately 16–18 px desktop and 15–17 px mobile, with comfortable line height.

### 8.4 Layout and interaction
- Strong grid and consistent alignment.
- Generous negative space.
- Cards only when they support grouping; avoid a page made entirely of identical cards.
- Use original process diagrams, data-flow illustrations, annotated sample outputs, and quality report visuals.
- Motion should explain state or flow, not distract.
- Respect `prefers-reduced-motion`.
- All interactions must work with keyboard and touch.
- Keep mobile layouts intentionally designed, not simply compressed desktop layouts.

### 8.5 Image and illustration direction
Prefer:
- Custom abstract data-to-output diagrams.
- Cropped annotation samples with clearly fictional/synthetic data.
- Human review and workflow imagery where authentic and appropriately licensed.
- Sample quality reports, schema snippets, and project artifacts.
- Visualizations of annotation, review, and dataset validation.

Avoid:
- Generic robot heads, glowing brains, stock circuit-board backgrounds.
- Fake screenshots of nonexistent proprietary tools.
- Unlicensed competitor screenshots, logos, or artwork.
- Real client data or identifiable sensitive data in examples.

### 8.6 Components to design
- Header / desktop navigation / mobile menu.
- Primary, secondary, and text CTA buttons.
- Hero layouts.
- Service cards and service detail sections.
- Process stepper / workflow diagram.
- Quality framework diagram.
- Delivery model comparison.
- Data flow / input-output visualization.
- Case-study template.
- FAQ accordion.
- Lead form, validation, loading, error, and success states.
- Footer.
- Cookie / consent UI only if needed based on actual analytics and applicable law.
- Breadcrumbs for deeper pages.

### 8.7 Design deliverables
- Brand direction board and palette.
- Typography and spacing tokens.
- Responsive desktop, tablet, and mobile layouts.
- Component library with states.
- High-fidelity homepage.
- High-fidelity templates for service, process, quality, delivery model, security, about, and contact pages.
- Original diagrams and illustration assets.
- Interactive prototype showing navigation and the primary lead flow.
- Annotated handoff notes and accessibility considerations.

---

## 9. Content and evidence requirements

### Content tone
- Direct, precise, calm, and technically credible.
- Explain technical terms in plain English when first used.
- Focus on client outcomes and operational proof.
- Avoid empty phrases such as “revolutionary,” “world-class,” “unmatched,” and “cutting-edge” unless backed by specific evidence.
- Avoid guaranteeing model performance or universal accuracy.

### Evidence register
Before publication, maintain a simple register for every factual claim:
- Exact claim.
- Evidence / source.
- Owner who approved it.
- Date last checked.
- Expiry / review date if relevant.
- Pages where the claim appears.

Evidence required for:
- Client logos, testimonials, and case studies.
- Accuracy, acceptance, volume, speed, cost, and workforce statistics.
- Years of experience.
- Languages, modalities, domain qualifications, and capacity.
- Security certifications and compliance statements.
- Offices, locations, and delivery footprints.
- Partnerships, integrations, and tooling claims.

If evidence is unavailable, omit the claim or label the example clearly as illustrative.

### Case-study template (future)
1. Client / industry context, with publication approval.
2. Problem and model use case.
3. Dataset type and scope (approved disclosure level).
4. Workflow and quality approach.
5. Challenges / edge cases.
6. Deliverables.
7. Measured results and measurement method.
8. Client quote only with permission.
9. Limitations / context where needed.

### Illustrative example policy
If the company has no publishable case studies at launch, show a “Sample workflow” or “Illustrative dataset example” rather than a fabricated customer story. Use synthetic data and label it clearly.

---

## 10. Technical and functional requirements

### 10.1 Build approach
The current repository contains a single `index.html` prototype. Before selecting a framework, the developer should review the repository and propose the simplest maintainable approach that fits hosting, performance, and the need for multiple pages. Do not introduce a heavy framework solely for fashion.

Preferred principles:
- Semantic HTML.
- Maintainable CSS tokens and reusable components.
- Small, purposeful JavaScript.
- Progressive enhancement.
- Static pages where possible.
- Secure server-side form processing or a vetted form/CRM integration.
- Clear environment configuration and documented deployment.

If the project grows into many service pages, case studies, and resources, evaluate a maintainable multi-page framework or static-site generator. Record the decision and rationale.

### 10.2 Required functionality
- Navigation links reach the correct sections/pages.
- Responsive mobile menu opens and closes correctly.
- CTAs go to real destinations.
- Contact form validates and submits to a configured destination.
- Success and failure states are implemented.
- Email links use a verified address.
- No dead links, placeholder hrefs, or misleading buttons.
- All forms have labels and accessible error messaging.
- All images have appropriate alt text or are marked decorative.
- Keyboard navigation and visible focus states work.
- Reduced-motion preferences are respected.
- External links behave consistently and safely.

### 10.3 Performance and compatibility
Targets for testing, not a guarantee:
- Aim for good Core Web Vitals, including LCP ≤ 2.5s, INP ≤ 200ms, and CLS ≤ 0.1 at the 75th percentile where field data is available.
- Optimize images and serve appropriate responsive sizes.
- Minimize render-blocking scripts and unnecessary third-party tools.
- Test current Chrome, Safari, Firefox, Edge, iOS Safari, and Android Chrome.
- Test common viewport sizes and slower mobile connections.
- Avoid heavy video backgrounds and excessive animation.

### 10.4 Accessibility
Target WCAG 2.2 AA:
- Sufficient contrast.
- Semantic headings and landmarks.
- Keyboard-operable menus, accordions, and forms.
- Visible focus indicators.
- Accessible form labels and errors.
- Meaningful link names.
- Screen-reader-friendly status updates.
- Text alternatives for meaningful visuals.
- No information conveyed by color alone.
- Reduced-motion support.

### 10.5 SEO
- Unique title and meta description for every indexable page.
- One clear H1 per page and logical heading hierarchy.
- Descriptive URLs.
- Canonical URLs once the production domain is chosen.
- XML sitemap and robots.txt.
- Open Graph metadata.
- Structured data only when accurate and appropriate (for example, Organization and BreadcrumbList).
- Image optimization and descriptive alt text.
- Internal linking between service, process, quality, and contact pages.
- Search intent mapped to actual service capability; do not create thin pages for every keyword.
- No indexing of staging, preview, or private client materials.

### 10.6 Privacy and security
- HTTPS in production.
- Server-side validation, spam prevention, and safe handling of inquiry data.
- Secrets and API keys never embedded in client-side JavaScript or repository source.
- Minimal personal data collection.
- Documented retention and deletion for form submissions.
- Privacy policy and any required consent mechanisms reviewed before launch.
- No confidential project uploads in a public web form.
- Dependency updates and basic vulnerability checks.
- Restrict access to the repository and deployment environment appropriately.

---

## 11. Information architecture and navigation behavior

### Desktop
Header should remain clear and lightweight. Main nav: Services, How We Work, Quality, Delivery Model, About. Primary CTA: “Discuss a project.”

### Mobile
- Accessible menu toggle with clear open/close state.
- Close menu after navigation.
- Ensure menu overlays content without trapping the user unexpectedly.
- CTA should remain easy to reach without covering content.

### CTA consistency
Primary CTA wording should remain consistent across pages. Recommended default: **Discuss a project**. Use **Scope a pilot** when the linked flow genuinely supports a pilot conversation.

### Footer
Include:
- Short company description.
- Core services.
- How We Work.
- Quality and Delivery Model.
- Contact.
- Privacy and Terms.
- LinkedIn or other social links only when official profiles exist.
- Copyright year generated automatically.

---

## 12. Content model and page template

For maintainability, the content structure should support reusable records.

### Service record
- Service name.
- Short value proposition.
- Data modalities.
- Task types.
- Typical inputs.
- Typical outputs.
- Workflow steps.
- Quality considerations.
- Required client inputs.
- Related industries / use cases.
- FAQs.
- CTA.

### Case-study record (future)
- Title.
- Client / industry (approval status).
- Challenge.
- Data scope.
- Approach.
- Quality process.
- Outcomes and evidence.
- Quote / permission status.
- Related services.

### Resource record (future)
- Title, summary, topic, author, publication date, reviewed date, SEO metadata, related service, CTA.

Content must be reviewed by a business owner who can confirm delivery capability, and by security/legal stakeholders for sensitive claims.

---

## 13. Analytics and lead management

Before launch, decide:
- Where form submissions are sent.
- Who owns lead follow-up.
- How lead qualification is recorded.
- Whether a CRM is available.
- Which analytics platform will be used.
- Whether consent is required for optional tracking.
- What event data is necessary and how long it is retained.

Recommended events:
- `project_cta_click`
- `contact_form_start`
- `contact_form_submit_success`
- `contact_form_submit_error`
- `service_page_view`
- `quality_page_view`
- `delivery_model_page_view`
- `pilot_cta_click`

Do not capture sensitive project descriptions, personal data, or confidential information in analytics events.

---

## 14. Acceptance criteria

The website is not considered ready because the homepage looks attractive. It is ready only when content, behavior, responsiveness, accessibility, and trust requirements pass review.

### Business and content
- [ ] The website clearly explains the managed-service business model.
- [ ] Visitors can understand the end-to-end client workflow.
- [ ] The roles of annotators, QA reviewers, leads, project managers, clients, and BPO partners are explained.
- [ ] Quality methods are specific and do not rely on unsupported guarantees.
- [ ] In-house / BPO / hybrid delivery is transparent and responsibly described.
- [ ] Services advertised match actual delivery capability.
- [ ] All statistics, logos, certifications, testimonials, and case studies have evidence and approval.
- [ ] Security and data-handling statements match implemented controls.
- [ ] The contact method is real and monitored.

### Design
- [ ] Homepage and core page templates are approved at desktop, tablet, and mobile sizes.
- [ ] Visual identity is consistent and distinct from competitors.
- [ ] Process and QA diagrams are original, readable, and accurate.
- [ ] Typography, spacing, color, and components follow design tokens.
- [ ] Motion is purposeful and reduced-motion behavior works.

### Functional
- [ ] All navigation and CTA links work.
- [ ] Mobile menu behavior is correct.
- [ ] Contact form has validation, error, loading, and success states.
- [ ] Form submissions reach the intended inbox/CRM.
- [ ] No placeholder links, false product demos, or nonfunctional controls remain.
- [ ] No console errors or broken assets in supported browsers.

### Technical
- [ ] Production build and deployment steps are documented.
- [ ] No secrets are committed.
- [ ] SEO metadata and sitemap are present.
- [ ] HTTPS and required security configuration are active.
- [ ] Performance is tested and bottlenecks addressed.
- [ ] Accessibility review is completed against WCAG 2.2 AA target.
- [ ] Privacy, terms, and consent requirements have been reviewed.
- [ ] Analytics events are tested without collecting sensitive content.

---

## 15. Phased delivery plan

### Phase 0 — Business and capability confirmation
**Outputs:** final brand name, confirmed services, delivery model, actual security controls, contact details, target industries, initial proof points.  
**Exit gate:** no unsupported capability or trust claims remain in the content draft.

### Phase 1 — Research and content architecture
**Outputs:** approved sitemap, competitor pattern summary, user journeys, page goals, content outline, claims/evidence register.  
**Exit gate:** business owner approves what the site says and does not say.

### Phase 2 — UX and design
**Outputs:** wireframes, navigation model, responsive layouts, design tokens, high-fidelity homepage, core page templates, original diagrams, interactive prototype.  
**Exit gate:** business, design, and delivery owners approve key flows and content hierarchy.

### Phase 3 — Development
**Outputs:** multi-page website, reusable components, responsive behavior, contact form integration, metadata, accessible interaction, deployment configuration.  
**Exit gate:** feature-complete build on staging.

### Phase 4 — Content and technical QA
**Outputs:** fact-checking, responsive/browser testing, accessibility review, link checks, performance fixes, SEO review, form testing, privacy/security review.  
**Exit gate:** acceptance checklist signed off.

### Phase 5 — Launch and improvement
**Outputs:** production deployment, analytics verification, lead-routing test, monitoring, feedback backlog.  
**Exit gate:** real inquiries can be received and handled end-to-end.

---

## 16. Dependencies, owners, and open questions

| Dependency / decision | Suggested owner | Needed before |
|---|---|---|
| Final company and domain name | Business owner | Final design / launch |
| Confirmed service list and current capability | Business + delivery lead | Content approval |
| In-house / BPO / hybrid operating model | Business + operations + legal | Delivery page approval |
| Actual QA process and metrics | Delivery / QA lead | Quality page approval |
| Security controls and partner access rules | Security / legal owner | Security page approval |
| Real contact email and lead owner | Business / sales | Form integration |
| Hosting / deployment choice | Technical owner | Development |
| CRM or form destination | Sales / operations | Form integration |
| Approved photos, logos, biographies, case studies | Business / marketing | Proof sections |
| Privacy policy and terms | Legal | Launch |
| Analytics and consent approach | Marketing / privacy owner | Launch |
| Final brand identity and domain | Business / design | Production assets |

### Questions to resolve
1. Is “Akki AI” the final public brand, or only the repository / working name?
2. Which services can be delivered on day one, and which are future capabilities?
3. Will the initial team be in-house, BPO-based, or hybrid?
4. If BPO is used, how will partners be approved, disclosed, and restricted from accessing data?
5. Which geographies and industries are in scope initially?
6. What data types, languages, tools, and output formats are genuinely supported?
7. What quality metrics can be measured reliably and shared with clients?
8. Are there real client projects or anonymized work samples that can be shown with permission?
9. Which security controls are already implemented? Which certifications, if any, are independently verified?
10. What business email, domain, CRM, and lead follow-up process will be used?
11. Should pricing be discussed only after discovery, or should the site include a pilot / pricing framework?
12. Who signs off on the website copy, security statements, and service commitments?

---

## 17. Immediate changes to the current prototype

The current `index.html` is an initial single-page concept, not the final site. Use it as a visual direction reference only.

Recommended next changes:
1. Confirm the brand name and whether the current dark-green/lime palette is retained.
2. Convert the single-page prototype into the approved multi-page information architecture.
3. Expand “How We Work” to include the full client journey, approval gates, and outputs.
4. Create dedicated Quality Framework and Delivery Model pages.
5. Add a dedicated Security / Responsible Data Handling page after the real controls are confirmed.
6. Add a detailed, honest service taxonomy and modality pages based on day-one capability.
7. Replace any placeholder contact email with a verified contact method.
8. Add a real form submission path only after an inbox or CRM is configured.
9. Replace illustrative claims or graphics that could be interpreted as actual performance data with explicitly labeled sample content.
10. Add a future case-study system, but do not publish fictional case studies.
11. Test all navigation, mobile behavior, accessibility, performance, SEO, and contact flow before launch.

---

## 18. Source references

These references informed the competitive pattern review. They are external examples, not endorsements and not a source of claims about this company.

- Sama — https://www.sama.com/
- Sama Data Annotation — https://www.sama.com/data-annotation-solution
- Sama Annotation and Validation Platform — https://www.sama.com/data-annotation-and-validation-platform
- TELUS Digital Data Annotation — https://www.telusdigital.com/solutions/data-for-ai-training/data-annotation-services
- TELUS Digital Data for AI Training — https://www.telusdigital.com/solutions/data-for-ai-training
- Scale AI Data Engine — https://scale.com/data-engine
- Scale AI Quality Engineering — https://scale.com/blog/data-quality
- iMerit — https://imerit.ai/
- Invisible Technologies Data Lab — https://invisibletech.ai/data-lab
- Labelbox — https://labelbox.com/
- Labelbox documentation — https://docs.labelbox.com/docs
- CloudFactory — https://www.cloudfactory.com/

**Review note:** Competitor messaging and offerings change. Revisit these links during design sign-off. The goal is to derive an original, credible experience from common enterprise best practices—not to clone a competitor's current website.

---

## Final direction

Build a website that makes the buyer confident about **the work, the people, the workflow, the quality controls, and the accountability**. The strongest differentiator should be operational transparency: show how a project is defined, staffed, trained, reviewed, corrected, and accepted.

The website must be ambitious in presentation and disciplined in its claims. It should look like an enterprise partner from day one while clearly distinguishing proven capabilities from planned capabilities.


---

## 19. Updated Design Direction and Implementation Decisions (2026-10-26)

### 19.1 Brand status and governance
- Official company name is **not yet confirmed**. Do not treat “Akki AI” as the approved public brand. It may remain a repository/project working label only until management confirms the legal and customer-facing name.
- Keep the logo, wordmark, domain, favicon, email address, social links, and brand-specific copy easy to replace.
- Do not invent a tagline as an official brand asset. Any tagline in prototypes is placeholder copy pending approval.
- Target geography is global, but no primary customer segment has been selected. Use broadly understandable international B2B English; do not claim global offices, worldwide delivery coverage, local presence, or specific regional compliance without evidence.

### 19.2 Brand personality
The agreed direction is **premium and enterprise-grade**. The site should feel confident, precise, thoughtful, and credible. Avoid both a generic blue corporate template and over-stylized “AI futurism” (neon glows, robot heads, glowing brains, excessive gradients, and motion without purpose).

### 19.3 Palette exploration (compare before locking)
The premium editorial direction is agreed, but the final palette is **not approved yet**. Compare at least these three distinct options in a small design study before implementation is locked:

**Palette A — Evergreen / Ivory / Brass (recommended starting candidate)**
- Deep evergreen: `#153C35`
- Warm ivory: `#F5F1E8`
- Muted brass: `#B69A61`
- Charcoal: `#252C2A`
- Soft mint: `#A7DCC5`
- Intended effect: grounded, premium, distinctive, and compatible with the existing green prototype.
- Risks: too much brass can feel decorative; large dark sections can make pages heavy.

**Palette B — Midnight Navy / Porcelain / Copper**
- Midnight navy: `#17263D`
- Porcelain: `#F7F8F5`
- Copper: `#B87552`
- Slate: `#354052`
- Mist blue: `#D8E3E9`
- Intended effect: established enterprise confidence with a technical feel.
- Risks: can feel conventional in the B2B technology category; copper should be an accent, not a dominant fill.

**Palette C — Graphite / Chalk / Electric Jade**
- Graphite: `#202725`
- Chalk: `#F4F4EF`
- Jade: `#2E806B`
- Pewter: `#89938E`
- Pale jade: `#D8E9E2`
- Intended effect: contemporary, restrained, technical, and highly legible.
- Risks: less warm or visibly “premium” than Palette A unless typography and spacing are excellent.

**Palette evaluation rules**
- Build comparable hero + service-card + CTA samples for all three palettes, using the same copy and layout so color is the main variable.
- Test normal text and interactive states for WCAG 2.2 AA contrast where applicable; do not assume the palette is accessible based on appearance alone.
- Check desktop and mobile, light and dark sections, focus/hover/disabled/error states, and long-form content.
- Keep gold/copper/jade as accents. Never use low-contrast accent text for essential body copy.
- Record the selected palette and rationale in the design tokens section after review. Until then, Palette A is a recommendation, not a final approval.

### 19.4 Typography and visual language
- Initial type pairing to test: Manrope for display/headings and Inter for body/interface. Confirm readability, rendering, licensing/hosting approach, and performance before final selection.
- Prefer clear type hierarchy, generous whitespace, restrained borders, consistent grid alignment, and purposeful section rhythm.
- Use authentic annotation examples, illustrative data visualizations, and original workflow diagrams to explain the work.
- Use genuine team photography only when available and approved. Stock imagery must not imply that pictured people are company employees, clients, or actual project participants.
- Avoid invented dashboard screenshots that imply a proprietary platform exists. Label concept visuals as illustrative when needed.

### 19.5 Positioning and audience
- Working positioning: **a managed AI data services partner** that helps clients scope and coordinate annotation/data projects and oversees delivery and quality checks, subject to operational confirmation.
- Audience: broad B2B audience; target geography: global. No single vertical or customer segment is prioritized yet.
- The homepage should lead with the customer problem and managed outcome, then provide clear paths to service categories, delivery approach, quality, and project inquiry.
- Potential audience paths: AI/model developers; enterprise AI teams; technology vendors and BPO/implementation partners. Do not create separate brands or imply equal maturity in every market.
- Avoid claims such as “industry-leading,” “world-class,” “most accurate,” “lowest cost,” “global network,” or guaranteed speed/scale unless evidence and management approval support them.

### 19.6 Proposed service taxonomy — pending management confirmation
The following categories are under consideration, not yet confirmed public offerings:
1. Image and video annotation.
2. Text and document annotation.
3. Audio and speech annotation.
4. LLM and generative AI data.
5. Data collection and data curation.
6. 3D, LiDAR, and autonomous-vehicle data.

For each category, management must confirm available task types, tooling, workforce expertise, supported languages/modalities, data handling constraints, delivery capacity, and any excluded work. Publish only the capabilities the business can actually deliver. The 3D/LiDAR category is especially specialized and should not be presented as available until expertise and tooling are verified.

### 19.7 Delivery model and quality ownership
- Delivery mix (internal team, BPO partners, or hybrid) is **not yet known** and must be confirmed.
- Current stated operating assumption: the company owns client coordination, project management, and quality checks. Confirm this with management before presenting it as a formal service commitment.
- Safe provisional language: “A managed delivery approach shaped around your project requirements.” Do not imply a specific staffing model, partner network, or scale.
- Before publishing QA details, confirm actual stages, reviewer responsibilities, sampling strategy, disagreement resolution, rework loops, acceptance criteria, reporting, and escalation.
- Do not publish accuracy percentages, turnaround guarantees, or capacity figures until they are measured, defined, and approved.

### 19.8 Differentiation hierarchy
**Lead positioning candidates**
1. Quality and accountability.
2. Flexible delivery and scaling.
3. Partnership and personalized service.

**Supporting themes**
- Cost-effective delivery: describe value and fit, not “lowest cost” or guaranteed savings.
- Specialized AI expertise: substantiate with named capabilities and verified team experience.
- Fast onboarding: describe the process, not unverified turnaround promises.
- Data security and confidentiality: provide a trust section only with verified controls, policies, contractual practices, and certifications where applicable. Never imply certification without evidence.

These are proposed brand priorities, not proven competitive advantages yet. They should be validated with management and then supported by real process descriptions or evidence.

### 19.9 Homepage content order
1. Hero: clear AI data services positioning, concise supporting explanation, primary project-inquiry CTA, and secondary services CTA.
2. Service categories, limited to confirmed capabilities.
3. How projects work: requirements and scoping, data/task preparation, annotation, quality review, correction/validation, delivery and feedback. Adjust to actual operations.
4. Quality and accountability: explain verified process controls rather than unsupported performance numbers.
5. Delivery approach: publish only after confirming internal/BPO/hybrid model.
6. Security and responsible data handling: factual, reviewed by management.
7. Industry/use-case examples: illustrative use cases clearly distinguished from client case studies.
8. Project inquiry form and clear contact route.

### 19.10 Conversion and inquiry requirements
- Primary CTA candidate: “Discuss a project” or “Tell us about your data.” Final copy depends on brand approval.
- Ask for only useful lead qualification details: name, work email, company, project type, approximate volume, timeline, and a short description. Make phone number and file upload optional unless a real operational need exists.
- Do not request sensitive or confidential datasets through an unsecured form. Display a concise instruction not to submit confidential data before an agreed secure transfer method is established.
- Form submission, privacy notice, consent where required, spam prevention, routing, confirmation message, and responsible recipient must be confirmed before launch.
- Do not show placeholder email addresses, nonfunctional CTA buttons, fake chat widgets, or forms that appear to submit but do not.

### 19.11 Implementation decisions and delivery plan
**Stage 0 — Confirm fundamentals**
- Obtain official company name, logo/brand assets, domain, approved contact details, and who can approve copy.
- Confirm service categories and exact deliverable examples.
- Confirm delivery model and quality ownership.
- Confirm target geographies, industries, languages, project size ranges, and whether client data can be shown in demonstrations.
- Confirm actual security/privacy practices and legal review requirements.

**Stage 1 — Design exploration**
- Create three comparable palette treatments (A, B, C) for the homepage hero, service cards, and CTA.
- Use the same structure and provisional copy for a fair comparison.
- Check contrast, responsive behavior, typography, and visual distinctiveness.
- Record final choice as design tokens only after approval.

**Stage 2 — Design system and homepage**
- Define color tokens, typography scale, spacing, layout grid, breakpoints, buttons, cards, forms, focus states, and motion rules.
- Implement the homepage using reusable components and responsive semantic HTML.
- Use a clearly marked provisional brand name only in development, never as approved final copy.
- Keep content data separate from layout so the official name and service list can be changed without rebuilding components.

**Stage 3 — Core service and trust pages**
- Build services, workflow, quality, delivery model, security/data handling, and contact pages based on verified facts.
- Do not publish unsupported case studies, customer logos, metrics, awards, certifications, or workforce claims.

**Stage 4 — QA and launch readiness**
- Test mobile, tablet, and desktop layouts; keyboard navigation; focus visibility; color contrast; form validation; links; performance; metadata; and basic accessibility.
- Confirm privacy/legal content, analytics consent requirements where relevant, contact routing, and ownership of incoming leads.
- Review all claims against a management-approved evidence checklist before deployment.

### 19.12 Current decisions and open questions
**Decisions made**
- Premium and enterprise-grade brand personality.
- Compare alternative palettes before finalizing; Palette A is only the initial recommendation.
- Global-facing website, broad B2B audience, no single segment prioritized.
- Position around managed AI data services, with quality/accountability, flexible delivery, and personalized partnership as proposed themes.
- Candidate services include image/video, text/document, audio/speech, LLM/GenAI, data collection/curation, and 3D/LiDAR/AV data.
- Company name and delivery mix remain unconfirmed.

**Open questions for management**
1. What is the official company name and approved brand asset set?
2. Which services are ready to sell today versus future ambitions?
3. What is the real internal/BPO delivery arrangement?
4. What quality checks and evidence can be described publicly?
5. What security/privacy controls and certifications are actually in place?
6. Which geographies, industries, languages, and project sizes are realistic initial targets?
7. Who receives project inquiries, and what is the approved contact address?
8. Is there a real company team, facility, toolchain, or project example that can be shown publicly?

**Launch gate:** no public deployment until the company name, contact route, service claims, privacy/security statements, and lead form behavior have been reviewed and approved.


### 19.13 Approved palette decision — Palette A (2026-10-26)
Palette A is selected as the working visual direction. Palette B and Palette C are no longer candidates for the current implementation unless management later reopens the decision.

**Design tokens**
- Primary deep evergreen: `#153C35`
- Main warm ivory: `#F5F1E8`
- Accent muted brass: `#B69A61`
- Primary text charcoal: `#252C2A`
- Secondary technical accent soft mint: `#A7DCC5`

**Usage rules**
- Use warm ivory for most long-form and service-page surfaces, with charcoal text for readability.
- Use deep evergreen for the hero, selected feature bands, navigation accents, and footer; avoid making every section dark.
- Use brass sparingly for primary actions, key separators, and small emphasis. Do not use brass for small body text unless contrast is verified.
- Use soft mint as a secondary highlight for technical diagrams, annotation details, and selected interface states—not as a competing primary color.
- Maintain consistent semantic tokens (background, surface, text, muted text, border, primary action, focus, success, warning, and error) so later adjustments are systematic.
- Validate text, buttons, focus indicators, and interactive states against WCAG 2.2 AA contrast requirements where applicable. The palette is selected, but accessibility is not assumed until tested.
- Typography starting point remains Manrope for display/headings and Inter for body/interface, pending rendering and performance checks.
- Brand personality remains premium and enterprise-grade, with editorial spacing, restrained motion, original data/workflow visuals, and no generic AI clichés.
- The official company name is still unconfirmed. Keep the name/logo/domain/contact details replaceable and do not publish “Akki AI” as an approved brand without management confirmation.
