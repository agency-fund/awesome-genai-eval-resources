# Awesome GenAI Evaluation for the Social Sector [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated resources for building, stress-testing, and governing generative AI systems aimed at social impact, with a focus on transparent evaluation practices.

> See also The Agency Fund's [AI Evaluation in the Social Sector Playbook](eval.playbook.org.ai), and [updated slide deck] (https://agency-fund.github.io/taf-ai-eval-slides/#1) based on expert feedback.

## How to Use This List
- Navigate via the table of contents to find platforms, benchmarks, or governance resources.
- Each entry includes a short description so you can quickly triage relevance.
- Got a new resource? See the contributing section and open a PR.

## Table of Contents
- [Platforms & Tooling](#platforms--tooling)
- [Program Playbooks & Domain Decks](#program-playbooks--domain-decks)
- [Academic & Practitioner Insights](#academic--practitioner-insights)
- [Education Benchmarks](#education-benchmarks)
- [Health Benchmarks & Clinical Validation](#health-benchmarks--clinical-validation)
- [AI Safety, Monitoring & Governance](#ai-safety-monitoring--governance)
- [Red Teaming & Sandboxing](#red-teaming--sandboxing)
- [Ideas, Strategy & Frameworks](#ideas-strategy--frameworks)
- [Contributing](#contributing)

## Platforms & Tooling
- **[The MoOVE Collaboration Platform](https://jointhemoove.org/Collaboration)** – Health innovation workspace featuring “health goldens,” shared evaluation infrastructure, and data partnerships for global health implementers.
- **[MMORE RAG (Swiss-AI / Light Laboratory)](https://github.com/swiss-ai/mmoreRAG)** – Open-source Retrieval-Augmented Generation management framework tuned for clinical and health data contexts.
- **[Dimagi Chat Studio](https://www.dimagi.com/)** & **[Gooey.AI](https://www.gooey.ai/)** – Gates Foundation–aligned efforts to embed evaluation workflows directly into low-code AI builders, signaling demand for standardized evaluability tooling.
- **[Gmail reference thread: Gates discussions](https://mail.google.com/mail/u/0/?pli=1#inbox/FMfcgzQbgcRfFddvNpCwNSVvmtxsRVbf)** – Internal funding conversations around open-source evaluation infrastructure (requires authorized access).
- **[Google Model Cards Explorer](https://modelcards.withgoogle.com/explore-a-model-card)** – Repository of model-card templates that inform disclosure for ChatSEL or other social impact deployments.
- **[Product Cards (Agency Fund)](https://www.notion.so/Product-Cards-26a6311d558d80b69887d8ef3c898108)** – Notion-based templates covering purpose, data flows, metrics, risks, and evaluation plans for social tech products.
- **[HumanTruths.ai](https://humantruths.ai/)** – Benchmark initiative centering human values and perceptions; valuable for grounding LLM evaluations in culturally aware semantics.
- **[Google STAX](https://stax.withgoogle.com/landing/index.html)** – Stress-testing tool for probing LLM safety, robustness, and retrieval alignment.
- **[Intron Benchmarks](https://www.intron.io/#benchmarks)** – Voice, speech, and healthcare workflow benchmark suite for multimodal models.
- **[MERL Tech – AI Vendor Assessment Tool](https://merltech.org/resources/tool-for-assessing-ai-vendors/)** – Practical rubric that scores transparency, governance, and technical maturity of AI vendors servicing NGOs.
- **[OpenAI INDQA](https://openai.com/index/introducing-indqa/)** – Retrieval-augmented reasoning benchmark that tests domain grounding and evidence use.
- **[Athina AI](https://github.com/athina-ai)** – Evaluation infrastructure and monitoring pipelines purpose-built for generative AI workloads.

## Program Playbooks & Domain Decks
- **[Wadhwani Institute Overview Deck](https://docs.google.com/presentation/d/1e35vs6JrV-oTDiOTFSK7ZVdMBV9HbCMDt5yMUscYhF0/edit)** – High-level summaries of Wadhwani’s AI/ML solutions portfolio.
- **[Wadhwani TB Solutions Deck](https://docs.google.com/presentation/d/1E48HwDubF50rty_MhDqH6rnjkt0fcGlx/edit)** – Deep dive on tuberculosis diagnostic and adherence AI products.
- **[Wadhwani Anthropometry Solution Deck](https://docs.google.com/presentation/d/1kYvFRlvNxEvKBtsVoXY7JKiiiTs2tw6JQXtUEI1HBwU/edit)** – Image-based child anthropometrics estimation approach and evaluation plan.
- **[Wadhwani Oral Reading Fluency Deck](https://docs.google.com/presentation/d/1tqsih96YeENrkfjxCrGPX_ERaSC9L5ljmRDlsF-hGvM/edit)** – Machine learning audio assessments for literacy programs.
- **Related papers (Anthropometry, TB Cough, TB adherence)** – Foundational evaluation studies underpinning the above solutions; pair these with the decks for methodological context.

## Academic & Practitioner Insights
- **[Armman & Milind Tambe Group: AI for MCH Scheduling](https://arxiv.org/pdf/2507.20755)** – Optimizes maternal and child health messaging via contextual bandits and adaptive scheduling.
- **[Audere – “Misleading Metrics, Higher Bar”](https://www.auderenow.org/what-were-thinking-about/misleadingmetrics-higherbar)** – Calls out vanity metrics in global health AI and argues for rigorous evaluability standards.
- **[Bilal Mateen on Global Health LLMs](https://www.linkedin.com/posts/bilal-a-mateen-0bb88254_llm-digitalhealth-globalhealth-activity-7376235359954817024-IJgP)** – Practitioner reflections on adoption risks, data gaps, and evaluation needs.
- **[Ethan Goh – AI Agents in Healthcare](https://www.linkedin.com/posts/ethan-goh_ai-agents-in-healthcare-are-coming-epic-activity-7376631599523708929-vhPC)** – Early commentary on agentic workflows in clinical settings.
- **[BIT – AI & Human Behaviour Report](https://www.bi.team/publications/ai-and-human-behaviour/)** – Behavioral science framing for how AI alters human decision pathways.
- **[WEVAL](https://weval.org/)** – Participatory evaluation framework emphasizing equity-centered evidence collection.
- **[PAIR Guidebook: Mental Models & Expectations](https://pair.withgoogle.com/guidebook/chapters/mental-models-and-expectations)** – Toolkit for diagnosing mismatched user expectations in human–AI interactions.

## Education Benchmarks
- **[Tutors of Tomorrow Benchmark](https://mbzuai.ac.ae/news/tutors-of-tomorrow-a-new-benchmark-for-evaluating-llms/)** – Assesses tutoring quality, pedagogy, and instructional reasoning in LLMs.
- **[AI for Education Benchmarks](https://ai-for-education.org/ai-benchmarks-for-education/)** – Community-built evaluations for learning outcomes, instructional fidelity, and pedagogy alignment.
- **Assorted academic benchmarks** – Emerging research sets on student modeling, feedback quality, and reasoning: [2412.09416](https://arxiv.org/abs/2412.09416), [2507.22947](https://arxiv.org/abs/2507.22947), [2506.18710](https://arxiv.org/abs/2506.18710), [2406.03368](https://arxiv.org/abs/2406.03368), [2412.00948](https://arxiv.org/abs/2412.00948), [2402.09809](https://arxiv.org/abs/2402.09809), [2410.03017](https://arxiv.org/abs/2410.03017).

## Health Benchmarks & Clinical Validation
- **[Stress-testing AI in Healthcare](https://sarahgebauermd.substack.com/p/stress-testing-ai-before-it-touches)** – Clinical risk framework for LLM deployment readiness.
- **[Supplementary Materials on Health Model Validation](https://pmc.ncbi.nlm.nih.gov/articles/instance/12141433/bin/41746_2025_1732_MOESM1_ESM.pdf)** – Technical appendix detailing evaluation protocols.
- **arXiv health evaluation papers** – New methods for clinical reasoning & multimodal agents: [2509.24506](https://arxiv.org/abs/2509.24506), [2510.04033](https://arxiv.org/abs/2510.04033).
- **[mDoc (Nigeria)](https://www.mdocglobal.com/)** – Digital health coaching platform surfacing real-world behavior-change metrics for AI copilots.
- **[Hippocratic AI](https://www.hippocraticai.com/)** – Clinician-first LLM platform sharing licensure-aligned testing and safety protocols.

## AI Safety, Monitoring & Governance
- **[Microsoft Observability for GenAI](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/observability)** – Guidance on monitoring drift, safety events, and evaluation pipelines.
- **[Contextualised Intervention Best Practices](https://pmc.ncbi.nlm.nih.gov/articles/PMC7286860/)** – Evidence on tailoring digital interventions to local contexts; valuable when interpreting outcomes.
- **[CoPE-9B](https://huggingface.co/zentropi-ai/cope-a-9b)** – Open LLM tuned for lower hallucination rates, useful for calibration experiments.
- **[Cove](https://getcove.com/)** – AI governance and compliance automation platform for policy-heavy orgs.
- **[Variance](https://www.variance.co/)** – Enterprise-grade evaluation and monitoring workflows for LLM-integrated products.
- **[Berkeley RDI Responsible GenAI Curriculum](https://rdi.berkeley.edu/responsible-genai/f23)** – Open curriculum covering responsible AI processes end-to-end.
- **[arXiv Safety Research (2505.08245)](https://arxiv.org/abs/2505.08245)** – Methods for detecting unsafe behaviors and adversarial susceptibility.
- **[Human Intelligence](https://humane-intelligence.org/)** – Community-driven ecosystem for responsible AI auditing and evaluation.
- **OpenAI & Anthropic system cards** – Transparency exemplars for disclosure requirements: [GPT-4o](https://cdn.openai.com/gpt-4o-system-card.pdf), [Claude 4.5 Sonnet](https://assets.anthropic.com/m/12f214efcc2f457a/original/Claude-Sonnet-4-5-System-Card.pdf).

## Red Teaming & Sandboxing
- **[Humane Intelligence Red-Teaming App](https://humane-intelligence.org/product/red-teaming-app/)** – Structured elicitation workflow for adversarial prompts and harm surfacing.
- **[Google Red Team Guide](https://drive.google.com/file/d/14AKKZ57AyrxtW3t1sPhoKsM1o5Km4Tui/view)** – Step-by-step methodology for adversarial probing of AI systems.
- **[Microsoft Red Teaming Documentation](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/red-teaming)** – Operational playbooks for scenario-driven stress tests.
- **[UK AISI Sandboxing Framework](https://github.com/UKGovernmentBEIS/aisi-sandboxing)** – Policy-compliant sandbox toolkit for testing AI systems under safe oversight.

## Ideas, Strategy & Frameworks
- **Strategic directions from Richard** – Model evaluation: explore large context windows & contextual bandits for personalization; User evaluation: embed validated self-efficacy scales plus behavioral indices; Impact evaluation: expand real-world outcomes datasets beyond MPESA to capture AI-induced change.
- **[Social Impact Frameworks Booklet](https://elgonsocial.wordpress.com/wp-content/uploads/2025/03/frameworksbooklet_v2.pdf)** – Digest of social intervention frameworks useful for scoping AI impact pathways.
- **[EJSP Article on Human Agency & Behavior](https://onlinelibrary.wiley.com/doi/full/10.1002/ejsp.2561)** – Scholarship on agency, motivation, and social behavior to inform Level 3/4 evaluations.

## Contributing
Seen a gap or have a favorite resource to add? Open an issue or PR with:
1. Resource name, link, and 1–2 sentence description.
2. Recommended section (or suggest a new one).
3. Any notes on licensing or access requirements.