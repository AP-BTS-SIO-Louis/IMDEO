### 3. Cadre juridique et contractuel

Le choix du prestataire repose sur sa capacité à respecter le cahier des charges technique et juridique du groupe. Afin de sécuriser le partenariat, les clauses suivantes devront être contractualisées :

#### 3.1 Tableau - clauses obligatoires dans le contrat

| **Clause**                      | **Objectif et Engagement pour IMDEO**                                                                                                                                |
| ------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Définition du périmètre**     | Délimiter strictement les responsabilités de l'hébergeur (infrastructure) et celles d'IMDEO (applicatif site vitrine) pour éviter tout litige en cas d'incident.     |
| **Niveau de service (SLA)**     | Garantir une disponibilité de **99% par an**. Inclut une Garantie de Temps d'Intervention (GTI) de **2h maximum** en cas d'incident critique.                        |
| **Pénalités**                   | Appliquer des pénalités financières dissuasives (ex: 5% du CA annuel d'IMDEO par heure d'indisponibilité hors SLA) pour contraindre le prestataire à l'excellence.   |
| **Conformité RGPD**             | Assurer que le traitement des données est conforme à la réglementation européenne, avec un accès aux serveurs strictement limité au personnel habilité.              |
| **Confidentialité**             | Garantir le secret industriel et la protection des brevets via le chiffrement des données et une clause de non-divulgation stricte pour les employés de l'hébergeur. |
| **Sécurité (Authentification)** | Imposer la mise en place d'une authentification multifacteur (**MFA**[^4]) pour sécuriser tout accès aux interfaces d'administration du serveur.                     |
| **Protection réseau**           | Garantir la continuité de service même en cas de cyberattaque massive grâce à une protection anti-DDoS[^5] native.                                                   |
| **Sauvegardes**                 | Contractualiser la stratégie de backup (règle du 3-2-1) pour prévenir toute perte de données accidentelle ou malveillante.                                           |
| **Réversibilité[^3]**           | Obliger le prestataire à fournir, en fin de contrat, un export complet et exploitable des données et applications pour permettre la migration vers un tiers.         |
| **Résiliation**                 | Définir les modalités de fin de contrat (préavis, motifs légitimes) et prévoir une révision annuelle des conditions pour s'adapter aux évolutions d'IMDEO.           |

#### Lexique

[^2]: **SLA** = **S**ervice **L**evel **A**greement : Détermine le niveau de service attendu entre un client et un prestataire.
[^5]: **DDoS** = **D**istributed **D**enial-**o**f-**S**ervice : Attaque informatique qui inonde le service légitime de requête afin d'empêcher son fonctionnement.
[^4]: **MFA** = **M**ulti-**F**actor **A**uthentication : Couche de protection supplémentaire pour l'authentification. Cela combine plusieurs méthode d'authentification comme un mot de passe et un code one time password via une application. 