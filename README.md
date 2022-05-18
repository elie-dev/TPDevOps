

## Projet DevObs CI/CD : Elie GUILBAUD & Morgan NOTT


#### Description du projet : 

Ce projet a été effectué dans le cadre d'un cours DevOps sur l'intégration et le déploiement 
continu. Il a été réalisé en utilisant Docker, SonarCloud, GitHub Action, le déploiement 
a été effectué sur Heroku.



Les Tests unitaires sont effectués grâce au workflow : unit-tests.yml

Les Tests de qualité sont directement réalisés par SonarCloud

Les Tests de sécurité (scan des dépendances) sont effectués par le workflow : dependency-review.yml

Le déploiement est effectué par le workflow : deployHeroku.yml
lien vers l'application en ligne  : https://tpdevops123.herokuapp.com/



Nous sommes informés de chaque modification, par des notifications Discord, sur un serveur créé pour l'occasion.


Nous avons rencontré quelques difficultés concernant les tests de qualité avec SonarCloud, nous pensons que cela venait
du fait qu'ils se faisaient en double, sur SonarCloud directement et via le workflow de test. Les tests se faisant
directement et facilement sur SonarCloud, nous avons supprimé le workflow SonarCloud 
et laissons les tests se faire directement en ligne.

PS. Le temps nous a manqué pour nous occuper de la documentation en ligne, nous suivions cette documentation : 
https://docs.github.com/en/pages/quickstart 






# project_DevOps

first : clone the project

second : cd project_DevOps puis npm i

thrid : launch test unit with npm run test 


AIDE POUR GITHUB : https://github.blog/2022-02-02-build-ci-cd-pipeline-github-actions-four-steps/

AIDE POUR GITLAB : https://blog.eleven-labs.com/fr/introduction-gitlab-ci/ 
