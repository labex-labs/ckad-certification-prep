# Formation CKAD Certification Prep Path

## Langues

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/fr/learn/ckad"><img width="128px" src="https://file.labex.io/path/izmE8twViI3a.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Commencer-le-Parcours-whitesmoke?style=for-the-badge)](https://labex.io/fr/learn/ckad)

Préparez-vous à l'examen Certified Kubernetes Application Developer (CKAD) grâce à un parcours structuré et orienté pratique. Ce plan met l'accent sur conception et construction d'applications, déploiement, observabilité et maintenance, configuration et sécurité, services et réseau dans Kubernetes, les tâches en mode performance au style CKAD et des scénarios réalistes. Des cours CKAD, des labs et des examens blancs seront ajoutés progressivement.

**Cours**: 3 · **Labs**: 82

## Cours

### 1. [Préparation à la certification CKAD](https://labex.io/fr/courses/ckad-prep)

Un cours de préparation à la certification CKAD adapté aux débutants, comprenant 42 travaux pratiques guidés sur le développement d'applications Kubernetes, allant des bases de kubectl et des objets aux charges de travail, à la configuration, au déploiement, à l'observabilité et au réseau.

[Commencer le Cours](https://labex.io/fr/courses/ckad-prep) · Labs: 42

#### Fondamentaux des applications Kubernetes

|   Index | Nom                                                       | Difficulté   | Pratique                                                                                                      |
|---------|-----------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Explorer kubectl, les contextes et les espaces de noms | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep)  |
|       2 | 🧩  Inspecter les ressources de l'API Kubernetes           | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep)         |
|       3 | 🧩  Créer et inspecter un Pod                              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/create-and-inspect-a-pod-663597?course=ckad-prep)                 |
|       4 | 🧩  Écrire un manifeste de Pod                             | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/write-a-pod-manifest-663628?course=ckad-prep)                     |
|       5 | 🧩  Utiliser des labels et des sélecteurs                  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/use-labels-and-selectors-663626?course=ckad-prep)                 |
|       6 | 🧩  Générer et modifier des manifestes avec kubectl        | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep) |

#### Conception et construction de charges de travail

|   Index | Nom                                                            | Difficulté   | Pratique                                                                                                          |
|---------|----------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Créer un déploiement                                        | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/create-a-deployment-663596?course=ckad-prep)                          |
|       2 | 🧩  Mise à l'échelle d'un déploiement                           | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/scale-a-deployment-663618?course=ckad-prep)                           |
|       3 | 🧩  Exécuter des tâches ponctuelles (Jobs)                      | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/run-one-time-jobs-663616?course=ckad-prep)                            |
|       4 | 🧩  Planifier des CronJobs                                      | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/schedule-cronjobs-663619?course=ckad-prep)                            |
|       5 | 🧩  Choisir la bonne ressource de charge de travail             | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/choose-the-right-workload-resource-663592?course=ckad-prep)           |
|       6 | 🧩  Ajouter des conteneurs d'initialisation (Init Containers)   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/add-init-containers-663589?course=ckad-prep)                          |
|       7 | 🧩  Ajouter un conteneur Sidecar                                | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/add-a-sidecar-container-663588?course=ckad-prep)                      |
|       8 | 🧩  Utiliser des volumes éphémères et persistants dans des Pods | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep) |

#### Configuration, stockage et paramètres d'exécution

|   Index | Nom                                                       | Difficulté   | Pratique                                                                                                    |
|---------|-----------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------|
|      01 | 🧩  Configurer des applications avec des ConfigMaps        | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/configure-applications-with-configmaps-663593?course=ckad-prep) |
|      02 | 🧩  Configurer des applications avec des Secrets           | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/configure-applications-with-secrets-663594?course=ckad-prep)    |
|      03 | 🧩  Injection de variables d'environnement                 | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inject-environment-variables-663607?course=ckad-prep)           |
|      04 | 🧩  Monter des fichiers de configuration                   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/mount-configuration-files-663609?course=ckad-prep)              |
|      05 | 🧩  Utiliser des volumes projetés                          | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/use-projected-volumes-663627?course=ckad-prep)                  |
|      06 | 🧩  Définir les requêtes et limites de ressources          | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/set-resource-requests-and-limits-663620?course=ckad-prep)       |
|      07 | 🧩  Appliquer des quotas de ressources aux espaces de noms | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/apply-namespace-resource-quotas-663590?course=ckad-prep)        |
|      08 | 🧩  Exécuter avec un ServiceAccount dédié                  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep)    |
|      09 | 🧩  Renforcer le contexte de sécurité d'un Pod             | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/harden-a-pod-security-context-663605?course=ckad-prep)          |
|      10 | 🧩  Découvrir et utiliser des ressources personnalisées    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/discover-and-use-custom-resources-663602?course=ckad-prep)      |

#### Déploiement et packaging

|   Index | Nom                                                       | Difficulté   | Pratique                                                                                                     |
|---------|-----------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Effectuer une mise à jour progressive (Rolling Update) | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/perform-a-rolling-update-663610?course=ckad-prep)                |
|       2 | 🧩  Annuler un déploiement défectueux                      | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep)           |
|       3 | 🧩  Ajuster la stratégie de mise à jour d'un déploiement   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/tune-deployment-update-strategy-663622?course=ckad-prep)         |
|       4 | 🧩  Implémenter une version Canary                         | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/implement-a-canary-release-663606?course=ckad-prep)              |
|       5 | 🧩  Basculer le trafic Blue-Green                          | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/switch-blue-green-traffic-663621?course=ckad-prep)               |
|       6 | 🧩  Déployer un chart Helm local                           | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/deploy-a-local-helm-chart-663600?course=ckad-prep)               |
|       7 | 🧩  Personnaliser une application avec Kustomize           | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/customize-an-application-with-kustomize-663598?course=ckad-prep) |
|       8 | 🧩  Construire et exécuter une image d'application locale  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/build-and-run-a-local-application-image-663591?course=ckad-prep) |

#### Observabilité, débogage et mise en réseau des applications

|   Index | Nom                                                                           | Difficulté   | Pratique                                                                                                             |
|---------|-------------------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------|
|      01 | 🧩  Lire les journaux et les événements                                        | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/read-logs-and-events-663611?course=ckad-prep)                            |
|      02 | 🧩  Utiliser exec et le transfert de port pour le débogage                     | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep)      |
|      03 | 🧩  Configurer les sondes de préparation (Readiness) et de vivacité (Liveness) | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep)         |
|      04 | 🧩  Déboguer une application en CrashLoop                                      | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/debug-a-crashlooping-application-663599?course=ckad-prep)                |
|      05 | 🧩  Mise à jour de manifestes d'API obsolètes                                  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/update-deprecated-api-manifests-663623?course=ckad-prep)                 |
|      06 | 🧩  Exposer un déploiement avec un Service                                     | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep)              |
|      07 | 🧩  Diagnostiquer l'accès DNS aux services                                     | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/diagnose-service-dns-access-663601?course=ckad-prep)                     |
|      08 | 🧩  Routage du trafic HTTP avec Ingress                                        | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/route-http-traffic-with-ingress-663615?course=ckad-prep)                 |
|      09 | 🧩  Restreindre le trafic applicatif avec NetworkPolicy                        | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep) |
|      10 | 🧩  Réparer le routage de port nommé d'un Service                              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/repair-named-service-port-routing-663612?course=ckad-prep)               |

### 2. [Examen blanc CKAD 01](https://labex.io/fr/courses/ckad-practice-exam-01)

Un examen blanc pratique pour la certification CKAD composé de 20 défis indépendants sur le développement d'applications Kubernetes, couvrant la conception et la construction d'applications, le déploiement, l'observabilité et la maintenance, la configuration et la sécurité de l'environnement, ainsi que les services et la mise en réseau.

[Commencer le Cours](https://labex.io/fr/courses/ckad-practice-exam-01) · Labs: 20

#### Conception et construction d'applications

|   Index | Nom                                                      | Difficulté   | Pratique                                                                                                                  |
|---------|----------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Construire et exécuter une image d'application locale | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/build-and-run-a-local-application-image-663095?course=ckad-practice-exam-01) |
|       2 | 🎯  Créer un CronJob de nettoyage planifié                | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/create-a-scheduled-cleanup-cronjob-663098?course=ckad-practice-exam-01)      |
|       3 | 🎯  Ajouter des conteneurs Init et Sidecar                | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/add-init-and-sidecar-containers-663093?course=ckad-practice-exam-01)         |
|       4 | 🎯  Utiliser des volumes éphémères et persistants         | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/use-ephemeral-and-persistent-volumes-663112?course=ckad-practice-exam-01)    |

#### Déploiement d'applications

|   Index | Nom                                                | Difficulté   | Pratique                                                                                                           |
|---------|----------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Effectuer une mise à jour progressive sécurisée | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/perform-a-safe-rolling-update-663106?course=ckad-practice-exam-01)    |
|       2 | 🎯  Implémenter une version Canary                  | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/implement-a-canary-release-663104?course=ckad-practice-exam-01)       |
|       3 | 🎯  Déployer une application Helm mise en scène     | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/deploy-a-staged-helm-application-663101?course=ckad-practice-exam-01) |
|       4 | 🎯  Personnaliser une application avec Kustomize    | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/customize-an-app-with-kustomize-663099?course=ckad-practice-exam-01)  |

#### Observabilité et maintenance des applications

|   Index | Nom                                      | Difficulté   | Pratique                                                                                                           |
|---------|------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Configurer les sondes de santé        | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/configure-health-probes-663096?course=ckad-practice-exam-01)          |
|       2 | 🎯  Déboguer une application en CrashLoop | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/debug-a-crashlooping-application-663100?course=ckad-practice-exam-01) |
|       3 | 🎯  Mise à jour des manifestes obsolètes  | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/update-deprecated-manifests-663111?course=ckad-practice-exam-01)      |

#### Environnement, configuration et sécurité des applications

|   Index | Nom                                                   | Difficulté   | Pratique                                                                                                              |
|---------|-------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Injecter des ConfigMaps et des Secrets             | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/inject-configmaps-and-secrets-663105?course=ckad-practice-exam-01)       |
|       2 | 🎯  Appliquer des requêtes et des quotas de ressources | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/apply-resource-requests-and-quotas-663094?course=ckad-practice-exam-01)  |
|       3 | 🎯  Exécuter avec un ServiceAccount dédié              | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/run-with-a-dedicated-serviceaccount-663109?course=ckad-practice-exam-01) |
|       4 | 🎯  Renforcer le contexte de sécurité d'un Pod         | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/harden-a-pod-security-context-663103?course=ckad-practice-exam-01)       |
|       5 | 🎯  Créer une ressource personnalisée d'application    | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/create-an-app-custom-resource-663097?course=ckad-practice-exam-01)       |

#### Services et mise en réseau

|   Index | Nom                                                                   | Difficulté   | Pratique                                                                                                                  |
|---------|-----------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Exposer un déploiement avec un Service                             | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/expose-a-deployment-with-a-service-663102?course=ckad-practice-exam-01)      |
|       2 | 🎯  Routage du trafic HTTP avec Ingress                                | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/route-http-traffic-with-ingress-663108?course=ckad-practice-exam-01)         |
|       3 | 🎯  Restreindre le trafic des applications avec NetworkPolicy          | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restrict-app-traffic-with-networkpolicy-663107?course=ckad-practice-exam-01) |
|       4 | 🎯  Dépanner l'accès aux points de terminaison (Endpoint) d'un Service | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/troubleshoot-service-endpoint-access-663110?course=ckad-practice-exam-01)    |

### 3. [Examen blanc CKAD 02](https://labex.io/fr/courses/ckad-practice-exam-02)

Un second examen blanc indépendant de type CKAD, composé de 20 défis de développement d'applications Kubernetes couvrant les domaines officiels de la certification CKAD à travers divers scénarios opérationnels.

[Commencer le Cours](https://labex.io/fr/courses/ckad-practice-exam-02) · Labs: 20

#### Conception et construction d'applications

|   Index | Nom                                             | Difficulté   | Pratique                                                                                                              |
|---------|-------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Empaqueter une image de worker locale        | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/package-a-local-worker-image-663123?course=ckad-practice-exam-02)        |
|       2 | 🎯  Exécuter un job de données parallèle         | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/run-a-parallel-data-job-663129?course=ckad-practice-exam-02)             |
|       3 | 🎯  Ajouter un sidecar adaptateur                | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/add-an-adapter-sidecar-663113?course=ckad-practice-exam-02)              |
|       4 | 🎯  Monter des données projetées et persistantes | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/mount-projected-and-persistent-data-663122?course=ckad-practice-exam-02) |

#### Déploiement d'applications

|   Index | Nom                                                             | Difficulté   | Pratique                                                                                                                  |
|---------|-----------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Basculer le trafic Bleu-Vert                                 | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/switch-blue-green-traffic-663131?course=ckad-practice-exam-02)               |
|       2 | 🎯  Annuler un déploiement défectueux                            | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/roll-back-a-faulty-deployment-663128?course=ckad-practice-exam-02)           |
|       3 | 🎯  Mise à jour d'une release Helm locale                        | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/upgrade-a-local-helm-release-663132?course=ckad-practice-exam-02)            |
|       4 | 🎯  Générer une surcouche (overlay) Kustomize pour la production | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/generate-a-kustomize-production-overlay-663120?course=ckad-practice-exam-02) |

#### Observabilité et maintenance des applications

|   Index | Nom                                                  | Difficulté   | Pratique                                                                                                               |
|---------|------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Réparer les sondes de démarrage lentes            | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/repair-slow-startup-probes-663127?course=ckad-practice-exam-02)           |
|       2 | 🎯  Déboguer un déploiement de configuration en échec | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/debug-a-failed-config-rollout-663117?course=ckad-practice-exam-02)        |
|       3 | 🎯  Convertir un manifeste de politique obsolète      | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/convert-a-deprecated-policy-manifest-663115?course=ckad-practice-exam-02) |

#### Environnement, configuration et sécurité des applications

|   Index | Nom                                                             | Difficulté   | Pratique                                                                                                              |
|---------|-----------------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Configuration du projet et fichiers secrets                  | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/project-config-and-secret-files-663124?course=ckad-practice-exam-02)     |
|       2 | 🎯  Appliquer les valeurs par défaut des ressources de Namespace | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/enforce-namespace-resource-defaults-663119?course=ckad-practice-exam-02) |
|       3 | 🎯  Restreindre un ServiceAccount d'application                  | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/limit-an-app-serviceaccount-663121?course=ckad-practice-exam-02)         |
|       4 | 🎯  Sécuriser un Pod de cache inscriptible                       | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/secure-a-writable-cache-pod-663130?course=ckad-practice-exam-02)         |
|       5 | 🎯  Créer une ressource d'application versionnée                 | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/create-a-versioned-app-resource-663116?course=ckad-practice-exam-02)     |

#### Services et mise en réseau

|   Index | Nom                                                   | Difficulté   | Pratique                                                                                                            |
|---------|-------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Réparer le routage des ports de service nommés     | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/repair-named-service-port-routing-663126?course=ckad-practice-exam-02) |
|       2 | 🎯  Publier des chemins fractionnés avec Ingress       | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/publish-split-paths-with-ingress-663125?course=ckad-practice-exam-02)  |
|       3 | 🎯  Autoriser le trafic depuis un Namespace spécifique | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/allow-traffic-from-one-namespace-663114?course=ckad-practice-exam-02)  |
|       4 | 🎯  Diagnostiquer l'accès DNS au Service               | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/diagnose-service-dns-access-663118?course=ckad-practice-exam-02)       |

## À propos de LabEx

[LabEx](https://labex.io) est une plateforme d'apprentissage interactive et pratique dédiée au codage et à la technologie. Elle combine des laboratoires, une assistance IA et des machines virtuelles pour offrir une expérience d'apprentissage pratique sans vidéo. Avec une approche stricte 'Apprendre en Faisant', des environnements en ligne interactifs dans le navigateur avec des vérifications automatisées étape par étape, une organisation structurée du contenu avec le système basé sur l'Arbre de Compétences, et une ressource d'apprentissage croissante de 30 Arbres de Compétences et plus de 6 000 Laboratoires, [LabEx](https://labex.io) offre une éducation pratique complète. La plateforme comprend l'assistant d'apprentissage Labby, construit sur les derniers modèles d'IA, offrant une expérience d'apprentissage conversationnelle.

