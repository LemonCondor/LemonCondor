<h1 align="center">Guillaume Marty</h1>

<p align="center">
  <b>AI &amp; Python Automation Developer</b> — La Rochelle, France<br>
  I build tools that find <b>real, reproducible bugs</b> in large open-source projects — and I fix them upstream.
</p>

<p align="center">
  <a href="https://lemoncondor.github.io/guillaume-marty/">🌐 Website</a> ·
  <a href="https://linkedin.com/in/guillaumemarty">💼 LinkedIn</a> ·
  <a href="https://github.com/LemonCondor/github-security-researcher">🔎 GSR tool</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/merged_upstream_PRs-11-2ea44f?style=for-the-badge" alt="11 merged PRs">
  <img src="https://img.shields.io/badge/automated_tests-500%2B-0a7bbb?style=for-the-badge" alt="500+ tests">
  <img src="https://img.shields.io/badge/languages-Python_·_Go_·_JS-444?style=for-the-badge" alt="languages">
</p>

<p align="center"><i>Fixes merged by the maintainers of:</i></p>
<p align="center">
  <img src="https://img.shields.io/badge/Google-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry">
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" alt="Celery">
  <img src="https://img.shields.io/badge/Pillow-11557C?style=flat-square&logo=python&logoColor=white" alt="Pillow">
  <img src="https://img.shields.io/badge/GoReleaser-00ADD8?style=flat-square&logo=go&logoColor=white" alt="GoReleaser">
</p>

---

### 🔎 [GitHub Security Researcher (GSR)](https://github.com/LemonCondor/github-security-researcher)

A Python tool I built to find real bugs in large open-source codebases — and to **never mistake an alert for a confirmed result**:

- static detectors for Go code (tree-sitter), plus logic-bug hunting driven by an LLM that is **kept honest by code**;
- every candidate is **reproduced by a failing test** on a clean checkout, then fixed with a regression test that is **red without the fix, green with it** — the verdict is always decided by code, never by the model;
- a deterministic decision engine: **LLM analysis alone can never confirm a finding**;
- 500+ automated tests · Apache-2.0.

On a blind replay against AWS Powertools, the hunter re-discovered two known bugs on its own and proved each fix (red→green) in about five minutes.

### 🧩 Bugs I found and fixed in open-source projects

| Project | Fix | Status |
|---|---|---|
| **Kubernetes** git-sync | panic on a git config key without a value — [#1006](https://github.com/kubernetes/git-sync/pull/1006) | ✅ merged |
| **Google** gVisor | ignored lock error in `Container.Update` — [#15632](https://github.com/google/gvisor/pull/15632) | ✅ merged |
| **AWS** Powertools | AppSync Events wildcard route matched sibling channels — [#8546](https://github.com/aws-powertools/powertools-lambda-python/pull/8546) | ✅ merged |
| **OpenTelemetry** Python | Jaeger propagator rejected URL-encoded `uber-trace-id` — [#5793](https://github.com/open-telemetry/opentelemetry-python/pull/5793) | ✅ merged |
| **Prometheus** procfs | panics on short lines in `/proc` and `/sys` parsers — [#880](https://github.com/prometheus/procfs/pull/880) | ✅ merged |
| **Prometheus** mysqld_exporter | wrong binlog file number for names with dots — [#1095](https://github.com/prometheus/mysqld_exporter/pull/1095) | ✅ merged |
| **pydata** xarray | string dimension names lost their suffix — [#11757](https://github.com/pydata/xarray/pull/11757) | ✅ merged |
| **Celery** | chain/group `repr` mangled task names and arguments — [#10855](https://github.com/celery/celery/pull/10855) | ✅ merged |
| **Pillow** | arithmetic between two TIFF `IFDRational` values failed — [#10321](https://github.com/python-pillow/Pillow/pull/10321) | ✅ merged |
| **GoReleaser** | nested Dockerfile `ARG` not expanded in the base image — [#7203](https://github.com/goreleaser/goreleaser/pull/7203) | ✅ merged |
| **INSEE** pynsee | cache key mixed up `startPeriod`/`endPeriod` queries — [#311](https://github.com/InseeFrLab/pynsee/pull/311) | ✅ merged |

<sub>Background: Network &amp; Telecom Administrator diploma (m2i, 2016) · Systems &amp; Network Technician at Sanofi (2018–2022) · Tier 2 Mac Support Technician at Apple (2022–2025) · self-taught in AI &amp; automation.</sub>
