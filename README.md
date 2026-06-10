# CKAD Training Certification Prep Path

## Languages

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/learn/ckad"><img width="128px" src="https://file.labex.io/path/izmE8twViI3a.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Start-Path-whitesmoke?style=for-the-badge)](https://labex.io/learn/ckad)

Prepare for the Certified Kubernetes Application Developer (CKAD) exam with a structured, hands-on learning path. This roadmap focuses on practical Kubernetes application design and build, deployment, observability and maintenance, configuration and security, and services and networking, plus performance-based exam tasks and real-world cloud-native scenarios. Guided CKAD courses, labs, and mock exam practice will be added over time to help you build skills aligned with CKAD objectives.

**Courses**: 3 · **Labs**: 82

## Courses

### 1. [CKAD Prep](https://labex.io/courses/ckad-prep)

[![CKAD Prep](https://course-cover.labex.io/ckad-prep.png)](https://labex.io/courses/ckad-prep)

A beginner-friendly CKAD preparation course with 42 guided Kubernetes application development labs arranged from kubectl and object fundamentals to workloads, configuration, deployment, observability, and networking.

[Start Course](https://labex.io/courses/ckad-prep) · Labs: 42

#### Kubernetes Application Foundations

|   Index | Name                                         | Difficulty   | Practice                                                                                            |
|---------|----------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------|
|       1 | 🧩  Explore kubectl, Contexts, and Namespaces | Beginner     | [Start Lab](https://labex.io/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep)  |
|       2 | 🧩  Inspect Kubernetes API Resources          | Beginner     | [Start Lab](https://labex.io/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep)         |
|       3 | 🧩  Create and Inspect a Pod                  | Beginner     | [Start Lab](https://labex.io/labs/create-and-inspect-a-pod-663597?course=ckad-prep)                 |
|       4 | 🧩  Write a Pod Manifest                      | Beginner     | [Start Lab](https://labex.io/labs/write-a-pod-manifest-663628?course=ckad-prep)                     |
|       5 | 🧩  Use Labels and Selectors                  | Beginner     | [Start Lab](https://labex.io/labs/use-labels-and-selectors-663626?course=ckad-prep)                 |
|       6 | 🧩  Generate and Edit Manifests with kubectl  | Beginner     | [Start Lab](https://labex.io/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep) |

#### Workload Design and Build

|   Index | Name                                            | Difficulty   | Practice                                                                                                |
|---------|-------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Create a Deployment                          | Beginner     | [Start Lab](https://labex.io/labs/create-a-deployment-663596?course=ckad-prep)                          |
|       2 | 🧩  Scale a Deployment                           | Beginner     | [Start Lab](https://labex.io/labs/scale-a-deployment-663618?course=ckad-prep)                           |
|       3 | 🧩  Run One-Time Jobs                            | Beginner     | [Start Lab](https://labex.io/labs/run-one-time-jobs-663616?course=ckad-prep)                            |
|       4 | 🧩  Schedule CronJobs                            | Beginner     | [Start Lab](https://labex.io/labs/schedule-cronjobs-663619?course=ckad-prep)                            |
|       5 | 🧩  Choose the Right Workload Resource           | Beginner     | [Start Lab](https://labex.io/labs/choose-the-right-workload-resource-663592?course=ckad-prep)           |
|       6 | 🧩  Add Init Containers                          | Beginner     | [Start Lab](https://labex.io/labs/add-init-containers-663589?course=ckad-prep)                          |
|       7 | 🧩  Add a Sidecar Container                      | Beginner     | [Start Lab](https://labex.io/labs/add-a-sidecar-container-663588?course=ckad-prep)                      |
|       8 | 🧩  Use Ephemeral and Persistent Volumes in Pods | Beginner     | [Start Lab](https://labex.io/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep) |

#### Configuration, Storage, and Runtime Settings

|   Index | Name                                      | Difficulty   | Practice                                                                                          |
|---------|-------------------------------------------|--------------|---------------------------------------------------------------------------------------------------|
|      01 | 🧩  Configure Applications with ConfigMaps | Beginner     | [Start Lab](https://labex.io/labs/configure-applications-with-configmaps-663593?course=ckad-prep) |
|      02 | 🧩  Configure Applications with Secrets    | Beginner     | [Start Lab](https://labex.io/labs/configure-applications-with-secrets-663594?course=ckad-prep)    |
|      03 | 🧩  Inject Environment Variables           | Beginner     | [Start Lab](https://labex.io/labs/inject-environment-variables-663607?course=ckad-prep)           |
|      04 | 🧩  Mount Configuration Files              | Beginner     | [Start Lab](https://labex.io/labs/mount-configuration-files-663609?course=ckad-prep)              |
|      05 | 🧩  Use Projected Volumes                  | Beginner     | [Start Lab](https://labex.io/labs/use-projected-volumes-663627?course=ckad-prep)                  |
|      06 | 🧩  Set Resource Requests and Limits       | Beginner     | [Start Lab](https://labex.io/labs/set-resource-requests-and-limits-663620?course=ckad-prep)       |
|      07 | 🧩  Apply Namespace Resource Quotas        | Beginner     | [Start Lab](https://labex.io/labs/apply-namespace-resource-quotas-663590?course=ckad-prep)        |
|      08 | 🧩  Run with a Dedicated ServiceAccount    | Beginner     | [Start Lab](https://labex.io/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep)    |
|      09 | 🧩  Harden a Pod Security Context          | Beginner     | [Start Lab](https://labex.io/labs/harden-a-pod-security-context-663605?course=ckad-prep)          |
|      10 | 🧩  Discover and Use Custom Resources      | Beginner     | [Start Lab](https://labex.io/labs/discover-and-use-custom-resources-663602?course=ckad-prep)      |

#### Deployment and Packaging

|   Index | Name                                       | Difficulty   | Practice                                                                                           |
|---------|--------------------------------------------|--------------|----------------------------------------------------------------------------------------------------|
|       1 | 🧩  Perform a Rolling Update                | Beginner     | [Start Lab](https://labex.io/labs/perform-a-rolling-update-663610?course=ckad-prep)                |
|       2 | 🧩  Roll Back a Faulty Deployment           | Beginner     | [Start Lab](https://labex.io/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep)           |
|       3 | 🧩  Tune Deployment Update Strategy         | Beginner     | [Start Lab](https://labex.io/labs/tune-deployment-update-strategy-663622?course=ckad-prep)         |
|       4 | 🧩  Implement a Canary Release              | Beginner     | [Start Lab](https://labex.io/labs/implement-a-canary-release-663606?course=ckad-prep)              |
|       5 | 🧩  Switch Blue-Green Traffic               | Beginner     | [Start Lab](https://labex.io/labs/switch-blue-green-traffic-663621?course=ckad-prep)               |
|       6 | 🧩  Deploy a Local Helm Chart               | Beginner     | [Start Lab](https://labex.io/labs/deploy-a-local-helm-chart-663600?course=ckad-prep)               |
|       7 | 🧩  Customize an Application with Kustomize | Beginner     | [Start Lab](https://labex.io/labs/customize-an-application-with-kustomize-663598?course=ckad-prep) |
|       8 | 🧩  Build and Run a Local Application Image | Beginner     | [Start Lab](https://labex.io/labs/build-and-run-a-local-application-image-663591?course=ckad-prep) |

#### Observability, Debugging, and App Networking

|   Index | Name                                               | Difficulty   | Practice                                                                                                   |
|---------|----------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------|
|      01 | 🧩  Read Logs and Events                            | Beginner     | [Start Lab](https://labex.io/labs/read-logs-and-events-663611?course=ckad-prep)                            |
|      02 | 🧩  Use exec and Port Forwarding for Debugging      | Beginner     | [Start Lab](https://labex.io/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep)      |
|      03 | 🧩  Configure Liveness and Readiness Probes         | Beginner     | [Start Lab](https://labex.io/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep)         |
|      04 | 🧩  Debug a CrashLooping Application                | Beginner     | [Start Lab](https://labex.io/labs/debug-a-crashlooping-application-663599?course=ckad-prep)                |
|      05 | 🧩  Update Deprecated API Manifests                 | Beginner     | [Start Lab](https://labex.io/labs/update-deprecated-api-manifests-663623?course=ckad-prep)                 |
|      06 | 🧩  Expose a Deployment with a Service              | Beginner     | [Start Lab](https://labex.io/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep)              |
|      07 | 🧩  Diagnose Service DNS Access                     | Beginner     | [Start Lab](https://labex.io/labs/diagnose-service-dns-access-663601?course=ckad-prep)                     |
|      08 | 🧩  Route HTTP Traffic with Ingress                 | Beginner     | [Start Lab](https://labex.io/labs/route-http-traffic-with-ingress-663615?course=ckad-prep)                 |
|      09 | 🧩  Restrict Application Traffic with NetworkPolicy | Beginner     | [Start Lab](https://labex.io/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep) |
|      10 | 🧩  Repair Named Service Port Routing               | Beginner     | [Start Lab](https://labex.io/labs/repair-named-service-port-routing-663612?course=ckad-prep)               |

### 2. [CKAD Practice Exam 01](https://labex.io/courses/ckad-practice-exam-01)

[![CKAD Practice Exam 01](https://course-cover.labex.io/ckad-practice-exam-01.png)](https://labex.io/courses/ckad-practice-exam-01)

A hands-on CKAD practice exam with 20 independent Kubernetes application development challenges covering application design and build, deployment, observability and maintenance, environment configuration and security, and services and networking.

[Start Course](https://labex.io/courses/ckad-practice-exam-01) · Labs: 20

#### Application Design and Build

|   Index | Name                                       | Difficulty   | Practice                                                                                                             |
|---------|--------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Build and Run a Local Application Image | Beginner     | [Start Challenge](https://labex.io/labs/build-and-run-a-local-application-image-663095?course=ckad-practice-exam-01) |
|       2 | 🎯  Create a Scheduled Cleanup CronJob      | Beginner     | [Start Challenge](https://labex.io/labs/create-a-scheduled-cleanup-cronjob-663098?course=ckad-practice-exam-01)      |
|       3 | 🎯  Add Init and Sidecar Containers         | Beginner     | [Start Challenge](https://labex.io/labs/add-init-and-sidecar-containers-663093?course=ckad-practice-exam-01)         |
|       4 | 🎯  Use Ephemeral and Persistent Volumes    | Beginner     | [Start Challenge](https://labex.io/labs/use-ephemeral-and-persistent-volumes-663112?course=ckad-practice-exam-01)    |

#### Application Deployment

|   Index | Name                                | Difficulty   | Practice                                                                                                      |
|---------|-------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Perform a Safe Rolling Update    | Beginner     | [Start Challenge](https://labex.io/labs/perform-a-safe-rolling-update-663106?course=ckad-practice-exam-01)    |
|       2 | 🎯  Implement a Canary Release       | Beginner     | [Start Challenge](https://labex.io/labs/implement-a-canary-release-663104?course=ckad-practice-exam-01)       |
|       3 | 🎯  Deploy a Staged Helm Application | Beginner     | [Start Challenge](https://labex.io/labs/deploy-a-staged-helm-application-663101?course=ckad-practice-exam-01) |
|       4 | 🎯  Customize an App with Kustomize  | Beginner     | [Start Challenge](https://labex.io/labs/customize-an-app-with-kustomize-663099?course=ckad-practice-exam-01)  |

#### Application Observability and Maintenance

|   Index | Name                                | Difficulty   | Practice                                                                                                      |
|---------|-------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Configure Health Probes          | Beginner     | [Start Challenge](https://labex.io/labs/configure-health-probes-663096?course=ckad-practice-exam-01)          |
|       2 | 🎯  Debug a CrashLooping Application | Beginner     | [Start Challenge](https://labex.io/labs/debug-a-crashlooping-application-663100?course=ckad-practice-exam-01) |
|       3 | 🎯  Update Deprecated Manifests      | Beginner     | [Start Challenge](https://labex.io/labs/update-deprecated-manifests-663111?course=ckad-practice-exam-01)      |

#### Application Environment, Configuration and Security

|   Index | Name                                   | Difficulty   | Practice                                                                                                         |
|---------|----------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Inject ConfigMaps and Secrets       | Beginner     | [Start Challenge](https://labex.io/labs/inject-configmaps-and-secrets-663105?course=ckad-practice-exam-01)       |
|       2 | 🎯  Apply Resource Requests and Quotas  | Beginner     | [Start Challenge](https://labex.io/labs/apply-resource-requests-and-quotas-663094?course=ckad-practice-exam-01)  |
|       3 | 🎯  Run with a Dedicated ServiceAccount | Beginner     | [Start Challenge](https://labex.io/labs/run-with-a-dedicated-serviceaccount-663109?course=ckad-practice-exam-01) |
|       4 | 🎯  Harden a Pod Security Context       | Beginner     | [Start Challenge](https://labex.io/labs/harden-a-pod-security-context-663103?course=ckad-practice-exam-01)       |
|       5 | 🎯  Create an App Custom Resource       | Beginner     | [Start Challenge](https://labex.io/labs/create-an-app-custom-resource-663097?course=ckad-practice-exam-01)       |

#### Services and Networking

|   Index | Name                                       | Difficulty   | Practice                                                                                                             |
|---------|--------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Expose a Deployment with a Service      | Beginner     | [Start Challenge](https://labex.io/labs/expose-a-deployment-with-a-service-663102?course=ckad-practice-exam-01)      |
|       2 | 🎯  Route HTTP Traffic with Ingress         | Beginner     | [Start Challenge](https://labex.io/labs/route-http-traffic-with-ingress-663108?course=ckad-practice-exam-01)         |
|       3 | 🎯  Restrict App Traffic with NetworkPolicy | Beginner     | [Start Challenge](https://labex.io/labs/restrict-app-traffic-with-networkpolicy-663107?course=ckad-practice-exam-01) |
|       4 | 🎯  Troubleshoot Service Endpoint Access    | Beginner     | [Start Challenge](https://labex.io/labs/troubleshoot-service-endpoint-access-663110?course=ckad-practice-exam-01)    |

### 3. [CKAD Practice Exam 02](https://labex.io/courses/ckad-practice-exam-02)

[![CKAD Practice Exam 02](https://course-cover.labex.io/ckad-practice-exam-02.png)](https://labex.io/courses/ckad-practice-exam-02)

A second independent CKAD-style practice exam with 20 Kubernetes application development challenges covering the public CKAD domains through different operational scenarios.

[Start Course](https://labex.io/courses/ckad-practice-exam-02) · Labs: 20

#### Application Design and Build

|   Index | Name                                   | Difficulty   | Practice                                                                                                         |
|---------|----------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Package a Local Worker Image        | Beginner     | [Start Challenge](https://labex.io/labs/package-a-local-worker-image-663123?course=ckad-practice-exam-02)        |
|       2 | 🎯  Run a Parallel Data Job             | Beginner     | [Start Challenge](https://labex.io/labs/run-a-parallel-data-job-663129?course=ckad-practice-exam-02)             |
|       3 | 🎯  Add an Adapter Sidecar              | Beginner     | [Start Challenge](https://labex.io/labs/add-an-adapter-sidecar-663113?course=ckad-practice-exam-02)              |
|       4 | 🎯  Mount Projected and Persistent Data | Beginner     | [Start Challenge](https://labex.io/labs/mount-projected-and-persistent-data-663122?course=ckad-practice-exam-02) |

#### Application Deployment

|   Index | Name                                       | Difficulty   | Practice                                                                                                             |
|---------|--------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Switch Blue Green Traffic               | Beginner     | [Start Challenge](https://labex.io/labs/switch-blue-green-traffic-663131?course=ckad-practice-exam-02)               |
|       2 | 🎯  Roll Back a Faulty Deployment           | Beginner     | [Start Challenge](https://labex.io/labs/roll-back-a-faulty-deployment-663128?course=ckad-practice-exam-02)           |
|       3 | 🎯  Upgrade a Local Helm Release            | Beginner     | [Start Challenge](https://labex.io/labs/upgrade-a-local-helm-release-663132?course=ckad-practice-exam-02)            |
|       4 | 🎯  Generate a Kustomize Production Overlay | Beginner     | [Start Challenge](https://labex.io/labs/generate-a-kustomize-production-overlay-663120?course=ckad-practice-exam-02) |

#### Application Observability and Maintenance

|   Index | Name                                    | Difficulty   | Practice                                                                                                          |
|---------|-----------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Repair Slow Startup Probes           | Beginner     | [Start Challenge](https://labex.io/labs/repair-slow-startup-probes-663127?course=ckad-practice-exam-02)           |
|       2 | 🎯  Debug a Failed Config Rollout        | Beginner     | [Start Challenge](https://labex.io/labs/debug-a-failed-config-rollout-663117?course=ckad-practice-exam-02)        |
|       3 | 🎯  Convert a Deprecated Policy Manifest | Beginner     | [Start Challenge](https://labex.io/labs/convert-a-deprecated-policy-manifest-663115?course=ckad-practice-exam-02) |

#### Application Environment, Configuration and Security

|   Index | Name                                   | Difficulty   | Practice                                                                                                         |
|---------|----------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Project Config and Secret Files     | Beginner     | [Start Challenge](https://labex.io/labs/project-config-and-secret-files-663124?course=ckad-practice-exam-02)     |
|       2 | 🎯  Enforce Namespace Resource Defaults | Beginner     | [Start Challenge](https://labex.io/labs/enforce-namespace-resource-defaults-663119?course=ckad-practice-exam-02) |
|       3 | 🎯  Limit an App ServiceAccount         | Beginner     | [Start Challenge](https://labex.io/labs/limit-an-app-serviceaccount-663121?course=ckad-practice-exam-02)         |
|       4 | 🎯  Secure a Writable Cache Pod         | Beginner     | [Start Challenge](https://labex.io/labs/secure-a-writable-cache-pod-663130?course=ckad-practice-exam-02)         |
|       5 | 🎯  Create a Versioned App Resource     | Beginner     | [Start Challenge](https://labex.io/labs/create-a-versioned-app-resource-663116?course=ckad-practice-exam-02)     |

#### Services and Networking

|   Index | Name                                 | Difficulty   | Practice                                                                                                       |
|---------|--------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Repair Named Service Port Routing | Beginner     | [Start Challenge](https://labex.io/labs/repair-named-service-port-routing-663126?course=ckad-practice-exam-02) |
|       2 | 🎯  Publish Split Paths with Ingress  | Beginner     | [Start Challenge](https://labex.io/labs/publish-split-paths-with-ingress-663125?course=ckad-practice-exam-02)  |
|       3 | 🎯  Allow Traffic from One Namespace  | Beginner     | [Start Challenge](https://labex.io/labs/allow-traffic-from-one-namespace-663114?course=ckad-practice-exam-02)  |
|       4 | 🎯  Diagnose Service DNS Access       | Beginner     | [Start Challenge](https://labex.io/labs/diagnose-service-dns-access-663118?course=ckad-practice-exam-02)       |

## About LabEx

[LabEx](https://labex.io) is an interactive, hands-on learning platform dedicated to coding and technology. It combines labs, AI assistance, and virtual machines to provide a no-video, practical learning experience. With a strict 'Learn by Doing' approach, interactive online environments in the browser with automated step-by-step checks, structured content organization through the [Skill Tree](https://labex.io/learn) learning system, and a growing resource of 30 Skill Trees and over 6,000 Labs, [LabEx](https://labex.io) offers comprehensive practical education. The platform includes Labby, an AI learning assistant built on latest AI models, providing a conversational learning experience.

