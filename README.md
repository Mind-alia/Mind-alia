# Alexis Lasserre

**Agentic AI engineer** · École 42 · France · former construction surveyor

I build AI agents you can verify: sandboxes, hidden tests, measured evals and human approval.
*Ingénieur IA agentique : je construis des agents IA qu'on peut vérifier.*

## Highlights

| Project | What it is | Proof |
|---|---|---|
| **The Circuit** | A harness that makes coding agents (Claude, Codex, Gemini, a local model) work on real code without trusting them: locked container, hidden tests, a "breaker" agent, cross-vendor review, human approval before any merge. | 0/82 bad diffs accepted on 126 reference diffs · 28/28 attacks blocked · 2,070 tests |
| **ARIA** | Site reports for construction professionals: voice notes and photos become a structured report, then PDF and Word. Rules forbid inventing a person in charge or a deadline. | In production · Report Lab comparing 17 models · ~1,240 tests |
| **ARIA Mobile** | Flutter app for iOS and Android: offline-first capture, automatic sync, annotated PDF plans, report review and sending. | 16 screens · 545 tests · iOS on TestFlight |
| **Local agents** | Five Claude Code agents scheduled on my PC and connected over MCP to Gmail, Drive, Calendar, Sheets and Slack. They only write drafts. | 36 MCP tools denied by config · rehearsal mode |
| **[RAG against the machine](https://github.com/Mind-alia/rag-against-the-machine)** | RAG over the vLLM codebase with character-exact citations built by the code, never by the model. | R@5 0.850 on the official grader |
| **[local-rag-eval](https://github.com/Mind-alia/local-rag-eval)** | The standard-library bench behind my note on RAG citations: hybrid search, citations mapped back to files by code, rescoring without calling the model. | 17 tests, no model needed · first run 0/20, then 16/20 exact cited answers |

Most of these repositories are private; the last two are public. I walk through the rest of the code in interviews.

## How I work

Agents write a large part of my code. I design the system around them, write the specs, measure the results and approve every merge.

## Stack

Python · TypeScript · FastAPI · React · Flutter · PostgreSQL · Docker · Claude Code · Codex · MCP · Ollama

## Contact

Portfolio: *link coming soon* · Open to apprenticeships, junior positions and freelance missions.
