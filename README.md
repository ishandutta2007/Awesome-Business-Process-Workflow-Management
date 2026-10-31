# Awesome-Business-Process-Workflow-Management

# Awesome-Business-Process-Workflow-Management

**Top Business Process Workflow Management (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on BPMN Engines, Visual Workflow Builders, Approval Automation & Self-Hosted Process Platforms*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Business Process & Workflow Management**. These tools enable organizations to model, automate, and monitor business processes—from fully managed low-code platforms with visual builders and AI agents to self-hosted BPMN engines that give teams complete control over their process logic and execution infrastructure.



**Examples** include Camunda, Nintex, Kissflow, Pipefy, Process Street, ServiceNow Workflow, Microsoft Power Automate, Jira Workflow, BP Logix, and Fluix (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted BPM, workflow automation, and open process infrastructure. **Critical note**: The open-source BPM landscape is mature and genuinely competitive—**Camunda 7** and its fork **CIB seven** dominate enterprise BPMN execution, **Flowable** offers the most modern alternative, and **Bonita** provides a low-code approach. No open-source project matches Nintex's SharePoint-native workflow depth or ServiceNow's ITSM integration, but for core process automation, the open-source engines are production-proven at scale.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Camunda](https://camunda.com/)**

  **Process orchestration platform** with BPMN, DMN, and CMMN engines. Camunda 8 (Zeebe) is cloud-native with gRPC and Kubernetes support; Camunda 7 Community Edition remains available under Apache 2.0/MIT but is in maintenance . **Pricing**: Development (self-managed) free; Production self-managed requires Enterprise license; SaaS offers 30-day trial . **Free tier**: Free for development/non-production self-managed use. **Best for**: developer-centric teams wanting the most widely adopted BPM engine with strong microservice orchestration—**note**: Camunda 8 uses SSPL license with SaaS resale restrictions .



- **[Nintex](https://www.nintex.com/)**

  **Workflow automation and process management** with document generation and RPA. **Pricing**: Quote-only; observed annual contracts range from $15,000–$50,000 for small deployments to $200,000+ for enterprise . **Free tier**: None. **Best for**: organizations heavily invested in Microsoft/SharePoint ecosystems.



- **[Kissflow](https://kissflow.com/)**

  **No-code/low-code workflow and process platform**. **Pricing**: Basic from $2,500/month; Enterprise custom with AI Copilot . **Free tier**: None; trial available. **Best for**: business teams wanting self-service process automation without developer involvement.



- **[Pipefy](https://www.pipefy.com/)**

  **Workflow management platform** with visual process builder and automation. **Pricing**: Quote-only. **Free tier**: Limited free tier available. **Best for**: operations and HR teams wanting a user-friendly workflow builder without BPMN complexity.



- **[Process Street](https://www.process.st/)**

  **Checklist and workflow automation** platform for recurring processes. **Pricing**: Tiered per-user pricing. **Free tier**: Limited free tier. **Best for**: teams needing simple, repeatable checklist-driven workflows.



- **[ServiceNow Workflow](https://www.servicenow.com/)**

  **Enterprise workflow automation** within the ServiceNow platform, including Flow Designer. **Pricing**: Quote-only; bundled with ServiceNow subscriptions. **Free tier**: None. **Best for**: ServiceNow customers wanting workflow automation tightly integrated with ITSM and enterprise data.



- **[Microsoft Power Automate](https://powerautomate.microsoft.com/)**

  **Workflow automation** across Microsoft 365, Dynamics 365, and 1,000+ connectors. **Pricing**: Per-user plans from ~$15/user/month; flow-based pricing available. **Free tier**: Limited included with Microsoft 365. **Best for**: Microsoft-centric organizations wanting automation within their existing ecosystem.



- **[Jira Workflow](https://www.atlassian.com/software/jira)**

  **Workflow engine within Jira** for issue tracking and approval processes. **Pricing**: Included with Jira plans; advanced features require Premium/Enterprise. **Free tier**: Limited on Jira Free. **Best for**: software teams wanting workflow states and transitions within their issue tracker—**not** a general-purpose BPM platform.



- **[BP Logix](https://www.bplogix.com/)**

  **BPM and workflow automation** platform with process timeline modeling. **Pricing**: Quote-only. **Free tier**: None. **Best for**: regulated industries needing process compliance and audit trails.



- **[Fluix](https://fluix.io/)**

  **Workflow automation for field teams** with mobile forms and document workflows. **Pricing**: Quote-only; per-user. **Free tier**: Trial available. **Best for**: field service and construction teams needing mobile-first process automation.



## Open-Source GitHub Projects



- **[CIB seven](https://github.com/cibseven/cibseven)**

  **Camunda 7 fork providing long-term open-source BPMN execution** (Apache 2.0) — **the most important open-source BPM development of 2025–2026** for teams invested in Camunda 7. Since Camunda discontinued manufacturer support for the Camunda 7 Community Edition, **CIB seven fills the gap** with guaranteed maintenance beyond 2025 . **Features**: **100% Camunda 7 compatible**—drop-in replacement without code changes; BPMN 2.0, DMN 1.3, and CMMN engines; modernized web apps (Cockpit for monitoring, Tasklist for task management, Admin for user/permission management); native support for Java, Spring Boot, Jakarta EE, and Quarkus; REST API; plugin architecture; Docker images and Helm charts; PostgreSQL, Oracle, MS SQL, MySQL support . **Tech stack**: Java (main), JavaScript (Vue 3). **Deploy**: Self-hosted (Docker, Helm) or on-premises . **Trade-off**: **Fork of an aging architecture**—Camunda 7's design is proven but not cloud-native like Camunda 8. No Zeebe distributed execution. **Best for**: public sector, regulated enterprises, and any organization running Camunda 7 that needs guaranteed long-term open-source maintenance without migrating to Camunda 8's licensing model.



- **[Flowable](https://github.com/flowable/flowable-engine)**

  **Cloud-native BPMN, CMMN, and DMN engine suite** (Apache 2.0) — **the strongest alternative to Camunda** for microservice and event-driven architectures, with active development and a modern approach . **Features**: Separate embeddable engines for BPMN, CMMN, and DMN; Spring Boot starter; official Docker images and Helm charts for Kubernetes; web-based Flowable Modeler; comprehensive REST API; rich Java API for orchestrating human or automated processing . **Adoption**: ~5k stars on GitHub; active community . **Tech stack**: Java, Spring Boot. **Deploy**: Self-managed; Docker/Kubernetes ready; can run embedded, as a service, or in the cloud . **Trade-off**: **Smaller community than Camunda**; commercial Flowable Work UI is enterprise-licensed. **Best for**: development teams building cloud-native applications needing lightweight BPMN/CMMN/DMN orchestration with strong Spring Boot and Kubernetes support—especially teams migrating from Activiti .



- **[Bonita](https://github.com/bonitasoft/bonita-engine)**

  **Full BPM platform with low-code studio** (GPL-2.0 for Community) — **the most complete open-source BPM experience** for business analysts and developers who want a ready-made platform rather than an embeddable engine . **Features**: Visual process modeling (BPMN); form builder; task portal; runtime engine; UI designer; **"zero-coding approach"** with connectors for external system integration; complete API with documentation; ability to add custom connectors . **Tech stack**: Java. **Deploy**: Self-managed. **Trade-off**: **Community vs. Subscription feature boundaries**; heavier than pure engines; less cloud-native than Flowable . **Best for**: organizations wanting a complete BPM suite (modeling + execution + portals) where business analysts can own workflow design without deep coding—especially SMBs and mid-market teams that find Camunda too developer-centric .



- **[Activiti](https://github.com/Activiti/Activiti)**

  **Lightweight BPMN process engine** (Apache 2.0) — **the original fork ancestor of Flowable**, with a long history and stable community . **Features**: BPMN 2.0 execution; REST API; Spring integration; "super-fast and rock-solid" core; runs in any Java application, server, cluster, or cloud . **Adoption**: ~11k stars, ~7k forks . **Tech stack**: Java. **Deploy**: Self-managed. **Trade-off**: **Development momentum has slowed**—Activiti 7 is based on Spring Boot but cloud-native support is weaker than Camunda 8 or Flowable; DMN/CMMN support is incomplete . **Best for**: teams with existing Activiti deployments or Spring-centric applications needing a proven, simple BPMN engine—**not greenfield adoption** where Flowable is the better Activiti-lineage choice .



- **[Imixs-Workflow](https://github.com/imixs/imixs-workflow)**

  **Open-source BPM engine with no enterprise edition and no feature limits** (EPL 2.0) — **the most philosophically open BPM engine** in this list . **Features**: BPMN 2.0 process modeling; open interfaces with no vendor lock-in; runs under Eclipse Public License 2.0; **"There is no enterprise edition and no feature limit, and it is free to use in production"**; the vendor builds its own products on the same engine—**no better version kept for themselves** . **Tech stack**: Java. **Deploy**: Self-hosted. **Trade-off**: **Smaller community and ecosystem** than Camunda or Flowable; less documentation and fewer integrations. **Best for**: organizations that want a genuinely unrestricted open-source BPM engine with no commercial upsell—especially those building products on top of the engine and needing clear licensing.



- **[Joget](https://github.com/jogetworkflow/jw-community)**

  **Open-source AI Agentic Application Development Platform** (license per repo) — **the most low-code-oriented open-source option with emerging AI capabilities** . **Features**: Combines **low-code and no-code** development with AI agents; visual-first approach for business users and developers; workflow automation with human oversight; Generative AI and Agentic AI capabilities; plugin architecture for integration with legacy systems and APIs . **Tech stack**: Java. **Deploy**: Self-hosted. **Trade-off**: **"Not fully polished and some simple tasks still require extra coding"** per Gartner reviewers; not an out-of-the-box solution—requires configuration and development . **Best for**: SMEs wanting a lightweight low-code platform for workflow and data repository with emerging AI features—willing to accept rough edges for flexibility.



- **[ProcessMaker (Community)](https://github.com/processmaker/processmaker)**

  **Open-source BPM and workflow platform** (AGPL-3.0 for Community) — **the community edition of the commercial ProcessMaker** . **Features**: Process modeling; form builder; case management; REST API; self-hosted deployment. **Tech stack**: PHP (Laravel), Vue.js. **Deploy**: Self-managed (Docker available). **Trade-off**: **Community edition has no commercial support** ; commercial edition offers more features. **Best for**: teams wanting a PHP-based BPM platform with a visual designer and case management—accepting community-only support.



- **[django-workflow-kit](https://pypi.org/project/django-workflow-kit/)**

  **Workflow and approval engine for Django applications** (MIT) — **the most Django-native open-source workflow solution** for developers building approval workflows into existing applications . **Features**: Declarative workflow, state and transition definitions; **atomic, concurrency-safe transitions**; sequential, parallel, any-of and all-of approvals; **workflow versioning**—immutable numbered definitions that never silently change mid-flight; append-only audit trail and derived timelines; comments and file attachments; extensible conditions (never `eval`); pluggable notification providers (email, webhooks, Slack, Teams); **workflow dashboard** (server-rendered Django app); REST API via DRF; Prometheus metrics; CLI with dry-run simulation and diagnostics . **Tech stack**: Python (Django). **Deploy**: `pip install django-workflow-kit`; add to `INSTALLED_APPS` . **Trade-off**: **Django-specific**—not a standalone BPM platform; no visual BPMN modeler. Approval workflows are code-defined, not drag-and-drop. **Best for**: Django developers who need to add sophisticated approval workflows (invoices, leave requests, document reviews) to an existing application without building an engine from scratch or adopting a heavyweight BPM platform .



### Additional Strong Open-Source Options



- **Elsa Workflows** — .NET workflow engine (MIT). Cross-platform, plugin architecture, visual + code-defined workflows. **Note**: Strong for system integration and backend automation; **lacks native OA approval features** (no built-in task inbox, approval portal requires custom development) . **Best for**: .NET teams wanting a modern workflow engine for automation, not human approval workflows.

- **Slickflow** — .NET BPMN 2.0 engine. Standard BPMN implementation; supports countersign, or-sign, reject, add-sign. **Note**: Weak built-in form capabilities; lightweight logic still requires code . **Best for**: .NET teams needing BPMN-compliant human approval workflows.

- **jBPM / Apache KIE** — BPM suite with integrated rules engine (Apache 2.0). **Note**: Complex setup; migration to Apache KIE governance underway. **Best for**: processes where business rules and workflows are deeply intertwined.



**Frameworks for building custom systems**: Combine **CIB seven** for Camunda 7-compatible BPMN execution with **Flowable** for cloud-native microservice orchestration, **Bonita** for low-code business analyst workflows, and **django-workflow-kit** for Django-embedded approvals—creating a BPM stack matched to each team's technical depth and deployment context. **None of these match Nintex's SharePoint integration or ServiceNow's ITSM depth**, but for core process automation, the open-source engines are production-proven at enterprise scale.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Business process platforms handling process data and approvals must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for workflow information.

- **The "BPMN engine" vs. "low-code platform" vs. "embedded workflow library" vs. "checklist tool" distinction is critical.** **Camunda, CIB seven, Flowable, Activiti, and Imixs-Workflow** are **BPMN engines**—they execute standard process models but leave UI and business features to you . **Bonita and Joget** are **low-code platforms**—they provide modeling, forms, and portals out of the box . **django-workflow-kit** is an **embedded library**—it adds approval workflows to Django applications . **Kissflow, Pipefy, and Process Street** are **checklist/workflow SaaS**—simpler than BPMN engines. **Choose based on whether you need standards-based process execution, ready-made UI, or embedded approvals.**

- **Camunda 7 Community Edition is no longer supported by the manufacturer.** **CIB seven is the community fork providing guaranteed long-term maintenance** with 100% compatibility—a drop-in replacement without code changes . **If you are running Camunda 7, CIB seven is the responsible migration path** for teams that do not want to move to Camunda 8's Zeebe architecture and licensing.

- **Flowable is the strongest choice for new cloud-native BPM projects** on the Activiti lineage—Apache 2.0 licensed, active development, full BPMN/DMN/CMMN support, and Docker/Kubernetes ready . **It is the pragmatic middle path** between Camunda 8's power and Activiti's stagnation .

- **Bonita is the best open-source option for business analysts** who want to model processes visually and deploy without deep coding—the "zero-coding approach" with connectors makes it accessible . **The trade-off**: heavier platform, Community vs. Subscription boundaries.

- **django-workflow-kit is not a BPM platform**—it is the right tool for Django developers who need approval workflows (invoice sign-off, leave requests, document review) embedded in their application, with audit trails and versioning, without adopting a separate BPM system .

- **Pricing opacity varies.** Camunda publishes Community vs. Enterprise tiers. Kissflow publishes Basic pricing. Microsoft Power Automate publishes per-user pricing. Nintex, Pipefy, Process Street, ServiceNow, BP Logix, and Fluix require sales contact. **Validate with direct vendor conversations against your process complexity and user count.**

- Self-hosted open-source solutions require proper infrastructure (databases, Java runtimes, container orchestration), security hardening, and ongoing maintenance. **Process engines execute business-critical logic**—ensure your deployment meets your organization's reliability and security requirements before automating production processes.



---



**Made for developers, process engineers, and organizations building transparent workflow automation solutions.**

Let's make Business Process & Workflow Management more open, data-driven, and process-friendly.
