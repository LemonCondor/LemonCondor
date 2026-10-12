# Guillaume Marty

**Développeur Python · automatisation · IA appliquée** — La Rochelle, France
Licence en administration des réseaux et télécommunications · ancien technicien support chez Apple

🌐 [Site](https://lemoncondor.github.io/guillaume-marty/) · 💼 [LinkedIn](https://linkedin.com/in/guillaumemarty)

---

### 🔎 [GitHub Security Researcher (GSR)](https://github.com/LemonCondor/github-security-researcher)

Un outil que j'ai construit en Python pour trouver de vrais bugs dans de grands projets open source, sans jamais prendre une alerte pour un résultat confirmé :

- détecteurs statiques pour le code Go (tree-sitter) ;
- chaque bug est **reproduit par un test qui échoue**, puis corrigé avec un test de régression ;
- moteur de décision déterministe : **une analyse par LLM seule ne peut jamais confirmer un résultat** ;
- plus de 500 tests automatisés · Apache-2.0 · développé avec Claude Code.

### 🧩 Bugs trouvés et corrigés dans des projets open source

| Projet | Correctif | Statut |
|---|---|---|
| **Kubernetes** git-sync | panic sur une clé de config git sans valeur — [#1006](https://github.com/kubernetes/git-sync/pull/1006) | ✅ fusionnée |
| **Google** gVisor | erreur de verrou ignorée dans `Container.Update` — [#15632](https://github.com/google/gvisor/pull/15632) | 👍 approuvée |
| **Canonical** LXD | panic du parseur de User-Agent — [#19250](https://github.com/canonical/lxd/pull/19250) | 👍 approuvée |
| **NASA** F´ (fprime-tools) | auto-merge qui refusait du C++ valide — [issue #6176](https://github.com/nasa/fprime/issues/6176) · [#356](https://github.com/nasa/fprime-tools/pull/356) | ⏹️ fermée (fonction expérimentale, non prioritaire) |
| **data.gouv.fr** (udata) | dates sans tirets lues comme une année entière — [#4007](https://github.com/opendatateam/udata/pull/4007) | 🔄 en revue |
| **Prometheus** node_exporter · procfs · mysqld_exporter | parseurs `/proc` et binlog — [#3848](https://github.com/prometheus/node_exporter/pull/3848) · [#880](https://github.com/prometheus/procfs/pull/880) · [#1095](https://github.com/prometheus/mysqld_exporter/pull/1095) | 🔄 en revue |
| **Google** cAdvisor · **Kubernetes** kube-state-metrics | [#3947](https://github.com/google/cadvisor/pull/3947) · [#3143](https://github.com/kubernetes/kube-state-metrics/pull/3143) | 🔄 en revue |

<sub>Statuts au 12/10/2026. Bugs fonctionnels et de robustesse, chacun reproduit par un test avant d'être proposé.</sub>

### 🛠️ Outils

Python · Go (lecture et correctifs) · tree-sitter · pytest · fuzzing · Claude Code · LLM · Linux · Git · réseaux
