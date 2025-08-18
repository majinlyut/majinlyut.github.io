<style>
  .wrapper { max-width: 1200px !important; padding: 24px; }
  img { max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 2px 14px rgba(0,0,0,.06); }
  sub { color: #666; }
</style>
# 👋 Salut, je suis Lyuta, Data Engineer
Après 2 ans en contrôle de gestion, j’ai évolué vers le data engineering pour automatiser et fiabiliser des flux de données à grande échelle. Je conçois et déploie des pipelines Big Data (Python, SQL, Spark, Kafka/Redpanda, Delta Lake) et des architectures Cloud (AWS, Docker, Kubernetes), avec une expertise en ETL/ELT, orchestration (Kestra, Airflow) et data visualization (Power BI, Grafana).
Mon atout ? Une double compétence : compréhension métier acquise en finance et maîtrise des outils techniques pour transformer la donnée en décisions.

## 🧑‍💻 À propos
- 🎓 Master Contrôle de gestion + Master Data Engineering  
- 💼 2 ans en contrôle de gestion → transition vers la data  
- 🚀 Spécialiste ETL/ELT, streaming temps réel, monitoring et pipelines cloud  


## 🛠️ Compétences
- **Langages** : Python, SQL, PySpark  
- **Data** : Kafka/Redpanda, Delta Lake, MongoDB, PostgreSQL  
- **Cloud/Infra** : AWS (ECS, S3, CloudWatch), Docker, Kestra  
- **Visualisation** : Power BI, Grafana  


## 🚀 Projets

### Forecast 2.0 — Pipeline météo
<p align="center">
  <img src="assets/img/Archi_meteo.png" alt="Architecture Forecast 2.0 (MongoDB RS, Airbyte, PySpark)" width="100%">
</p>
<sub>Architecture : MongoDB Replica Set (ECS) • Airbyte • PySpark • CloudWatch</sub>

**Objectif.** Améliorer la fiabilité des prévisions électriques en zones peu couvertes.  
**Stack.** Airbyte → MongoDB **Replica Set** (AWS ECS) → **PySpark** → CloudWatch.  
**Rôle / actions.**
- Architecture **multi-sources** (normalisation + contrôles qualité)
- Déploiement MongoDB en **Replica Set** (EC2/ECS)
- **Observabilité** : métriques + logs CloudWatch
- Tests de validation (completeness, duplicates, z-score)

**Impact.**
- **+35%** de données météo exploitables  
- **-50%** de temps de traitement

<details><summary><b>Détails techniques</b></summary>

- Schémas unifiés, idempotence, partitionnement, backfills  
- Stratégies de ré-essai et alerting
</details>

---

### Sport Data Solution — ETL streaming bien-être
<p align="center">
  <img src="assets/img/Archi_slack.png" alt="Architecture streaming Slack/Delta Lake" width="100%">
</p>
<sub>Architecture : Redpanda/Kafka • PySpark Structured Streaming • Delta Lake • Slack API • Power BI</sub>

**Objectif.** Récompenser l’activité sportive (primes & jours “bien-être”).  
**Stack.** **Redpanda/Kafka** → **PySpark** → **Delta Lake** → **Slack API** / **Power BI**.  
**Rôle / actions.**
- Ingestion temps réel (topics par activité)
- Enrichissement + **règles d’éligibilité** (croisement activités/RH)
- **Notifications Slack** en live (consumer Python)
- **Monitoring** : Prometheus + Grafana

**Impact.**
- Latence **< 5 s** sur notifications  
- Attribution automatique des droits (prime + 5 jours “bien-être”)

<details><summary><b>Détails techniques</b></summary>

- Schémas d’événements, exactly-once (checkpointing), SCD sur Delta  
- Gestion des pics (backpressure) et DLQ
</details>

---

### RAG Chatbot — Recherche assistée par Mistral
<p align="center">
  <img src="assets/img/Archi_RAG.png" alt="Architecture RAG (Mistral, FAISS, Streamlit)" width="100%">
</p>
<sub>Architecture : Mistral API • FAISS • Streamlit</sub>

**Objectif.** Accès rapide à la connaissance interne **sans logging** utilisateur.  
**Stack.** **Mistral API** + **FAISS** + **Streamlit**.  
**Rôle / actions.**
- Ingestion & indexation (chunking, embeddings, métadonnées)
- Prompting **contextualisé** + gestion d’historique
- Déploiement conteneurisé + gestion des secrets

**Impact.**
- Temps de recherche divisé par **3**  
- Satisfaction interne ↑

<details><summary><b>Détails techniques</b></summary>

- Formats supportés, politique de ré-indexation, limites FAISS  
- Stratégies d’évaluation (exact match / semantic match)
</details>


## 📬 Contact

- Email : [lyuta.nakata@gmail.com.com](mailto:lyuta.nakata@gmail.com)  
- LinkedIn : [https://linkedin.com/in/lyuta ](https://www.linkedin.com/in/lyuta-nakata/) 
- GitHub : [https://github.com/majinlyut](https://github.com/majinlyut)

_Dernière mise à jour : 2025‑08‑18_

