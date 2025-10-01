# Track A — Layout-Preserving Document Editing (PDF & DOCX)

## Problem
When businesses edit contracts, letters, or formal documents, layout fidelity is critical. Translating, redacting, or updating must not change how the document looks.

## Core Deliverable
Build an **agent (using OpenAI’s Agents SDK)** that ingests a PDF/DOCX, applies edits (translation, replacement, redaction, updates), and outputs:
- A file that is **exactly identical in layout** to the original (fonts, spacing, tables, footnotes, headers, pagination, formatting).
- A **change log** highlighting all edits.

## Example Task
Take a legal contract in **German**, translate it into **English**, and deliver the translated document with the **exact same layout** (same fonts, sections, and pagination) as the original.

## Constraints
- Redactions must fully remove sensitive text.
- Multi-column layouts, numbered clauses, tables, and footnotes must remain untouched.
- Accessibility features (e.g., reading order) must be preserved.

## Success Criteria
- **Layout fidelity:** Edited file is visually and structurally identical to the original.
- **Content accuracy:** All requested edits applied correctly.
- **Traceability:** Change log with page/section references.
- **Robustness:** Handles tables, footnotes, and multi-column text.
- **Throughput:** Works reliably on 50–100 page inputs.

---

## Getting Started (Agents SDK)
Use the OpenAI **Agents SDK** to orchestrate your agent and tool calls.

- **Agents SDK (Python) docs:** https://openai.github.io/openai-agents-python/  [oai_citation:0‡OpenAI GitHub](https://openai.github.io/openai-agents-python/?utm_source=chatgpt.com)  
- **Quickstart:** https://openai.github.io/openai-agents-python/quickstart/  [oai_citation:1‡OpenAI GitHub](https://openai.github.io/openai-agents-python/quickstart/?utm_source=chatgpt.com)  
- **Agents guide (platform docs):** https://platform.openai.com/docs/guides/agents-sdk  [oai_citation:2‡OpenAI Platform](https://platform.openai.com/docs/guides/agents-sdk?utm_source=chatgpt.com)  
- **Responses API reference (for tool use & stateful runs):** https://platform.openai.com/docs/api-reference/responses  [oai_citation:3‡OpenAI Platform](https://platform.openai.com/docs/api-reference/responses?utm_source=chatgpt.com)

### Local setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install openai-agents  # Agents SDK
