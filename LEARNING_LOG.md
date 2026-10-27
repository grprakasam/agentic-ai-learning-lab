# Learning log

Short, dated notes on what I built, what I learned and what went wrong.

## 2026-10-27 (rename)

- Renamed the repository from my_ai_pet_project to agentic-ai-learning-lab, which says more clearly that this is where I learn by building. GitHub redirects the old links.

## 2026-10-27 (later)

- Merged my Workflow Modernization Agent into this repository as Track 1, with its full commit history, under `workflow_modernization/`. Its CI now runs from the repository root.
- Track 1 is built and tested offline on synthetic samples. Next for it: a recorded live-model run, a real export adapter and a Power Platform tenant import test.
- Added the converter to the Track 2 AWS plan (Lambda behind API Gateway).

## 2026-10-27

- Created the repository and wrote the plan in the README.
- Scope: a question-answering assistant over public-domain FDA guidance documents, with retrieval evaluation, permission-aware search and an answer-and-verify flow, deployed on AWS with Terraform.
- Next: collect about 20 guidance documents, write the first 50 labelled questions, and stand up a local pgvector baseline (milestone M1).
