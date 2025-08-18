# 👋 Salut, je suis Lyuta  
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

<img src="assets/img/Archi_meteo.png" alt="Architecture" width="150%">

**Objectif.** Améliorer la fiabilité des prévisions électriques dans des zones peu couvertes.  
**Stack.** Airbyte → MongoDB **Replica Set** (AWS ECS) → **PySpark** → CloudWatch.  
**Ce que j’ai fait.**
- Architecture **multi-sources météo** (normalisation + contrôle qualité)
- Déploiement MongoDB en **Replica Set** sur ECS (instances EC2)
- **Monitoring** (métriques + logs) via CloudWatch
- Tests de validation sur la chaîne (completeness, duplicates, z-scores)

**Impact (exemples, à adapter).**
- +35% de données météo exploitables  
- -50% du temps de traitement

➕ *Détails techniques :* formatage des schémas, idempotence, partitionnement, backfills.

---

### Sport Data Solution — ETL streaming bien-être

<img src="assets/img/Archi_slack.png" alt="Architecture" width="150%">

**Objectif.** Récompenser l’activité sportive des salarié·e·s (primes & jours “bien‑être”).  
**Stack.** **Redpanda/Kafka** → **PySpark Structured Streaming** → **Delta Lake** → **Slack API** / **Power BI**.  
**Ce que j’ai fait.**
- Ingestion temps réel (topics par type d’activité)
- Enrichissement + **règles d’éligibilité** (croisement activités/RH)
- **Notifications Slack** instantanées via consumer Python
- **Monitoring** pipeline : Prometheus + Grafana

**Impact (exemples, à adapter).**
- Latence **< 5 s** sur le flux notifications  
- Calcul automatique des droits (prime + 5 jours “bien‑être”)

➕ *Détails techniques :* schémas d’événements, exactly‑once (checkpointing), SCD sur Delta.

---

### RAG Chatbot — Recherche assistée par Mistral

<img src="assets/img/Archi_RAG.png" alt="Architecture" width="150%">

**Objectif.** Accès rapide à la connaissance interne sans logging utilisateur.  
**Stack.** **Mistral API** + **FAISS** + **Streamlit** (frontend léger).  
**Ce que j’ai fait.**
- Pipeline d’indexation (chunking, embeddings, métadonnées)
- Prompting **contextualisé** + gestion de l’historique
- Déploiement simple (container) + secrets

**Impact (exemples, à adapter).**
- Réduction du temps de recherche **x3**  
- Satisfaction interne ↑

➕ *Détails techniques :* formats supportés, politique de ré-indexation, limites FAISS.

---

## 📬 Contact

- Email : [lyuta.nakata@gmail.com.com](mailto:lyuta.nakata@gmail.com)  
- LinkedIn : [https://linkedin.com/in/lyuta ](https://www.linkedin.com/in/lyuta-nakata/) 
- GitHub : https://github.com/majinlyut

_Dernière mise à jour : 2025‑08‑18_

