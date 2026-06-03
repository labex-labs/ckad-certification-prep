# CKAD-Schulung Zertifizierungsvorbereitung

## Sprachen

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/de/learn/ckad"><img width="128px" src="https://file.labex.io/path/izmE8twViI3a.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Pfad-Starten-whitesmoke?style=for-the-badge)](https://labex.io/de/learn/ckad)

Bereiten Sie sich mit einem strukturierten, praxisorientierten Lernpfad auf die Prüfung Certified Kubernetes Application Developer (CKAD) vor. Der Fokus liegt auf Anwendungsdesign und -erstellung, Deployment, Observability und Wartung, Konfiguration und Sicherheit sowie Services und Netzwerk in Kubernetes, leistungsbasierten CKAD-Aufgaben und realistischen Szenarien. CKAD-Kurse, Labs und Übungsprüfungen werden schrittweise ergänzt.

**Kurse**: 3 · **Labs**: 82

## Kurse

### 1. [CKAD-Vorbereitung](https://labex.io/de/courses/ckad-prep)

Ein einsteigerfreundlicher Vorbereitungskurs für die CKAD-Zertifizierung mit 42 geführten Kubernetes-Anwendungsentwicklungs-Experimenten, die von den Grundlagen zu kubectl und Objekten bis hin zu Workloads, Konfiguration, Deployment, Observability und Networking reichen.

[Kurs Starten](https://labex.io/de/courses/ckad-prep) · Labs: 42

#### Kubernetes Application Foundations

|   Index | Name                                               | Schwierigkeit   | Übung                                                                                                      |
|---------|----------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Erkundung von kubectl, Kontexten und Namespaces | Anfänger        | [Labor Starten](https://labex.io/de/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep)  |
|       2 | 🧩  Kubernetes API-Ressourcen untersuchen           | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep)         |
|       3 | 🧩  Einen Pod erstellen und untersuchen             | Anfänger        | [Labor Starten](https://labex.io/de/labs/create-and-inspect-a-pod-663597?course=ckad-prep)                 |
|       4 | 🧩  Ein Pod-Manifest schreiben                      | Anfänger        | [Labor Starten](https://labex.io/de/labs/write-a-pod-manifest-663628?course=ckad-prep)                     |
|       5 | 🧩  Labels und Selektoren verwenden                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-labels-and-selectors-663626?course=ckad-prep)                 |
|       6 | 🧩  Manifeste mit kubectl generieren und bearbeiten | Anfänger        | [Labor Starten](https://labex.io/de/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep) |

#### Workload Design and Build

|   Index | Name                                                         | Schwierigkeit   | Übung                                                                                                          |
|---------|--------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Ein Deployment erstellen                                  | Anfänger        | [Labor Starten](https://labex.io/de/labs/create-a-deployment-663596?course=ckad-prep)                          |
|       2 | 🧩  Skalierung eines Deployments                              | Anfänger        | [Labor Starten](https://labex.io/de/labs/scale-a-deployment-663618?course=ckad-prep)                           |
|       3 | 🧩  Einmalige Jobs ausführen                                  | Anfänger        | [Labor Starten](https://labex.io/de/labs/run-one-time-jobs-663616?course=ckad-prep)                            |
|       4 | 🧩  CronJobs planen                                           | Anfänger        | [Labor Starten](https://labex.io/de/labs/schedule-cronjobs-663619?course=ckad-prep)                            |
|       5 | 🧩  Die richtige Workload-Ressource wählen                    | Anfänger        | [Labor Starten](https://labex.io/de/labs/choose-the-right-workload-resource-663592?course=ckad-prep)           |
|       6 | 🧩  Init-Container hinzufügen                                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/add-init-containers-663589?course=ckad-prep)                          |
|       7 | 🧩  Hinzufügen eines Sidecar-Containers                       | Anfänger        | [Labor Starten](https://labex.io/de/labs/add-a-sidecar-container-663588?course=ckad-prep)                      |
|       8 | 🧩  Verwendung von ephemeren und persistenten Volumes in Pods | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep) |

#### Configuration, Storage, and Runtime Settings

|   Index | Name                                               | Schwierigkeit   | Übung                                                                                                    |
|---------|----------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------|
|      01 | 🧩  Anwendungen mit ConfigMaps konfigurieren        | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-applications-with-configmaps-663593?course=ckad-prep) |
|      02 | 🧩  Anwendungen mit Secrets konfigurieren           | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-applications-with-secrets-663594?course=ckad-prep)    |
|      03 | 🧩  Umgebungsvariablen injizieren                   | Anfänger        | [Labor Starten](https://labex.io/de/labs/inject-environment-variables-663607?course=ckad-prep)           |
|      04 | 🧩  Konfigurationsdateien einbinden                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/mount-configuration-files-663609?course=ckad-prep)              |
|      05 | 🧩  Projected Volumes verwenden                     | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-projected-volumes-663627?course=ckad-prep)                  |
|      06 | 🧩  Ressourcenanforderungen und -limits festlegen   | Anfänger        | [Labor Starten](https://labex.io/de/labs/set-resource-requests-and-limits-663620?course=ckad-prep)       |
|      07 | 🧩  Namespace Resource Quotas anwenden              | Anfänger        | [Labor Starten](https://labex.io/de/labs/apply-namespace-resource-quotas-663590?course=ckad-prep)        |
|      08 | 🧩  Ausführung mit einem dedizierten ServiceAccount | Anfänger        | [Labor Starten](https://labex.io/de/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep)    |
|      09 | 🧩  Härtung eines Pod Security Context              | Anfänger        | [Labor Starten](https://labex.io/de/labs/harden-a-pod-security-context-663605?course=ckad-prep)          |
|      10 | 🧩  Eigene Ressourcen entdecken und nutzen          | Anfänger        | [Labor Starten](https://labex.io/de/labs/discover-and-use-custom-resources-663602?course=ckad-prep)      |

#### Deployment and Packaging

|   Index | Name                                                | Schwierigkeit   | Übung                                                                                                     |
|---------|-----------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Durchführung eines Rolling Updates               | Anfänger        | [Labor Starten](https://labex.io/de/labs/perform-a-rolling-update-663610?course=ckad-prep)                |
|       2 | 🧩  Roll Back a Faulty Deployment                    | Anfänger        | [Labor Starten](https://labex.io/de/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep)           |
|       3 | 🧩  Deployment-Update-Strategie anpassen             | Anfänger        | [Labor Starten](https://labex.io/de/labs/tune-deployment-update-strategy-663622?course=ckad-prep)         |
|       4 | 🧩  Implementierung eines Canary-Releases            | Anfänger        | [Labor Starten](https://labex.io/de/labs/implement-a-canary-release-663606?course=ckad-prep)              |
|       5 | 🧩  Blue-Green-Traffic umschalten                    | Anfänger        | [Labor Starten](https://labex.io/de/labs/switch-blue-green-traffic-663621?course=ckad-prep)               |
|       6 | 🧩  Bereitstellung eines lokalen Helm-Charts         | Anfänger        | [Labor Starten](https://labex.io/de/labs/deploy-a-local-helm-chart-663600?course=ckad-prep)               |
|       7 | 🧩  Anwendung mit Kustomize anpassen                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/customize-an-application-with-kustomize-663598?course=ckad-prep) |
|       8 | 🧩  Lokales Anwendungs-Image erstellen und ausführen | Anfänger        | [Labor Starten](https://labex.io/de/labs/build-and-run-a-local-application-image-663591?course=ckad-prep) |

#### Observability, Debugging, and App Networking

|   Index | Name                                                 | Schwierigkeit   | Übung                                                                                                             |
|---------|------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------------|
|      01 | 🧩  Logs und Events lesen                             | Anfänger        | [Labor Starten](https://labex.io/de/labs/read-logs-and-events-663611?course=ckad-prep)                            |
|      02 | 🧩  Debugging mit exec und Port Forwarding            | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep)      |
|      03 | 🧩  Liveness- und Readiness-Probes konfigurieren      | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep)         |
|      04 | 🧩  Fehlersuche bei einer CrashLooping-Anwendung      | Anfänger        | [Labor Starten](https://labex.io/de/labs/debug-a-crashlooping-application-663599?course=ckad-prep)                |
|      05 | 🧩  Veraltete API-Manifeste aktualisieren             | Anfänger        | [Labor Starten](https://labex.io/de/labs/update-deprecated-api-manifests-663623?course=ckad-prep)                 |
|      06 | 🧩  Ein Deployment mit einem Service verfügbar machen | Anfänger        | [Labor Starten](https://labex.io/de/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep)              |
|      07 | 🧩  Diagnose von Service-DNS-Zugriffen                | Anfänger        | [Labor Starten](https://labex.io/de/labs/diagnose-service-dns-access-663601?course=ckad-prep)                     |
|      08 | 🧩  HTTP-Traffic mit Ingress routen                   | Anfänger        | [Labor Starten](https://labex.io/de/labs/route-http-traffic-with-ingress-663615?course=ckad-prep)                 |
|      09 | 🧩  Anwendungsverkehr mit NetworkPolicy einschränken  | Anfänger        | [Labor Starten](https://labex.io/de/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep) |
|      10 | 🧩  Routing für benannte Service-Ports reparieren     | Anfänger        | [Labor Starten](https://labex.io/de/labs/repair-named-service-port-routing-663612?course=ckad-prep)               |

### 2. [CKAD-Übungsprüfung 01](https://labex.io/de/courses/ckad-practice-exam-01)

Eine praxisorientierte CKAD-Übungsprüfung mit 20 unabhängigen Herausforderungen zur Kubernetes-Anwendungsentwicklung. Die Themen umfassen Anwendungsdesign und -erstellung, Deployment, Observability und Wartung, Umgebungskonfiguration und Sicherheit sowie Services und Networking.

[Kurs Starten](https://labex.io/de/courses/ckad-practice-exam-01) · Labs: 20

#### Application Design and Build

|   Index | Name                                                 | Schwierigkeit   | Übung                                                                                                                     |
|---------|------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Lokales Anwendungs-Image erstellen und ausführen  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/build-and-run-a-local-application-image-663095?course=ckad-practice-exam-01) |
|       2 | 🎯  Erstellen eines geplanten Bereinigungs-CronJobs   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/create-a-scheduled-cleanup-cronjob-663098?course=ckad-practice-exam-01)      |
|       3 | 🎯  Init- und Sidecar-Container hinzufügen            | Anfänger        | [Challenge Starten](https://labex.io/de/labs/add-init-and-sidecar-containers-663093?course=ckad-practice-exam-01)         |
|       4 | 🎯  Verwendung von ephemeren und persistenten Volumes | Anfänger        | [Challenge Starten](https://labex.io/de/labs/use-ephemeral-and-persistent-volumes-663112?course=ckad-practice-exam-01)    |

#### Application Deployment

|   Index | Name                                             | Schwierigkeit   | Übung                                                                                                              |
|---------|--------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Sicheres Rolling Update durchführen           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/perform-a-safe-rolling-update-663106?course=ckad-practice-exam-01)    |
|       2 | 🎯  Implementierung eines Canary-Releases         | Anfänger        | [Challenge Starten](https://labex.io/de/labs/implement-a-canary-release-663104?course=ckad-practice-exam-01)       |
|       3 | 🎯  Bereitstellung einer gestuften Helm-Anwendung | Anfänger        | [Challenge Starten](https://labex.io/de/labs/deploy-a-staged-helm-application-663101?course=ckad-practice-exam-01) |
|       4 | 🎯  Anpassen einer App mit Kustomize              | Anfänger        | [Challenge Starten](https://labex.io/de/labs/customize-an-app-with-kustomize-663099?course=ckad-practice-exam-01)  |

#### Application Observability and Maintenance

|   Index | Name                                               | Schwierigkeit   | Übung                                                                                                              |
|---------|----------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Health Probes konfigurieren                     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/configure-health-probes-663096?course=ckad-practice-exam-01)          |
|       2 | 🎯  Fehlerbehebung bei einer CrashLooping-Anwendung | Anfänger        | [Challenge Starten](https://labex.io/de/labs/debug-a-crashlooping-application-663100?course=ckad-practice-exam-01) |
|       3 | 🎯  Veraltete Manifeste aktualisieren               | Anfänger        | [Challenge Starten](https://labex.io/de/labs/update-deprecated-manifests-663111?course=ckad-practice-exam-01)      |

#### Application Environment, Configuration and Security

|   Index | Name                                               | Schwierigkeit   | Übung                                                                                                                 |
|---------|----------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  ConfigMaps und Secrets injizieren               | Anfänger        | [Challenge Starten](https://labex.io/de/labs/inject-configmaps-and-secrets-663105?course=ckad-practice-exam-01)       |
|       2 | 🎯  Ressourcenanforderungen und Quotas anwenden     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/apply-resource-requests-and-quotas-663094?course=ckad-practice-exam-01)  |
|       3 | 🎯  Ausführung mit einem dedizierten ServiceAccount | Anfänger        | [Challenge Starten](https://labex.io/de/labs/run-with-a-dedicated-serviceaccount-663109?course=ckad-practice-exam-01) |
|       4 | 🎯  Härten eines Pod Security Context               | Anfänger        | [Challenge Starten](https://labex.io/de/labs/harden-a-pod-security-context-663103?course=ckad-practice-exam-01)       |
|       5 | 🎯  Erstellen einer App Custom Resource             | Anfänger        | [Challenge Starten](https://labex.io/de/labs/create-an-app-custom-resource-663097?course=ckad-practice-exam-01)       |

#### Services and Networking

|   Index | Name                                                 | Schwierigkeit   | Übung                                                                                                                     |
|---------|------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Ein Deployment mit einem Service verfügbar machen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/expose-a-deployment-with-a-service-663102?course=ckad-practice-exam-01)      |
|       2 | 🎯  HTTP-Datenverkehr mit Ingress routen              | Anfänger        | [Challenge Starten](https://labex.io/de/labs/route-http-traffic-with-ingress-663108?course=ckad-practice-exam-01)         |
|       3 | 🎯  App-Traffic mit NetworkPolicy einschränken        | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restrict-app-traffic-with-networkpolicy-663107?course=ckad-practice-exam-01) |
|       4 | 🎯  Fehlerbehebung beim Zugriff auf Service-Endpunkte | Anfänger        | [Challenge Starten](https://labex.io/de/labs/troubleshoot-service-endpoint-access-663110?course=ckad-practice-exam-01)    |

### 3. [CKAD-Übungsprüfung 02](https://labex.io/de/courses/ckad-practice-exam-02)

Eine zweite, unabhängige Übungsprüfung im CKAD-Stil mit 20 Kubernetes-Anwendungsentwicklungs-Herausforderungen, die die offiziellen CKAD-Themenbereiche anhand verschiedener operativer Szenarien abdecken.

[Kurs Starten](https://labex.io/de/courses/ckad-practice-exam-02) · Labs: 20

#### Application Design and Build

|   Index | Name                                           | Schwierigkeit   | Übung                                                                                                                 |
|---------|------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Lokales Worker-Image paketieren             | Anfänger        | [Challenge Starten](https://labex.io/de/labs/package-a-local-worker-image-663123?course=ckad-practice-exam-02)        |
|       2 | 🎯  Ausführen eines parallelen Daten-Jobs       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/run-a-parallel-data-job-663129?course=ckad-practice-exam-02)             |
|       3 | 🎯  Einen Adapter-Sidecar hinzufügen            | Anfänger        | [Challenge Starten](https://labex.io/de/labs/add-an-adapter-sidecar-663113?course=ckad-practice-exam-02)              |
|       4 | 🎯  Projizierte und persistente Daten einbinden | Anfänger        | [Challenge Starten](https://labex.io/de/labs/mount-projected-and-persistent-data-663122?course=ckad-practice-exam-02) |

#### Application Deployment

|   Index | Name                                             | Schwierigkeit   | Übung                                                                                                                     |
|---------|--------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Blue-Green-Traffic umschalten                 | Anfänger        | [Challenge Starten](https://labex.io/de/labs/switch-blue-green-traffic-663131?course=ckad-practice-exam-02)               |
|       2 | 🎯  Roll Back a Faulty Deployment                 | Anfänger        | [Challenge Starten](https://labex.io/de/labs/roll-back-a-faulty-deployment-663128?course=ckad-practice-exam-02)           |
|       3 | 🎯  Upgrade eines lokalen Helm-Releases           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/upgrade-a-local-helm-release-663132?course=ckad-practice-exam-02)            |
|       4 | 🎯  Erstellen eines Kustomize-Production-Overlays | Anfänger        | [Challenge Starten](https://labex.io/de/labs/generate-a-kustomize-production-overlay-663120?course=ckad-practice-exam-02) |

#### Application Observability and Maintenance

|   Index | Name                                               | Schwierigkeit   | Übung                                                                                                                  |
|---------|----------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Langsame Startup-Probes reparieren              | Anfänger        | [Challenge Starten](https://labex.io/de/labs/repair-slow-startup-probes-663127?course=ckad-practice-exam-02)           |
|       2 | 🎯  Fehlerhaftes Konfigurations-Rollout debuggen    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/debug-a-failed-config-rollout-663117?course=ckad-practice-exam-02)        |
|       3 | 🎯  Konvertierung eines veralteten Policy-Manifests | Anfänger        | [Challenge Starten](https://labex.io/de/labs/convert-a-deprecated-policy-manifest-663115?course=ckad-practice-exam-02) |

#### Application Environment, Configuration and Security

|   Index | Name                                            | Schwierigkeit   | Übung                                                                                                                 |
|---------|-------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Projektkonfiguration und Secret-Dateien      | Anfänger        | [Challenge Starten](https://labex.io/de/labs/project-config-and-secret-files-663124?course=ckad-practice-exam-02)     |
|       2 | 🎯  Namespace-Ressourcen-Standardwerte erzwingen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/enforce-namespace-resource-defaults-663119?course=ckad-practice-exam-02) |
|       3 | 🎯  Einschränkung eines App-ServiceAccount       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/limit-an-app-serviceaccount-663121?course=ckad-practice-exam-02)         |
|       4 | 🎯  Einen beschreibbaren Cache-Pod absichern     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/secure-a-writable-cache-pod-663130?course=ckad-practice-exam-02)         |
|       5 | 🎯  Erstellen einer versionierten App-Ressource  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/create-a-versioned-app-resource-663116?course=ckad-practice-exam-02)     |

#### Services and Networking

|   Index | Name                                             | Schwierigkeit   | Übung                                                                                                               |
|---------|--------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Routing für benannte Service-Ports reparieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/repair-named-service-port-routing-663126?course=ckad-practice-exam-02) |
|       2 | 🎯  Split-Pfade mit Ingress veröffentlichen       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/publish-split-paths-with-ingress-663125?course=ckad-practice-exam-02)  |
|       3 | 🎯  Datenverkehr aus einem Namespace zulassen     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/allow-traffic-from-one-namespace-663114?course=ckad-practice-exam-02)  |
|       4 | 🎯  Diagnose von Service-DNS-Zugriffen            | Anfänger        | [Challenge Starten](https://labex.io/de/labs/diagnose-service-dns-access-663118?course=ckad-practice-exam-02)       |

## Über LabEx

[LabEx](https://labex.io) ist eine interaktive, praktische Lernplattform für Programmierung und Technologie. Sie kombiniert Labore, KI-Unterstützung und virtuelle Maschinen für eine videofreie, praktische Lernerfahrung. Mit einem strikten 'Learning by Doing'-Ansatz, interaktiven Online-Umgebungen im Browser mit automatisierten Schritt-für-Schritt-Überprüfungen, strukturierter Inhaltsorganisation mit dem Skill-Tree-basierten System, und einer wachsenden Lernressource von 30 Skill Trees und über 6.000 Laboren, [LabEx](https://labex.io) bietet umfassende praktische Bildung. Die Plattform umfasst den Lernassistenten Labby, aufgebaut auf den neuesten KI-Modellen, der eine konversationelle Lernerfahrung bietet.

