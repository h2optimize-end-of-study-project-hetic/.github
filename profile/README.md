# H2Optimize

## Architecture

Nous avons mis en place une architecture hybride, en procédant à un découpage de l’application en services indépendants, chacun ayant un rôle spécifique :
- DB : persistance des données.
- Telegraf : connecteur, agissant comme un intermédiaire entre le broker MQTT et la base de données TimescaleDB.
- Frontend : interface utilisateur développée en React.
- Backend : gestion de la logique métier via une API REST avec FastAPI.
- Deploy : utilitaires pour le déploiement
  
## Organisation du projet

- Organisation : https://github.com/h2optimize-end-of-study-project-hetic
  - Frontend : https://github.com/h2optimize-end-of-study-project-hetic/frontend/tree/main
  - Backend : https://github.com/h2optimize-end-of-study-project-hetic/backend/tree/main
  - Database : https://github.com/h2optimize-end-of-study-project-hetic/database
  - Mqtt-connector : https://github.com/h2optimize-end-of-study-project-hetic/mqtt_connector
  - Deployement :  https://github.com/h2optimize-end-of-study-project-hetic/deployement

## Membres

- BERNARD Anne-Flore : QA - Full-Stack
- RENEVIER Joachim : DevOps - Back-End
- LIN Chrisline : Design UI/UX - Full-Stack
- MACHEFAUX Valentin : Data - Back-End
- AVALLE Sylvain

Organisations / interactions des services

<img width="1714" height="1084" alt="image-20250808-132153" src="https://github.com/user-attachments/assets/1040e040-6e5d-4029-b868-b4b3cfc34292" />


Services deployées

<img width="1568" height="1080" alt="Sans-titre-2025-08-06-1044" src="https://github.com/user-attachments/assets/2d33aec0-84fa-4cfd-8368-0413ba496690" />





