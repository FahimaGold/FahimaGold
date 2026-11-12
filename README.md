# Hi, I'm Fahima 👋

**Backend & Platform Engineer | LLM infrastructure, cloud security, AWS**
📍 Kitchener, ON, Canada (Permanent Resident) · Platform engineer at [Eden AI](https://www.edenai.co)

I build AI/LLM systems and the infrastructure under them: a multi-provider LLM gateway, provider integrations, billing accuracy, and production security on AWS.

## 🔧 Open source

- **[LiteLLM](https://github.com/BerriAI/litellm)** (LLM gateway): 3 merged fixes found running it in production
  - [#36705](https://github.com/BerriAI/litellm/pull/36705): a 400 whose body contained `429` was mapped to a rate limit
  - [#36800](https://github.com/BerriAI/litellm/pull/36800): an explicit provider no longer loses to a known OpenAI model name
  - [#47963](https://github.com/BerriAI/litellm/pull/47963): AWS Polly now uses the requested engine instead of always `neural`
- **[syzkaller](https://github.com/google/syzkaller)** (Google's kernel fuzzer): author of the [guide to porting syzkaller to a new OS](https://github.com/google/syzkaller/blob/master/docs/adding_new_os_support.md)
- **[Haystack](https://github.com/deepset-ai/haystack-core-integrations/pull/3721)**: CI/CD hardening, scoping secrets across 51 GitHub Actions workflows

## 💼 Recent work

- **[edenai-workflows](https://github.com/edenai/Edenai-workflows)**: Eden AI's Python SDK for AI workflows (primary author): async client, `@workflow` / `@step` orchestration, zero-config deploys via GitHub Actions
- Zero-downtime migration of a production PostgreSQL database (228M-row tables) to encrypted RDS with logical replication
- RAG pipeline that triages support tickets and proposes code fixes (FAISS, AST-based code chunking)
- Security hardening: account-takeover fix, SSRF protections, OIDC CI/CD, SOC 2 / ISO 27001 remediation

**Stack:** Python · Django · FastAPI · Go · TypeScript · PostgreSQL · Redis · AWS · Terraform · Docker · Kubernetes · GitHub Actions

## ✍️ Writing

Deep dives on [Medium](https://df-mokhtari.medium.com), including [React Fiber internals](https://blog.stackademic.com/part-2-react-reconciliation-a-deep-dive-react-fibers-28fba20e3334) ([demo repo](https://github.com/FahimaGold/FiberInternals)).

## 📬 Contact

[LinkedIn](https://www.linkedin.com/in/fahima-mokhtari-allal/) · df_mokhtari@esi.dz · [Stack Overflow](https://stackoverflow.com/users/6651763/fahima-mokhtari?tab=profile)
