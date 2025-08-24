
# 👋 Salut!  
# Je suis Lyuta, Data Engineer
Après 2 ans en contrôle de gestion, j’ai évolué vers le data engineering pour automatiser et fiabiliser des flux de données à grande échelle. Je conçois et déploie des pipelines Big Data (Python, SQL, Spark, Kafka/Redpanda, Delta Lake) et des architectures Cloud (AWS, Docker), avec une expertise en ETL/ELT, orchestration (Kestra, Airflow) et data visualization (Power BI, Grafana).  
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

### Sport Data Solution — ETL streaming d'activités sportives
<p align="center">
  <img src="assets/img/Slack1.png" width="100%">
</p>
<sub>Architecture : Redpanda/Kafka • PySpark Structured Streaming • Delta Lake • Slack API • Power BI</sub>

**Objectif:** Récompenser l’activité sportive (trajet domicile/travail et extra-professionnel) + Notification Slack pour renforcer l'émulation de l'équipe 
**Stack:** PostgreSql → Redpanda/Kafka → PySpark → Delta Lake → Power BI  
                                       → Slack API  
**Rôle / actions:**
- Ingestion temps réel
- Delta lake (bronze & gold) 
- Enrichissement + règles d’éligibilité (croisement activités/RH)
- Notifications Slack en live (consumer Python) / Dashboard PowerBI pour suivre les indicateurs
- Monitoring : Prometheus + Grafana (temps de latence, pics, erreurs ...)

<p align="center">
  <img src="assets/img/Archi_slack.png" alt="Architecture streaming Slack/Delta Lake" width="100%">
</p>

**Impact:**
- Latence **< 2 s** sur notifications  
- Calcul automatique des primes visualisable sur PowerBI
- Possibilité de changement des rêgles d'attribution pour recalcul

[Lien vers le projet](https://github.com/majinlyut/sport_data_solution)

* * *
* * *



### Energy Weather Data Pipeline
<p align="center">
  <img src="assets/img/meteo1.png"  width="100%">
</p>


**Objectif:** Améliorer la fiabilité des prévisions électriques vertes en zones peu couvertes en ajoutant des sources météo semi-amateurs.  
**Stack:** Airbyte → MongoDB Replica Set (AWS ECS) → PySpark → CloudWatch.  
**Rôle / actions:**
- Architecture multi-sources (normalisation + contrôles qualité)  
- Déploiement MongoDB en Replica Set (EC2/ECS)  
- Monitoring: métriques + logs CloudWatch  
- Tests de validation (completeness, duplicates)  

<p align="center">
  <img src="assets/img/Archi_meteo.png" alt="Architecture" width="100%">
</p>

**Impact:**
- Plus de données météo exploitables  
- Moins de temps de traitement  
- Disponibilité accrue, scalable et sécurisé  

[Lien vers le projet](https://github.com/majinlyut/weather_data_pipeline)

* * *
* * *



### RAG Chatbot de recommandation d'évènements
<p align="center">
  <img src="assets/img/rag.jpg" alt="Architecture RAG " width="100%">
</p>


**Objectif.** Faciliter l’accès aux évènements internes et externes via un assistant intelligent, capable de fournir des réponses contextualisées et personnalisées.  
**Stack:** AWS (S3, Lambda, API Gateway, OpenSearch, DynamoDB, Quicksight, CloudWatch) + Mistral API  
**Rôle / actions.**
- Ingestion des données OpenAgenda → stockage sur S3
- Lambda : chunking + embeddings, indexation dans OpenSearch
- API Gateway → script RAG connecté à Mistral API pour génération de réponses
- Gestion de l’historique conversationnel + feedback utilisateurs avec DynamoDB
- Analyse des retours utilisateurs via dashboard Quicksight
- Monitoring complet de l’architecture avec CloudWatch

<p align="center">
  <img src="assets/img/Archi_RAG.png" width="100%">
</p>


**Impact.**
- Temps de recherche amélioré
- Satisfaction utilisateur ↑ grâce à des réponses contextualisées
- Scalabilité et résilience grâce à l’architecture cloud-native sur AWS

[Lien vers le projet](https://github.com/majinlyut/rag_chatbot_event_Paris)

* * *
* * *

## 📬 Contact

- Email : [lyuta.nakata@gmail.com.com](mailto:lyuta.nakata@gmail.com)  
- LinkedIn : [https://linkedin.com/in/lyuta ](https://www.linkedin.com/in/lyuta-nakata/) 
- GitHub : [https://github.com/majinlyut](https://github.com/majinlyut)

_Dernière mise à jour : 2025‑08‑18_

