# Guillaume Marty

**AI Architect · Python · Applied AI** — La Rochelle, France
BSc in Network & Telecom Administration · former Mac Support Technician at Apple (AppleCare, 2015–2023) and Systems & Network Administrator at Sanofi

🌐 [Website](https://lemoncondor.github.io/guillaume-marty/) · 💼 [LinkedIn](https://linkedin.com/in/guillaumemarty)

---

### 🔎 [GitHub Security Researcher (GSR)](https://github.com/LemonCondor/github-security-researcher)

A Python tool I built to find real bugs in large open-source projects without ever mistaking an alert for a confirmed result:

- static detectors for Go code (tree-sitter);
- every bug is **reproduced by a failing test**, then fixed with a regression test;
- deterministic decision engine: **LLM analysis alone can never confirm a finding**;
- more than 500 automated tests · Apache-2.0.

### 🧩 Bugs found and fixed in open-source projects

| Project | Fix | Status |
|---|---|---|
| **Kubernetes** git-sync | panic on a git config key without a value — [#1006](https://github.com/kubernetes/git-sync/pull/1006) | ✅ merged |
| **Google** gVisor | ignored lock error in `Container.Update` — [#15632](https://github.com/google/gvisor/pull/15632) | ✅ merged |
| **Canonical** LXD | User-Agent parser panic — [#19250](https://github.com/canonical/lxd/pull/19250) | 👍 approved |
| **Apache Airflow** | API server fails to start on an IPv6 host with gunicorn — [#74631](https://github.com/apache/airflow/pull/74631) | 🔄 in review |
| **AWS Powertools** | AppSync Events wildcard route matches sibling channels — [#8546](https://github.com/aws-powertools/powertools-lambda-python/pull/8546) | 🔄 in review |
| **Trivy** | npm packages with several licenses lose them all — [#11398](https://github.com/aquasecurity/trivy/pull/11398) | 🔄 in review |
| **GoReleaser** | Nested Dockerfile ARG not expanded in base image — [#7203](https://github.com/goreleaser/goreleaser/pull/7203) | 🔄 in review |
| **Tailscale** | IPv6 DNAT rules without brackets (Kubernetes operator) — [#21770](https://github.com/tailscale/tailscale/pull/21770) | 🔄 in review |
| **containerd** (CNCF) | devmapper `Mounts` lost the snapshot error — [#14335](https://github.com/containerd/containerd/pull/14335) | 🔄 in review |
| **Celery** | chain/group `repr` mangled task names and arguments — [#10855](https://github.com/celery/celery/pull/10855) | 🔄 in review |
| **Netflix** Metaflow | AWS Batch tags with `=` in the value crashed — [#3403](https://github.com/Netflix/metaflow/pull/3403) | 🔄 in review |
| **Unidata** MetPy | exact Lambert W inversion for `dewpoint` (Ambaum 2020) — [#4153](https://github.com/Unidata/MetPy/pull/4153) | 🔄 in review |
| **Sandia National Labs** wiretap | IPv6 API URLs without brackets — [#114](https://github.com/sandialabs/wiretap/pull/114) | 🔄 in review |
| **NASA** earthdata-varinfo | NetCDF-4 `valid_range` ignored in UMM-Var — [#115](https://github.com/nasa/earthdata-varinfo/pull/115) | 🔄 in review |
| **INSEE** pynsee | cache key mixed up `startPeriod`/`endPeriod` queries — [#311](https://github.com/InseeFrLab/pynsee/pull/311) | 🔄 in review |
| **NASA** PO.DAAC l2ss-py | no data for northern-hemisphere granules — [#465](https://github.com/podaac/l2ss-py/pull/465) | 🔄 in review |
| **NASA** harmony-py | EDR time window shifted by the UTC offset — [#155](https://github.com/nasa/harmony-py/pull/155) | 🔄 in review |
| **data.gouv.fr** (udata) | undashed dates read as a whole year — [#4007](https://github.com/opendatateam/udata/pull/4007) | 🔄 in review |
| **Prometheus** node_exporter · procfs · mysqld_exporter | `/proc` and binlog parsers — [#3848](https://github.com/prometheus/node_exporter/pull/3848) · [#880](https://github.com/prometheus/procfs/pull/880) · [#1095](https://github.com/prometheus/mysqld_exporter/pull/1095) | 🔄 in review |
| **Google** cAdvisor · **Kubernetes** kube-state-metrics | [#3947](https://github.com/google/cadvisor/pull/3947) · [#3143](https://github.com/kubernetes/kube-state-metrics/pull/3143) | 🔄 in review |
| **NASA** F´ (fprime-tools) | auto-merge rejected valid C++ — [#356](https://github.com/nasa/fprime-tools/pull/356) | ⏹️ closed (experimental feature, not prioritised) |

<sub>Statuses as of 2026-10-13. Functional and robustness bugs, each reproduced by a test before being submitted.</sub>

### 🛠️ Tools

Python · Go (reading and fixing) · tree-sitter · pytest · fuzzing · LLM integration · Linux · Git · networking
