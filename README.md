# Dawit Lemma Balcha

Backend engineer working on AI evaluation: I review model-generated code, write
rubrics and benchmark tasks, and build the Python tooling around that work.

## What I do

**Evaluation and review**

- Review model output in Python, TypeScript, Go, Java, and occasional C# against
  task specs and repository conventions. Every verdict carries a short written
  rationale.
- Write rubrics and reviewer guidelines; calibrated two reviewers on rubric edge
  cases and revised the guidelines where we kept disagreeing.
- Author benchmark tasks with hidden tests and Docker-based setup.
- Triage GitHub issues: reproduce bugs, check test coverage, rate difficulty.
- Run light red-team passes on coding assistants (prompt injection, insecure
  suggestions) with written findings.

**Engineering**

- FastAPI and Django services on PostgreSQL and Redis; REST APIs.
- React and Next.js when the work needs a UI.
- Docker and GitHub Actions; AWS (EC2, S3, Lambda, ECS); some Kubernetes and
  Terraform.
- pandas and Jupyter for analysis; OWASP basics and dependency scanning as part
  of review.

## Numbers

- Roughly 200 GitHub issues triaged across Python, JavaScript, and Java projects.
- About 40 benchmark tasks written with hidden tests and Docker setup scripts; six public examples are in code-review-bench.
- Two reviewers calibrated on rubric edge cases.

## Selected work

| Repository | What it is |
|---|---|
| [issue-triage-notes](https://github.com/DawitLemmaBalcha/issue-triage-notes) | Python CLI that groups issues by label and drafts reproduction steps |
| [code-review-bench](https://github.com/DawitLemmaBalcha/code-review-bench) | Review benchmark across Python, JavaScript, Go and Java: hidden tests, rubric, Docker runner |
| [Momentum engine](https://github.com/DawitLemmaBalcha/Momentum-Confirmed_Volatility-Adjusted_Engine) | Event-driven quant research engine: intrabar replay, walk-forward optimisation, strategy ensembles, and a TimesFM foundation-model entry gate |
| [agent-workflow](https://github.com/DawitLemmaBalcha/agent-workflow) | Agent engineering loop with a review rubric and a calibration protocol |
| [index_gebeya](https://github.com/DawitLemmaBalcha/index_gebeya) | Telegram-native marketplace: FastAPI, Postgres/pgvector, React Mini App, LLM extraction |

## Writing

- [Review rubric](https://github.com/DawitLemmaBalcha/agent-workflow/blob/main/skills/engineering-loop/references/review-rubric.md):
  severities, verdicts, evidence rules, and test-quality checks for model output.
- [Benchmark rubric](https://github.com/DawitLemmaBalcha/code-review-bench/blob/main/rubric.md)
  and [red-team checklist](https://github.com/DawitLemmaBalcha/code-review-bench/blob/main/redteam.md).
- [Calibration protocol](https://github.com/DawitLemmaBalcha/code-review-bench/blob/main/calibration.md)
  for reviewer disagreement.

## Stack

`Python` `TypeScript` `Go` `Java` `SQL`
`FastAPI` `Django` `PostgreSQL` `Redis`
`React` `Next.js`
`Docker` `GitHub Actions` `AWS`
`pandas` `Jupyter`
