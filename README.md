# Awesome Automation for Knowledge Work

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of patterns, case studies, capabilities, and tools for automating knowledge work.

This list is **not** a generic AI tools directory, a workflow-engine catalog, or a PKM app collection.

It is organized around recurring work patterns such as **ingest**, **triage**, **summarize**, **retrieve**, **review**, **deliver**, and **audit**.

The goal is to help people design automation systems that are useful, legible, and durable, with explicit attention to human review, provenance, and evidence-bearing outputs.

## Contents

- [Scope](#scope)
- [How to Use This List](#how-to-use-this-list)
- [Landscape and Adjacent Lists](#landscape-and-adjacent-lists)
- [Patterns](#patterns)
  - [Ingest](#ingest)
  - [Triage, Classify, Route](#triage-classify-route)
  - [Summarize, Digest, Condense](#summarize-digest-condense)
  - [Retrieve and Remember](#retrieve-and-remember)
  - [Review and Human-in-the-Loop](#review-and-human-in-the-loop)
  - [Deliver, Materialize, Handoff](#deliver-materialize-handoff)
  - [Audit and Provenance](#audit-and-provenance)
- [Case Studies](#case-studies)
- [Supporting Capabilities](#supporting-capabilities)
- [Tool Families](#tool-families)
- [Discovery Surfaces](#discovery-surfaces)
- [Further Reading and Neighboring Spaces](#further-reading-and-neighboring-spaces)
- [Contributing](#contributing)

## Scope

Included here:

- pattern-first resources
- workflow examples with visible inputs and outputs
- case studies with real operational problems
- capability references that support knowledge-work automation
- tool families that matter because they support recurring patterns

Usually excluded here:

- generic AI tools directories
- giant template dumps without conceptual framing
- workflow engines with no obvious knowledge-work relevance
- broad PKM catalogs unless they add a strong conceptual angle
- agent lists that optimize for hype rather than clarity

## How to Use This List

You can read this list in three passes:

1. **Patterns** to understand the recurring anatomy of knowledge-work automation.
2. **Case studies** to see what those patterns look like in practice.
3. **Capabilities and tools** to understand what makes the patterns work.

## Landscape and Adjacent Lists

These are useful neighboring resources, benchmarks, or contrast cases.

### Direct neighbors

* [dariubs/awesome-workflow-automation](https://github.com/dariubs/awesome-workflow-automation) [![Stars](https://img.shields.io/github/stars/dariubs/awesome-workflow-automation.svg)](https://github.com/dariubs/awesome-workflow-automation) - Broad list of workflow automation tools, platforms, frameworks, and resources.
* [meirwah/awesome-workflow-engines](https://github.com/meirwah/awesome-workflow-engines) [![Stars](https://img.shields.io/github/stars/meirwah/awesome-workflow-engines.svg)](https://github.com/meirwah/awesome-workflow-engines) - Canonical list of workflow engines.
* [bentsherman/awesome-workflow](https://github.com/bentsherman/awesome-workflow) [![Stars](https://img.shields.io/github/stars/bentsherman/awesome-workflow.svg)](https://github.com/bentsherman/awesome-workflow) - Curated list of workflow systems across domains.
* [githubnext/awesome-continuous-ai](https://github.com/githubnext/awesome-continuous-ai) [![Stars](https://img.shields.io/github/stars/githubnext/awesome-continuous-ai.svg)](https://github.com/githubnext/awesome-continuous-ai) - Continuous AI actions and frameworks for collaborative workflows.
* [PixelCove/awesome-ai-automation](https://github.com/PixelCove/awesome-ai-automation) [![Stars](https://img.shields.io/github/stars/PixelCove/awesome-ai-automation.svg)](https://github.com/PixelCove/awesome-ai-automation) - AI automation resources with a more tool-centric flavor.

### Template-heavy and ecosystem-heavy neighbors

* [enescingoz/awesome-n8n-templates](https://github.com/enescingoz/awesome-n8n-templates) [![Stars](https://img.shields.io/github/stars/enescingoz/awesome-n8n-templates.svg)](https://github.com/enescingoz/awesome-n8n-templates) - Large collection of n8n templates.
* [skadaai/awesome-n8n-templates](https://github.com/skadaai/awesome-n8n-templates) [![Stars](https://img.shields.io/github/stars/skadaai/awesome-n8n-templates.svg)](https://github.com/skadaai/awesome-n8n-templates) - Another n8n-template collection, narrower and more agency-oriented.

### Knowledge management and PKM neighbors

* [brettkromkamp/awesome-knowledge-management](https://github.com/brettkromkamp/awesome-knowledge-management) [![Stars](https://img.shields.io/github/stars/brettkromkamp/awesome-knowledge-management.svg)](https://github.com/brettkromkamp/awesome-knowledge-management) - Large knowledge-management list.
* [knowfox/awesome-pkm](https://github.com/knowfox/awesome-pkm) [![Stars](https://img.shields.io/github/stars/knowfox/awesome-pkm.svg)](https://github.com/knowfox/awesome-pkm) - Tools and resources for personal knowledge management.
* [doanhthong/awesome-pkm](https://github.com/doanhthong/awesome-pkm) [![Stars](https://img.shields.io/github/stars/doanhthong/awesome-pkm.svg)](https://github.com/doanhthong/awesome-pkm) - PKM and note-taking tools.
* [githubkusi/awesome-knowledge-management-tools](https://github.com/githubkusi/awesome-knowledge-management-tools) [![Stars](https://img.shields.io/github/stars/githubkusi/awesome-knowledge-management-tools.svg)](https://github.com/githubkusi/awesome-knowledge-management-tools) - Collaborative KM software comparison.
* [sn3akiwhizper-pkms/awesome-foam](https://github.com/sn3akiwhizper-pkms/awesome-foam) [![Stars](https://img.shields.io/github/stars/sn3akiwhizper-pkms/awesome-foam.svg)](https://github.com/sn3akiwhizper-pkms/awesome-foam) - PKMS theory and principles around Foam.

### Broad AI directories to treat cautiously

* [mahseema/awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) [![Stars](https://img.shields.io/github/stars/mahseema/awesome-ai-tools.svg)](https://github.com/mahseema/awesome-ai-tools) - Broad AI tools list.
* [ai-tools-inc/awesome-ai-tools](https://github.com/ai-tools-inc/awesome-ai-tools) [![Stars](https://img.shields.io/github/stars/ai-tools-inc/awesome-ai-tools.svg)](https://github.com/ai-tools-inc/awesome-ai-tools) - Broad AI tools and productivity list.
* [openbestof/awesome-ai](https://github.com/openbestof/awesome-ai) [![Stars](https://img.shields.io/github/stars/openbestof/awesome-ai.svg)](https://github.com/openbestof/awesome-ai) - Large AI curation surface.
* [Arindam200/awesome-ai-apps](https://github.com/Arindam200/awesome-ai-apps) [![Stars](https://img.shields.io/github/stars/Arindam200/awesome-ai-apps.svg)](https://github.com/Arindam200/awesome-ai-apps) - LLM-powered applications and tutorials.
* [caramaschiHG/awesome-ai-agents-2026](https://github.com/caramaschiHG/awesome-ai-agents-2026) [![Stars](https://img.shields.io/github/stars/caramaschiHG/awesome-ai-agents-2026.svg)](https://github.com/caramaschiHG/awesome-ai-agents-2026) - Broad AI agent landscape.

## Patterns

### Ingest

Turn raw material into machine-usable records, chunks, or searchable assets.

* [dvictor357/docs-ingester](https://github.com/dvictor357/docs-ingester) [![Stars](https://img.shields.io/github/stars/dvictor357/docs-ingester.svg)](https://github.com/dvictor357/docs-ingester) - Document upload, OCR, structuring, and searchable knowledge-base ingestion.
* [aws-ia/terraform-aws-genai-document-ingestion-rag](https://github.com/aws-ia/terraform-aws-genai-document-ingestion-rag) [![Stars](https://img.shields.io/github/stars/aws-ia/terraform-aws-genai-document-ingestion-rag.svg)](https://github.com/aws-ia/terraform-aws-genai-document-ingestion-rag) - Enterprise-oriented document ingestion stack.
* [imuchnik/knowledge-base](https://github.com/imuchnik/knowledge-base) [![Stars](https://img.shields.io/github/stars/imuchnik/knowledge-base.svg)](https://github.com/imuchnik/knowledge-base) - Searchable document-management knowledge base with vector search.
* [rikusato0/AI-Powered-Knowledge-Base-Search---Enrichment](https://github.com/rikusato0/AI-Powered-Knowledge-Base-Search---Enrichment) [![Stars](https://img.shields.io/github/stars/rikusato0/AI-Powered-Knowledge-Base-Search---Enrichment.svg)](https://github.com/rikusato0/AI-Powered-Knowledge-Base-Search---Enrichment) - Prototype for ingestion, search, and enrichment.
* [infiniflow/ragflow](https://github.com/infiniflow/ragflow) [![Stars](https://img.shields.io/github/stars/infiniflow/ragflow.svg)](https://github.com/infiniflow/ragflow) - Broad RAG workflow system, more platform-like than canonical, but relevant as infrastructure context.

### Triage, Classify, Route

Classify incoming work and decide what should happen next.

* [stonefullstm/ai-email-triage](https://github.com/stonefullstm/ai-email-triage) [![Stars](https://img.shields.io/github/stars/stonefullstm/ai-email-triage.svg)](https://github.com/stonefullstm/ai-email-triage) - AI-powered email triage using heuristics, embeddings, and LLMs.
* [ericporres/email-triage-plugin](https://github.com/ericporres/email-triage-plugin) [![Stars](https://img.shields.io/github/stars/ericporres/email-triage-plugin.svg)](https://github.com/ericporres/email-triage-plugin) - Email classification, alias-aware routing, reply drafting, and archive management.
* [MatheusDSantossi/n8n-email-priority-agent](https://github.com/MatheusDSantossi/n8n-email-priority-agent) [![Stars](https://img.shields.io/github/stars/MatheusDSantossi/n8n-email-priority-agent.svg)](https://github.com/MatheusDSantossi/n8n-email-priority-agent) - Priority-based email categorization and actions.
* [LuiseFreese/espc25-smart-support-agent](https://github.com/LuiseFreese/espc25-smart-support-agent) [![Stars](https://img.shields.io/github/stars/LuiseFreese/espc25-smart-support-agent.svg)](https://github.com/LuiseFreese/espc25-smart-support-agent) - Support-email triage and routing.
* [dottxt-ai/outlines](https://github.com/dottxt-ai/outlines) [![Stars](https://img.shields.io/github/stars/dottxt-ai/outlines.svg)](https://github.com/dottxt-ai/outlines) - Structured outputs library that helps turn messy inputs into typed downstream decisions.
* [Stevenshanmukh/n8n-ai-automation](https://github.com/Stevenshanmukh/n8n-ai-automation) [![Stars](https://img.shields.io/github/stars/Stevenshanmukh/n8n-ai-automation.svg)](https://github.com/Stevenshanmukh/n8n-ai-automation) - Workflow examples including support routing with structured output.
* [m-saad125/n8n-email-ai-agent](https://github.com/m-saad125/n8n-email-ai-agent) [![Stars](https://img.shields.io/github/stars/m-saad125/n8n-email-ai-agent.svg)](https://github.com/m-saad125/n8n-email-ai-agent) - Email classification, labeling, and AI draft generation with review.
* [copyleftdev/mailsentinel](https://github.com/copyleftdev/mailsentinel) [![Stars](https://img.shields.io/github/stars/copyleftdev/mailsentinel.svg)](https://github.com/copyleftdev/mailsentinel) - Privacy-first Gmail classification with local inference.

### Summarize, Digest, Condense

Reduce information volume while preserving useful signal.

* [AbdoulayeDiop/my-research-digest](https://github.com/AbdoulayeDiop/my-research-digest) [![Stars](https://img.shields.io/github/stars/AbdoulayeDiop/my-research-digest.svg)](https://github.com/AbdoulayeDiop/my-research-digest) - Finds relevant papers, analyzes them, and delivers a curated digest.
* [DoubtfulPrism/research-digest-toolkit](https://github.com/DoubtfulPrism/research-digest-toolkit) [![Stars](https://img.shields.io/github/stars/DoubtfulPrism/research-digest-toolkit.svg)](https://github.com/DoubtfulPrism/research-digest-toolkit) - Weekly automated digest with raw outputs, notes, and report artifacts.
* [realikechukwu/cardiology-feed](https://github.com/realikechukwu/cardiology-feed) [![Stars](https://img.shields.io/github/stars/realikechukwu/cardiology-feed.svg)](https://github.com/realikechukwu/cardiology-feed) - End-to-end monitored reading workflow with filtering, classification, summaries, dedupe, and email delivery.
* [junshi-research/research-junshi](https://github.com/junshi-research/research-junshi) [![Stars](https://img.shields.io/github/stars/junshi-research/research-junshi.svg)](https://github.com/junshi-research/research-junshi) - Claude Code skill for recurring research digests.
* [ruslanmv/news-and-trends](https://github.com/ruslanmv/news-and-trends) [![Stars](https://img.shields.io/github/stars/ruslanmv/news-and-trends.svg)](https://github.com/ruslanmv/news-and-trends) - Retrieve, normalize, summarize, score, and materialize trend outputs.
* [Tavish9/awesome-daily-AI-arxiv](https://github.com/Tavish9/awesome-daily-AI-arxiv) [![Stars](https://img.shields.io/github/stars/Tavish9/awesome-daily-AI-arxiv.svg)](https://github.com/Tavish9/awesome-daily-AI-arxiv) - Public-facing AI research digest.
* [AadarshMoudgil/Meeting-Notes-Summarizer-LLM-Automation-](https://github.com/AadarshMoudgil/Meeting-Notes-Summarizer-LLM-Automation-) [![Stars](https://img.shields.io/github/stars/AadarshMoudgil/Meeting-Notes-Summarizer-LLM-Automation-.svg)](https://github.com/AadarshMoudgil/Meeting-Notes-Summarizer-LLM-Automation-) - Long meeting transcript summarization into key points, decisions, and action items.
* [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) [![Stars](https://img.shields.io/github/stars/Zackriya-Solutions/meetily.svg)](https://github.com/Zackriya-Solutions/meetily) - Privacy-first meeting assistant for capture, transcription, and summarization.

### Retrieve and Remember

Make stored knowledge searchable, reusable, and inspectable.

* [imuchnik/knowledge-base](https://github.com/imuchnik/knowledge-base) [![Stars](https://img.shields.io/github/stars/imuchnik/knowledge-base.svg)](https://github.com/imuchnik/knowledge-base) - Searchable memory store with document-management focus.
* [intelav/autonomous-local-research-agent](https://github.com/intelav/autonomous-local-research-agent) [![Stars](https://img.shields.io/github/stars/intelav/autonomous-local-research-agent.svg)](https://github.com/intelav/autonomous-local-research-agent) - Local-first retrieval over ingested research papers.
* [directtt/rag-with-knowledge-base-management](https://github.com/directtt/rag-with-knowledge-base-management) [![Stars](https://img.shields.io/github/stars/directtt/rag-with-knowledge-base-management.svg)](https://github.com/directtt/rag-with-knowledge-base-management) - RAG plus explicit document-management operations.
* [TensorBlock/awesome-mcp-servers](https://github.com/TensorBlock/awesome-mcp-servers) [![Stars](https://img.shields.io/github/stars/TensorBlock/awesome-mcp-servers.svg)](https://github.com/TensorBlock/awesome-mcp-servers) - Ecosystem surface including knowledge-management and memory-oriented MCP servers.
* [mbhatt1/maif](https://github.com/mbhatt1/maif) [![Stars](https://img.shields.io/github/stars/mbhatt1/maif.svg)](https://github.com/mbhatt1/maif) - Trustworthy memory format and SDK with tamper-evident audit trails.

### Review and Human-in-the-Loop

Insert explicit approval, correction, or oversight before downstream action.

* [aws-samples/review-and-assessment-powered-by-intelligent-documentation](https://github.com/aws-samples/review-and-assessment-powered-by-intelligent-documentation) [![Stars](https://img.shields.io/github/stars/aws-samples/review-and-assessment-powered-by-intelligent-documentation.svg)](https://github.com/aws-samples/review-and-assessment-powered-by-intelligent-documentation) - AI-assisted review centered on final human judgment.
* [aws-samples/aws-ai-intelligent-document-processing](https://github.com/aws-samples/aws-ai-intelligent-document-processing) [![Stars](https://img.shields.io/github/stars/aws-samples/aws-ai-intelligent-document-processing.svg)](https://github.com/aws-samples/aws-ai-intelligent-document-processing) - Document classification, extraction, enrichment, and HITL review.
* [aws-samples/sample-scalable-intelligent-document-processing-with-amazon-bedrock-data-automation](https://github.com/aws-samples/sample-scalable-intelligent-document-processing-with-amazon-bedrock-data-automation) [![Stars](https://img.shields.io/github/stars/aws-samples/sample-scalable-intelligent-document-processing-with-amazon-bedrock-data-automation.svg)](https://github.com/aws-samples/sample-scalable-intelligent-document-processing-with-amazon-bedrock-data-automation) - Scalable document processing with human review.
* [Yevanchen/human-in-the-loop-in-dify](https://github.com/Yevanchen/human-in-the-loop-in-dify) [![Stars](https://img.shields.io/github/stars/Yevanchen/human-in-the-loop-in-dify.svg)](https://github.com/Yevanchen/human-in-the-loop-in-dify) - Asynchronous human review in Dify workflows.
* [cimulink/ai-workflow-engine](https://github.com/cimulink/ai-workflow-engine) [![Stars](https://img.shields.io/github/stars/cimulink/ai-workflow-engine.svg)](https://github.com/cimulink/ai-workflow-engine) - Stateful workflows with human-in-the-loop support.
* [GongRzhe/Human-In-the-Loop-MCP-Server](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) [![Stars](https://img.shields.io/github/stars/GongRzhe/Human-In-the-Loop-MCP-Server.svg)](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) - Human approval and feedback layer for AI processes.
* [Flowise human-in-the-loop tutorial](https://github.com/FlowiseAI/FlowiseDocs/blob/main/en/tutorials/human-in-the-loop.md) - Tutorial framing HITL as a control layer rather than a niche feature.
* [Azure sample: add a human in the loop to workflows](https://github.com/Azure-Samples/python-agentframework-demos/blob/main/presentations/english/session-6/README.md) - Educational walkthrough for approval checkpoints in workflows.

### Deliver, Materialize, Handoff

Push outputs into the next place where work happens.

* [Automated Meeting Notes & Action Items](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/meeting-notes-action-items.md) - Transcript to notes to tasks in Jira, Linear, or Todoist.
* [ndourc/founder-os](https://github.com/ndourc/founder-os) [![Stars](https://img.shields.io/github/stars/ndourc/founder-os.svg)](https://github.com/ndourc/founder-os) - Turns raw meeting notes into structured Projects, Meetings, and Tasks in Notion.
* [sgharlow/claude-code-recipes: Meeting Notes to Action Items](https://github.com/sgharlow/claude-code-recipes/blob/main/recipes/Recipe-001-Meeting-Notes-to-Action-Items.md) - Recipe-shaped pattern for summarize-plus-action handoff.
* [realikechukwu/cardiology-feed](https://github.com/realikechukwu/cardiology-feed) [![Stars](https://img.shields.io/github/stars/realikechukwu/cardiology-feed.svg)](https://github.com/realikechukwu/cardiology-feed) - Digest delivery through email.
* [AbdoulayeDiop/my-research-digest](https://github.com/AbdoulayeDiop/my-research-digest) [![Stars](https://img.shields.io/github/stars/AbdoulayeDiop/my-research-digest.svg)](https://github.com/AbdoulayeDiop/my-research-digest) - Curated research output delivery.
* [ruslanmv/news-and-trends](https://github.com/ruslanmv/news-and-trends) [![Stars](https://img.shields.io/github/stars/ruslanmv/news-and-trends.svg)](https://github.com/ruslanmv/news-and-trends) - Materializes structured JSON artifacts by date.

### Audit and Provenance

Keep evidence about what happened, where it came from, and how it changed.

* [mbhatt1/maif](https://github.com/mbhatt1/maif) [![Stars](https://img.shields.io/github/stars/mbhatt1/maif.svg)](https://github.com/mbhatt1/maif) - Memory with cryptographic links and tamper-evident audit trails.
* [GitHub Docs: artifact attestations](https://docs.github.com/actions/security-for-github-actions/using-artifact-attestations/using-artifact-attestations-to-establish-provenance-for-builds) - Strong concept reference for provenance-bearing artifacts.
* [tfjmp/provenance-papers](https://github.com/tfjmp/provenance-papers) [![Stars](https://img.shields.io/github/stars/tfjmp/provenance-papers.svg)](https://github.com/tfjmp/provenance-papers) - Bibliography on provenance and auditing.
* [GitHub topic: data-provenance](https://github.com/topics/data-provenance?o=asc&s=forks) - Discovery surface for provenance-oriented systems.

## Case Studies

### Meeting workflows

* [Automated Meeting Notes & Action Items](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/meeting-notes-action-items.md) - Compact exemplar of transcript to summary to tasks.
* [ndourc/founder-os](https://github.com/ndourc/founder-os) [![Stars](https://img.shields.io/github/stars/ndourc/founder-os.svg)](https://github.com/ndourc/founder-os) - Meeting notes into structured operational objects.
* [AadarshMoudgil/Meeting-Notes-Summarizer-LLM-Automation-](https://github.com/AadarshMoudgil/Meeting-Notes-Summarizer-LLM-Automation-) [![Stars](https://img.shields.io/github/stars/AadarshMoudgil/Meeting-Notes-Summarizer-LLM-Automation-.svg)](https://github.com/AadarshMoudgil/Meeting-Notes-Summarizer-LLM-Automation-) - Lighter implementation example.
* [Zero Missed Actions With AI Meeting Notes](https://nexustechconsulting.com.au/case-studies/meeting-notes-to-action-items.html) - Real-world consulting case study.

### Email workflows

* [stonefullstm/ai-email-triage](https://github.com/stonefullstm/ai-email-triage) [![Stars](https://img.shields.io/github/stars/stonefullstm/ai-email-triage.svg)](https://github.com/stonefullstm/ai-email-triage) - Email triage as a recurring work-unit pattern.
* [ericporres/email-triage-plugin](https://github.com/ericporres/email-triage-plugin) [![Stars](https://img.shields.io/github/stars/ericporres/email-triage-plugin.svg)](https://github.com/ericporres/email-triage-plugin) - Classification and downstream action.
* [MatheusDSantossi/n8n-email-priority-agent](https://github.com/MatheusDSantossi/n8n-email-priority-agent) [![Stars](https://img.shields.io/github/stars/MatheusDSantossi/n8n-email-priority-agent.svg)](https://github.com/MatheusDSantossi/n8n-email-priority-agent) - Implementation-oriented routing example.
* [m-saad125/n8n-email-ai-agent](https://github.com/m-saad125/n8n-email-ai-agent) [![Stars](https://img.shields.io/github/stars/m-saad125/n8n-email-ai-agent.svg)](https://github.com/m-saad125/n8n-email-ai-agent) - AI draft generation with review.
* [copyleftdev/mailsentinel](https://github.com/copyleftdev/mailsentinel) [![Stars](https://img.shields.io/github/stars/copyleftdev/mailsentinel.svg)](https://github.com/copyleftdev/mailsentinel) - Privacy-first local email classification.
* [ZenML: automated email triage system using Amazon Bedrock Flows](https://www.zenml.io/llmops-database/automated-email-triage-system-using-amazon-bedrock-flows) - Framing of email triage as a production problem.

### Research and monitored reading workflows

* [DoubtfulPrism/research-digest-toolkit](https://github.com/DoubtfulPrism/research-digest-toolkit) [![Stars](https://img.shields.io/github/stars/DoubtfulPrism/research-digest-toolkit.svg)](https://github.com/DoubtfulPrism/research-digest-toolkit) - Strong artifact-oriented digest workflow.
* [AbdoulayeDiop/my-research-digest](https://github.com/AbdoulayeDiop/my-research-digest) [![Stars](https://img.shields.io/github/stars/AbdoulayeDiop/my-research-digest.svg)](https://github.com/AbdoulayeDiop/my-research-digest) - End-to-end digest pipeline.
* [realikechukwu/cardiology-feed](https://github.com/realikechukwu/cardiology-feed) [![Stars](https://img.shields.io/github/stars/realikechukwu/cardiology-feed.svg)](https://github.com/realikechukwu/cardiology-feed) - Filter, classify, summarize, dedupe, deliver.
* [junshi-research/research-junshi](https://github.com/junshi-research/research-junshi) [![Stars](https://img.shields.io/github/stars/junshi-research/research-junshi.svg)](https://github.com/junshi-research/research-junshi) - Agent-environment-specific recurring research pipeline.
* [Tavish9/awesome-daily-AI-arxiv](https://github.com/Tavish9/awesome-daily-AI-arxiv) [![Stars](https://img.shields.io/github/stars/Tavish9/awesome-daily-AI-arxiv.svg)](https://github.com/Tavish9/awesome-daily-AI-arxiv) - Public digest surface.
* [Doubleword: research summaries](https://docs.doubleword.ai/inference-api/research-summaries) - Guide for automated research summary generation.
* [Towards AI: from arXiv to your inbox](https://pub.towardsai.net/building-a-free-ai-research-digest-from-arxiv-to-your-inbox-using-llama-3-1-groq-and-sendgrid-5fc92ba6a819) - Ranking plus summarization plus newsletter delivery.

### Review-centric workflows

* [aws-samples/review-and-assessment-powered-by-intelligent-documentation](https://github.com/aws-samples/review-and-assessment-powered-by-intelligent-documentation) [![Stars](https://img.shields.io/github/stars/aws-samples/review-and-assessment-powered-by-intelligent-documentation.svg)](https://github.com/aws-samples/review-and-assessment-powered-by-intelligent-documentation) - Review-oriented, not autonomy-oriented.
* [AWS human-in-the-loop review docs](https://github.com/aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws/blob/main/docs/human-review.md) - Clear reusable review-loop statement.
* [Flowise human-in-the-loop tutorial](https://github.com/FlowiseAI/FlowiseDocs/blob/main/en/tutorials/human-in-the-loop.md) - HITL as a control layer.
* [GongRzhe/Human-In-the-Loop-MCP-Server](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) [![Stars](https://img.shields.io/github/stars/GongRzhe/Human-In-the-Loop-MCP-Server.svg)](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) - Approval and human dialog in AI processes.

## Supporting Capabilities

### OCR and extraction

* [machinelearnear/amazon-textract-workbench](https://github.com/machinelearnear/amazon-textract-workbench) [![Stars](https://img.shields.io/github/stars/machinelearnear/amazon-textract-workbench.svg)](https://github.com/machinelearnear/amazon-textract-workbench) - OCR plus forms and tables extraction.
* [yobix-ai/extractous](https://github.com/yobix-ai/extractous) [![Stars](https://img.shields.io/github/stars/yobix-ai/extractous.svg)](https://github.com/yobix-ai/extractous) - Unstructured extraction, metadata extraction, and OCR support.
* [aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws](https://github.com/aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws) [![Stars](https://img.shields.io/github/stars/aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws.svg)](https://github.com/aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws) - OCR, extraction, and review as one capability bundle.

### Parsing and structuring

* [Unstructured-IO/unstructured](https://github.com/Unstructured-IO/unstructured) [![Stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured.svg)](https://github.com/Unstructured-IO/unstructured) - Foundational parsing layer for complex documents.
* [Unstructured-IO](https://github.com/Unstructured-IO) - Broader ecosystem for turning documents into structured formats.
* [Unstructured-IO/unstructured-eval-metrics](https://github.com/Unstructured-IO/unstructured-eval-metrics) [![Stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured-eval-metrics.svg)](https://github.com/Unstructured-IO/unstructured-eval-metrics) - Evaluation layer for parsing quality.

### Semantic indexing and retrieval

* [qdrant/qdrant](https://github.com/qdrant/qdrant) [![Stars](https://img.shields.io/github/stars/qdrant/qdrant.svg)](https://github.com/qdrant/qdrant) - Semantic search backbone.
* [OpenAI Cookbook: Using Qdrant for embeddings search](https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/qdrant/Using_Qdrant_for_embeddings_search.ipynb) - Direct walkthrough of embed, index, and search.
* [qdrant/examples](https://github.com/qdrant/examples) [![Stars](https://img.shields.io/github/stars/qdrant/examples.svg)](https://github.com/qdrant/examples) - Tutorials and demos.
* [qdrant/qdrant_demo](https://github.com/qdrant/qdrant_demo) [![Stars](https://img.shields.io/github/stars/qdrant/qdrant_demo.svg)](https://github.com/qdrant/qdrant_demo) - Vector search plus filters and text-search seams.
* [Hawksight-AI/semantica](https://github.com/Hawksight-AI/semantica) [![Stars](https://img.shields.io/github/stars/Hawksight-AI/semantica.svg)](https://github.com/Hawksight-AI/semantica) - Emerging semantic layer with provenance and explainability ambitions.

### Scheduling and orchestration

* [GitHub Docs: getting started with GitHub Actions](https://docs.github.com/articles/getting-started-with-github-actions) - Baseline orchestration substrate for recurring workflows.
* [Schedule Workflow action](https://github.com/marketplace/actions/schedule-workflow) - Scheduled workflow execution on GitHub.
* [schedule-job-action](https://github.com/marketplace/actions/schedule-job-action) - Another scheduling layer for GitHub Actions.
* [runjtu/vpr-arxiv-daily](https://github.com/runjtu/vpr-arxiv-daily) [![Stars](https://img.shields.io/github/stars/runjtu/vpr-arxiv-daily.svg)](https://github.com/runjtu/vpr-arxiv-daily) - Example of scheduled recurring content production.

### Review and control

* [aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws](https://github.com/aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws) [![Stars](https://img.shields.io/github/stars/aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws.svg)](https://github.com/aws-solutions-library-samples/accelerated-intelligent-document-processing-on-aws) - Review as a first-class control loop.
* [Flowise human-in-the-loop tutorial](https://github.com/FlowiseAI/FlowiseDocs/blob/main/en/tutorials/human-in-the-loop.md) - HITL concept and implementation guidance.
* [GongRzhe/Human-In-the-Loop-MCP-Server](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) [![Stars](https://img.shields.io/github/stars/GongRzhe/Human-In-the-Loop-MCP-Server.svg)](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) - Approval and checkpoint patterns.

### Provenance and auditability

* [mbhatt1/maif](https://github.com/mbhatt1/maif) [![Stars](https://img.shields.io/github/stars/mbhatt1/maif.svg)](https://github.com/mbhatt1/maif) - Trustworthy memory and tamper-evident records.
* [GitHub Docs: artifact attestations](https://docs.github.com/actions/security-for-github-actions/using-artifact-attestations/using-artifact-attestations-to-establish-provenance-for-builds) - Provenance-bearing artifact pattern.
* [tfjmp/provenance-papers](https://github.com/tfjmp/provenance-papers) [![Stars](https://img.shields.io/github/stars/tfjmp/provenance-papers.svg)](https://github.com/tfjmp/provenance-papers) - Research bibliography on provenance.
* [GitHub topic: data-provenance](https://github.com/topics/data-provenance?o=asc&s=forks) - Discovery surface for provenance systems.

## Tool Families

These are listed as families, not as a shopping catalog.

### Workflow orchestrators

* [n8n-io/n8n](https://github.com/n8n-io/n8n) [![Stars](https://img.shields.io/github/stars/n8n-io/n8n.svg)](https://github.com/n8n-io/n8n) - The most visible integration-heavy workflow orchestrator in this space.
* [nusquama/n8nworkflows.xyz](https://github.com/nusquama/n8nworkflows.xyz) [![Stars](https://img.shields.io/github/stars/nusquama/n8nworkflows.xyz.svg)](https://github.com/nusquama/n8nworkflows.xyz) - Discovery surface for n8n workflows.
* [activepieces/activepieces](https://github.com/activepieces/activepieces) [![Stars](https://img.shields.io/github/stars/activepieces/activepieces.svg)](https://github.com/activepieces/activepieces) - Open-source no-code business automation platform.
* [Zapier](https://zapier.com/) - Hosted automation platform with huge integration reach.
* [Make](https://www.make.com/) - Hosted workflow builder and automation platform.

### Document parsing and extraction

* [Unstructured-IO/unstructured](https://github.com/Unstructured-IO/unstructured) [![Stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured.svg)](https://github.com/Unstructured-IO/unstructured) - Parse documents into useful structured elements.
* [yobix-ai/extractous](https://github.com/yobix-ai/extractous) [![Stars](https://img.shields.io/github/stars/yobix-ai/extractous.svg)](https://github.com/yobix-ai/extractous) - Practical extraction and OCR support.
* [machinelearnear/amazon-textract-workbench](https://github.com/machinelearnear/amazon-textract-workbench) [![Stars](https://img.shields.io/github/stars/machinelearnear/amazon-textract-workbench.svg)](https://github.com/machinelearnear/amazon-textract-workbench) - OCR plus tables/forms extraction.

### Typed-output and structuring tools

* [dottxt-ai/outlines](https://github.com/dottxt-ai/outlines) [![Stars](https://img.shields.io/github/stars/dottxt-ai/outlines.svg)](https://github.com/dottxt-ai/outlines) - Structured outputs for reliable downstream automation.
* [Guardrails AI](https://github.com/guardrails-ai/guardrails) [![Stars](https://img.shields.io/github/stars/guardrails-ai/guardrails.svg)](https://github.com/guardrails-ai/guardrails) - Validation and structured generation guardrails.
* [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) [![Stars](https://img.shields.io/github/stars/pydantic/pydantic-ai.svg)](https://github.com/pydantic/pydantic-ai) - Agent and LLM outputs with typed schemas.

### Semantic retrieval backbones

* [qdrant/qdrant](https://github.com/qdrant/qdrant) [![Stars](https://img.shields.io/github/stars/qdrant/qdrant.svg)](https://github.com/qdrant/qdrant) - Semantic indexing and retrieval.
* [weaviate/weaviate](https://github.com/weaviate/weaviate) [![Stars](https://img.shields.io/github/stars/weaviate/weaviate.svg)](https://github.com/weaviate/weaviate) - Another major retrieval backend with vector search.
* [chroma-core/chroma](https://github.com/chroma-core/chroma) [![Stars](https://img.shields.io/github/stars/chroma-core/chroma.svg)](https://github.com/chroma-core/chroma) - Retrieval backend frequently used in LLM memory stacks.

### Meeting and note-processing tools

* [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) [![Stars](https://img.shields.io/github/stars/Zackriya-Solutions/meetily.svg)](https://github.com/Zackriya-Solutions/meetily) - Privacy-first meeting assistant.
* [ndourc/founder-os](https://github.com/ndourc/founder-os) [![Stars](https://img.shields.io/github/stars/ndourc/founder-os.svg)](https://github.com/ndourc/founder-os) - Meeting notes into structured operational objects.
* [sgharlow/claude-code-recipes: Meeting Notes to Action Items](https://github.com/sgharlow/claude-code-recipes/blob/main/recipes/Recipe-001-Meeting-Notes-to-Action-Items.md) - Recipe-shaped prompt workflow.

### Email triage and routing tools

* [stonefullstm/ai-email-triage](https://github.com/stonefullstm/ai-email-triage) [![Stars](https://img.shields.io/github/stars/stonefullstm/ai-email-triage.svg)](https://github.com/stonefullstm/ai-email-triage) - Email triage as a recurring work pattern.
* [ericporres/email-triage-plugin](https://github.com/ericporres/email-triage-plugin) [![Stars](https://img.shields.io/github/stars/ericporres/email-triage-plugin.svg)](https://github.com/ericporres/email-triage-plugin) - Routing and action-oriented email processing.
* [copyleftdev/mailsentinel](https://github.com/copyleftdev/mailsentinel) [![Stars](https://img.shields.io/github/stars/copyleftdev/mailsentinel.svg)](https://github.com/copyleftdev/mailsentinel) - Local-first email triage.

### Review and approval systems

* [aws-samples/review-and-assessment-powered-by-intelligent-documentation](https://github.com/aws-samples/review-and-assessment-powered-by-intelligent-documentation) [![Stars](https://img.shields.io/github/stars/aws-samples/review-and-assessment-powered-by-intelligent-documentation.svg)](https://github.com/aws-samples/review-and-assessment-powered-by-intelligent-documentation) - Review-first workflow example.
* [Yevanchen/human-in-the-loop-in-dify](https://github.com/Yevanchen/human-in-the-loop-in-dify) [![Stars](https://img.shields.io/github/stars/Yevanchen/human-in-the-loop-in-dify.svg)](https://github.com/Yevanchen/human-in-the-loop-in-dify) - Human review in agent workflows.
* [GongRzhe/Human-In-the-Loop-MCP-Server](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) [![Stars](https://img.shields.io/github/stars/GongRzhe/Human-In-the-Loop-MCP-Server.svg)](https://github.com/GongRzhe/Human-In-the-Loop-MCP-Server) - Human approval primitives for AI systems.

## Discovery Surfaces

Useful places to keep discovering new candidates without blindly inflating the list.

* [GitHub Code Search](https://github.com/features/code-search) - Search by problem phrase, not just by stars or topics.
* [GitHub topic: workflow-automation](https://github.com/topics/workflow-automation) - Broad discovery surface.
* [GitHub topic: automation](https://github.com/topics/automation) - Broader, noisier discovery surface.
* [GitHub topic: ai-automation](https://github.com/topics/ai-automation) - AI-heavy automation discovery surface.
* [GitHub topic: knowledge-management](https://github.com/topics/knowledge-management) - Neighboring KM surface.
* [GitHub topic: personal-knowledge-management](https://github.com/topics/personal-knowledge-management?l=typescript) - Local-first and PKM-adjacent discovery surface.
* [GitHub topic: meeting-notes](https://github.com/topics/meeting-notes?o=desc&s=updated) - Discovery surface for meeting-note tooling.
* [GitHub topic: email-automation](https://github.com/topics/email-automation) - Discovery surface for email workflows.
* [GitHub topic: data-provenance](https://github.com/topics/data-provenance?o=asc&s=forks) - Discovery surface for provenance-oriented systems.

## Further Reading and Neighboring Spaces

These are useful but should stay secondary in this list.

* [workflow systems](https://github.com/bentsherman/awesome-workflow) - Good for broad workflow framing.
* [knowledge management](https://github.com/brettkromkamp/awesome-knowledge-management) - Useful for the memory and retrieval edge.
* [PKM](https://github.com/knowfox/awesome-pkm) - Useful for personal-memory design ideas.
* [AI app catalogs](https://github.com/Arindam200/awesome-ai-apps) - Useful for exploration, but easy to overfit to hype.
* [AI agent catalogs](https://github.com/caramaschiHG/awesome-ai-agents-2026) - Useful for discovery, weak as conceptual scaffolding.

## Contributing

Contributions are welcome, but this list aims to stay **pattern-first**.

Before proposing a new link, ask:

- Does it show a recurring knowledge-work pattern?
- Does it expose a real workflow, not just a product pitch?
- Does it help explain a capability that underlies useful automation?
- Does it add something distinct, or is it just another variant of a crowded family?
- If it is a tool, is it here because it supports a pattern, not because it is popular?

A useful contribution usually includes:

- a short explanation of the workflow problem
- the primary pattern it belongs to
- any relevant supporting capabilities
- one sentence on why it matters
- one sentence on its limitation or caveat

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/)

