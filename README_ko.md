# CKAD 교육 인증 준비 경로

## 언어

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/ko/learn/ckad"><img width="128px" src="https://file.labex.io/path/izmE8twViI3a.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/경로-시작-whitesmoke?style=for-the-badge)](https://labex.io/ko/learn/ckad)

Certified Kubernetes Application Developer(CKAD) 시험을 위해 구조화된 실습 중심 학습 경로로 준비하세요. Kubernetes에서 애플리케이션 설계 및 구축, 배포, 관측성 및 유지보수, 구성 및 보안, 서비스 및 네트워킹, CKAD 형태의 성능 기반 작업, 현실 시나리오에 초점을 맞춥니다. CKAD 과정, 랩, 모의고사 연습이 단계적으로 추가됩니다.

**코스**: 3 · **실습**: 82

## 코스

### 1. [CKAD 준비 과정](https://labex.io/ko/courses/ckad-prep)

kubectl 및 오브젝트 기초부터 워크로드, 구성, 배포, 관측 가능성, 네트워킹까지 42개의 가이드형 Kubernetes 애플리케이션 개발 실습으로 구성된 초보자 맞춤형 CKAD 준비 과정입니다.

[코스 시작](https://labex.io/ko/courses/ckad-prep) · 실습: 42

#### Kubernetes Application Foundations

|   인덱스 | 이름                                | 난이도   | 연습                                                                                                 |
|-------|-----------------------------------|-------|----------------------------------------------------------------------------------------------------|
|     1 | 🧩  kubectl, 컨텍스트 및 네임스페이스 탐색      | 초급    | [실습 시작](https://labex.io/ko/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep)  |
|     2 | 🧩  Kubernetes API 리소스 검사          | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep)         |
|     3 | 🧩  Pod 생성 및 검사                    | 초급    | [실습 시작](https://labex.io/ko/labs/create-and-inspect-a-pod-663597?course=ckad-prep)                 |
|     4 | 🧩  Pod 매니페스트 작성하기                 | 초급    | [실습 시작](https://labex.io/ko/labs/write-a-pod-manifest-663628?course=ckad-prep)                     |
|     5 | 🧩  레이블 및 셀렉터 사용하기                 | 초급    | [실습 시작](https://labex.io/ko/labs/use-labels-and-selectors-663626?course=ckad-prep)                 |
|     6 | 🧩  kubectl 을 사용하여 매니페스트 생성 및 편집하기 | 초급    | [실습 시작](https://labex.io/ko/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep) |

#### Workload Design and Build

|   인덱스 | 이름                                       | 난이도   | 연습                                                                                                     |
|-------|------------------------------------------|-------|--------------------------------------------------------------------------------------------------------|
|     1 | 🧩  디플로이먼트 (Deployment) 생성하기              | 초급    | [실습 시작](https://labex.io/ko/labs/create-a-deployment-663596?course=ckad-prep)                          |
|     2 | 🧩  Deployment 스케일링                       | 초급    | [실습 시작](https://labex.io/ko/labs/scale-a-deployment-663618?course=ckad-prep)                           |
|     3 | 🧩  일회성 작업 (Job) 실행하기                     | 초급    | [실습 시작](https://labex.io/ko/labs/run-one-time-jobs-663616?course=ckad-prep)                            |
|     4 | 🧩  CronJob 스케줄링                          | 초급    | [실습 시작](https://labex.io/ko/labs/schedule-cronjobs-663619?course=ckad-prep)                            |
|     5 | 🧩  올바른 워크로드 리소스 선택하기                     | 초급    | [실습 시작](https://labex.io/ko/labs/choose-the-right-workload-resource-663592?course=ckad-prep)           |
|     6 | 🧩  Init 컨테이너 추가하기                        | 초급    | [실습 시작](https://labex.io/ko/labs/add-init-containers-663589?course=ckad-prep)                          |
|     7 | 🧩  사이드카 컨테이너 추가하기                        | 초급    | [실습 시작](https://labex.io/ko/labs/add-a-sidecar-container-663588?course=ckad-prep)                      |
|     8 | 🧩  Pod 에서 Ephemeral 및 Persistent 볼륨 사용하기 | 초급    | [실습 시작](https://labex.io/ko/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep) |

#### Configuration, Storage, and Runtime Settings

|   인덱스 | 이름                                       | 난이도   | 연습                                                                                               |
|-------|------------------------------------------|-------|--------------------------------------------------------------------------------------------------|
|    01 | 🧩  ConfigMap 을 사용한 애플리케이션 구성             | 초급    | [실습 시작](https://labex.io/ko/labs/configure-applications-with-configmaps-663593?course=ckad-prep) |
|    02 | 🧩  Secret 을 사용한 애플리케이션 구성                | 초급    | [실습 시작](https://labex.io/ko/labs/configure-applications-with-secrets-663594?course=ckad-prep)    |
|    03 | 🧩  환경 변수 주입                              | 초급    | [실습 시작](https://labex.io/ko/labs/inject-environment-variables-663607?course=ckad-prep)           |
|    04 | 🧩  구성 파일 마운트                             | 초급    | [실습 시작](https://labex.io/ko/labs/mount-configuration-files-663609?course=ckad-prep)              |
|    05 | 🧩  Projected Volume 사용하기                 | 초급    | [실습 시작](https://labex.io/ko/labs/use-projected-volumes-663627?course=ckad-prep)                  |
|    06 | 🧩  리소스 요청 및 제한 설정                        | 초급    | [실습 시작](https://labex.io/ko/labs/set-resource-requests-and-limits-663620?course=ckad-prep)       |
|    07 | 🧩  네임스페이스 리소스 쿼터 (Resource Quota) 적용     | 초급    | [실습 시작](https://labex.io/ko/labs/apply-namespace-resource-quotas-663590?course=ckad-prep)        |
|    08 | 🧩  전용 서비스 계정 (ServiceAccount) 으로 실행하기    | 초급    | [실습 시작](https://labex.io/ko/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep)    |
|    09 | 🧩  Pod 보안 컨텍스트 (Security Context) 강화     | 초급    | [실습 시작](https://labex.io/ko/labs/harden-a-pod-security-context-663605?course=ckad-prep)          |
|    10 | 🧩  사용자 정의 리소스 (Custom Resources) 발견 및 사용 | 초급    | [실습 시작](https://labex.io/ko/labs/discover-and-use-custom-resources-663602?course=ckad-prep)      |

#### Deployment and Packaging

|   인덱스 | 이름                               | 난이도   | 연습                                                                                                |
|-------|----------------------------------|-------|---------------------------------------------------------------------------------------------------|
|     1 | 🧩  롤링 업데이트 수행                    | 초급    | [실습 시작](https://labex.io/ko/labs/perform-a-rolling-update-663610?course=ckad-prep)                |
|     2 | 🧩  결함이 있는 배포 롤백하기                | 초급    | [실습 시작](https://labex.io/ko/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep)           |
|     3 | 🧩  배포 업데이트 전략 조정                 | 초급    | [실습 시작](https://labex.io/ko/labs/tune-deployment-update-strategy-663622?course=ckad-prep)         |
|     4 | 🧩  카나리 릴리스 (Canary Release) 구현   | 초급    | [실습 시작](https://labex.io/ko/labs/implement-a-canary-release-663606?course=ckad-prep)              |
|     5 | 🧩  블루 - 그린 트래픽 전환                | 초급    | [실습 시작](https://labex.io/ko/labs/switch-blue-green-traffic-663621?course=ckad-prep)               |
|     6 | 🧩  로컬 Helm 차트 배포                 | 초급    | [실습 시작](https://labex.io/ko/labs/deploy-a-local-helm-chart-663600?course=ckad-prep)               |
|     7 | 🧩  Kustomize 를 사용한 애플리케이션 커스터마이징 | 초급    | [실습 시작](https://labex.io/ko/labs/customize-an-application-with-kustomize-663598?course=ckad-prep) |
|     8 | 🧩  로컬 애플리케이션 이미지 빌드 및 실행         | 초급    | [실습 시작](https://labex.io/ko/labs/build-and-run-a-local-application-image-663591?course=ckad-prep) |

#### Observability, Debugging, and App Networking

|   인덱스 | 이름                                   | 난이도   | 연습                                                                                                        |
|-------|--------------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|    01 | 🧩  로그 및 이벤트 읽기                       | 초급    | [실습 시작](https://labex.io/ko/labs/read-logs-and-events-663611?course=ckad-prep)                            |
|    02 | 🧩  exec 및 포트 포워딩을 이용한 디버깅            | 초급    | [실습 시작](https://labex.io/ko/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep)      |
|    03 | 🧩  Liveness 및 Readiness 프로브 구성       | 초급    | [실습 시작](https://labex.io/ko/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep)         |
|    04 | 🧩  CrashLooping 애플리케이션 디버깅           | 초급    | [실습 시작](https://labex.io/ko/labs/debug-a-crashlooping-application-663599?course=ckad-prep)                |
|    05 | 🧩  사용 중단된 API 매니페스트 업데이트             | 초급    | [실습 시작](https://labex.io/ko/labs/update-deprecated-api-manifests-663623?course=ckad-prep)                 |
|    06 | 🧩  Service 를 사용하여 Deployment 노출하기    | 초급    | [실습 시작](https://labex.io/ko/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep)              |
|    07 | 🧩  Service DNS 액세스 진단                | 초급    | [실습 시작](https://labex.io/ko/labs/diagnose-service-dns-access-663601?course=ckad-prep)                     |
|    08 | 🧩  Ingress 를 이용한 HTTP 트래픽 라우팅        | 초급    | [실습 시작](https://labex.io/ko/labs/route-http-traffic-with-ingress-663615?course=ckad-prep)                 |
|    09 | 🧩  NetworkPolicy 를 사용한 애플리케이션 트래픽 제한 | 초급    | [실습 시작](https://labex.io/ko/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep) |
|    10 | 🧩  Named Service 포트 라우팅 복구           | 초급    | [실습 시작](https://labex.io/ko/labs/repair-named-service-port-routing-663612?course=ckad-prep)               |

### 2. [CKAD 실전 모의고사 01](https://labex.io/ko/courses/ckad-practice-exam-01)

애플리케이션 설계 및 빌드, 배포, 관찰 가능성 및 유지보수, 환경 구성 및 보안, 서비스 및 네트워킹 등 CKAD 의 핵심 영역을 다루는 20 개의 독립적인 쿠버네티스 애플리케이션 개발 챌린지로 구성된 실습형 모의고사입니다.

[코스 시작](https://labex.io/ko/courses/ckad-practice-exam-01) · 실습: 20

#### Application Design and Build

|   인덱스 | 이름                        | 난이도   | 연습                                                                                                            |
|-------|---------------------------|-------|---------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  로컬 애플리케이션 이미지 빌드 및 실행  | 초급    | [도전 시작](https://labex.io/ko/labs/build-and-run-a-local-application-image-663095?course=ckad-practice-exam-01) |
|     2 | 🎯  예약된 정리 CronJob 생성      | 초급    | [도전 시작](https://labex.io/ko/labs/create-a-scheduled-cleanup-cronjob-663098?course=ckad-practice-exam-01)      |
|     3 | 🎯  Init 및 Sidecar 컨테이너 추가 | 초급    | [도전 시작](https://labex.io/ko/labs/add-init-and-sidecar-containers-663093?course=ckad-practice-exam-01)         |
|     4 | 🎯  임시 및 영구 볼륨 사용          | 초급    | [도전 시작](https://labex.io/ko/labs/use-ephemeral-and-persistent-volumes-663112?course=ckad-practice-exam-01)    |

#### Application Deployment

|   인덱스 | 이름                               | 난이도   | 연습                                                                                                     |
|-------|----------------------------------|-------|--------------------------------------------------------------------------------------------------------|
|     1 | 🎯  안전한 롤링 업데이트 수행                | 초급    | [도전 시작](https://labex.io/ko/labs/perform-a-safe-rolling-update-663106?course=ckad-practice-exam-01)    |
|     2 | 🎯  카나리 릴리스 구현                    | 초급    | [도전 시작](https://labex.io/ko/labs/implement-a-canary-release-663104?course=ckad-practice-exam-01)       |
|     3 | 🎯  스테이징된 Helm 애플리케이션 배포          | 초급    | [도전 시작](https://labex.io/ko/labs/deploy-a-staged-helm-application-663101?course=ckad-practice-exam-01) |
|     4 | 🎯  Kustomize 를 사용한 애플리케이션 커스터마이징 | 초급    | [도전 시작](https://labex.io/ko/labs/customize-an-app-with-kustomize-663099?course=ckad-practice-exam-01)  |

#### Application Observability and Maintenance

|   인덱스 | 이름                           | 난이도   | 연습                                                                                                     |
|-------|------------------------------|-------|--------------------------------------------------------------------------------------------------------|
|     1 | 🎯  상태 프로브 (Health Probes) 구성 | 초급    | [도전 시작](https://labex.io/ko/labs/configure-health-probes-663096?course=ckad-practice-exam-01)          |
|     2 | 🎯  CrashLooping 애플리케이션 디버깅   | 초급    | [도전 시작](https://labex.io/ko/labs/debug-a-crashlooping-application-663100?course=ckad-practice-exam-01) |
|     3 | 🎯  지원 중단된 매니페스트 업데이트         | 초급    | [도전 시작](https://labex.io/ko/labs/update-deprecated-manifests-663111?course=ckad-practice-exam-01)      |

#### Application Environment, Configuration and Security

|   인덱스 | 이름                          | 난이도   | 연습                                                                                                        |
|-------|-----------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|     1 | 🎯  ConfigMap 및 Secret 주입    | 초급    | [도전 시작](https://labex.io/ko/labs/inject-configmaps-and-secrets-663105?course=ckad-practice-exam-01)       |
|     2 | 🎯  리소스 요청 및 쿼터 적용           | 초급    | [도전 시작](https://labex.io/ko/labs/apply-resource-requests-and-quotas-663094?course=ckad-practice-exam-01)  |
|     3 | 🎯  전용 ServiceAccount 로 실행하기 | 초급    | [도전 시작](https://labex.io/ko/labs/run-with-a-dedicated-serviceaccount-663109?course=ckad-practice-exam-01) |
|     4 | 🎯  Pod 보안 컨텍스트 강화           | 초급    | [도전 시작](https://labex.io/ko/labs/harden-a-pod-security-context-663103?course=ckad-practice-exam-01)       |
|     5 | 🎯  앱 커스텀 리소스 생성             | 초급    | [도전 시작](https://labex.io/ko/labs/create-an-app-custom-resource-663097?course=ckad-practice-exam-01)       |

#### Services and Networking

|   인덱스 | 이름                                 | 난이도   | 연습                                                                                                            |
|-------|------------------------------------|-------|---------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  Service 를 사용하여 Deployment 노출하기  | 초급    | [도전 시작](https://labex.io/ko/labs/expose-a-deployment-with-a-service-663102?course=ckad-practice-exam-01)      |
|     2 | 🎯  Ingress 를 통한 HTTP 트래픽 라우팅       | 초급    | [도전 시작](https://labex.io/ko/labs/route-http-traffic-with-ingress-663108?course=ckad-practice-exam-01)         |
|     3 | 🎯  NetworkPolicy 를 사용하여 앱 트래픽 제한하기 | 초급    | [도전 시작](https://labex.io/ko/labs/restrict-app-traffic-with-networkpolicy-663107?course=ckad-practice-exam-01) |
|     4 | 🎯  서비스 엔드포인트 액세스 문제 해결             | 초급    | [도전 시작](https://labex.io/ko/labs/troubleshoot-service-endpoint-access-663110?course=ckad-practice-exam-01)    |

### 3. [CKAD 실전 모의고사 02](https://labex.io/ko/courses/ckad-practice-exam-02)

CKAD 시험 영역을 포괄하는 20 개의 쿠버네티스 애플리케이션 개발 도전 과제로 구성된 두 번째 실전 모의고사입니다. 다양한 운영 시나리오를 통해 실무 역량을 점검할 수 있습니다.

[코스 시작](https://labex.io/ko/courses/ckad-practice-exam-02) · 실습: 20

#### Application Design and Build

|   인덱스 | 이름                                | 난이도   | 연습                                                                                                        |
|-------|-----------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|     1 | 🎯  로컬 워커 이미지 패키징                  | 초급    | [도전 시작](https://labex.io/ko/labs/package-a-local-worker-image-663123?course=ckad-practice-exam-02)        |
|     2 | 🎯  병렬 데이터 작업 실행                   | 초급    | [도전 시작](https://labex.io/ko/labs/run-a-parallel-data-job-663129?course=ckad-practice-exam-02)             |
|     3 | 🎯  어댑터 사이드카 추가                    | 초급    | [도전 시작](https://labex.io/ko/labs/add-an-adapter-sidecar-663113?course=ckad-practice-exam-02)              |
|     4 | 🎯  Projected 및 Persistent 데이터 마운트 | 초급    | [도전 시작](https://labex.io/ko/labs/mount-projected-and-persistent-data-663122?course=ckad-practice-exam-02) |

#### Application Deployment

|   인덱스 | 이름                        | 난이도   | 연습                                                                                                            |
|-------|---------------------------|-------|---------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  블루 - 그린 트래픽 전환         | 초급    | [도전 시작](https://labex.io/ko/labs/switch-blue-green-traffic-663131?course=ckad-practice-exam-02)               |
|     2 | 🎯  결함이 있는 배포 롤백           | 초급    | [도전 시작](https://labex.io/ko/labs/roll-back-a-faulty-deployment-663128?course=ckad-practice-exam-02)           |
|     3 | 🎯  로컬 Helm 릴리스 업그레이드      | 초급    | [도전 시작](https://labex.io/ko/labs/upgrade-a-local-helm-release-663132?course=ckad-practice-exam-02)            |
|     4 | 🎯  Kustomize 프로덕션 오버레이 생성 | 초급    | [도전 시작](https://labex.io/ko/labs/generate-a-kustomize-production-overlay-663120?course=ckad-practice-exam-02) |

#### Application Observability and Maintenance

|   인덱스 | 이름                    | 난이도   | 연습                                                                                                         |
|-------|-----------------------|-------|------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  느린 시작 프로브 수정       | 초급    | [도전 시작](https://labex.io/ko/labs/repair-slow-startup-probes-663127?course=ckad-practice-exam-02)           |
|     2 | 🎯  실패한 설정 롤아웃 디버깅     | 초급    | [도전 시작](https://labex.io/ko/labs/debug-a-failed-config-rollout-663117?course=ckad-practice-exam-02)        |
|     3 | 🎯  사용 중단된 정책 매니페스트 변환 | 초급    | [도전 시작](https://labex.io/ko/labs/convert-a-deprecated-policy-manifest-663115?course=ckad-practice-exam-02) |

#### Application Environment, Configuration and Security

|   인덱스 | 이름                         | 난이도   | 연습                                                                                                        |
|-------|----------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|     1 | 🎯  프로젝트 구성 및 보안 파일         | 초급    | [도전 시작](https://labex.io/ko/labs/project-config-and-secret-files-663124?course=ckad-practice-exam-02)     |
|     2 | 🎯  네임스페이스 리소스 기본값 강제 적용    | 초급    | [도전 시작](https://labex.io/ko/labs/enforce-namespace-resource-defaults-663119?course=ckad-practice-exam-02) |
|     3 | 🎯  App ServiceAccount 제한하기 | 초급    | [도전 시작](https://labex.io/ko/labs/limit-an-app-serviceaccount-663121?course=ckad-practice-exam-02)         |
|     4 | 🎯  쓰기 가능한 캐시 파드 보안 강화      | 초급    | [도전 시작](https://labex.io/ko/labs/secure-a-writable-cache-pod-663130?course=ckad-practice-exam-02)         |
|     5 | 🎯  버전 관리되는 앱 리소스 생성        | 초급    | [도전 시작](https://labex.io/ko/labs/create-a-versioned-app-resource-663116?course=ckad-practice-exam-02)     |

#### Services and Networking

|   인덱스 | 이름                         | 난이도   | 연습                                                                                                      |
|-------|----------------------------|-------|---------------------------------------------------------------------------------------------------------|
|     1 | 🎯  Named Service 포트 라우팅 복구 | 초급    | [도전 시작](https://labex.io/ko/labs/repair-named-service-port-routing-663126?course=ckad-practice-exam-02) |
|     2 | 🎯  Ingress 를 사용하여 경로 분할 게시 | 초급    | [도전 시작](https://labex.io/ko/labs/publish-split-paths-with-ingress-663125?course=ckad-practice-exam-02)  |
|     3 | 🎯  단일 네임스페이스로부터의 트래픽 허용    | 초급    | [도전 시작](https://labex.io/ko/labs/allow-traffic-from-one-namespace-663114?course=ckad-practice-exam-02)  |
|     4 | 🎯  서비스 DNS 액세스 진단          | 초급    | [도전 시작](https://labex.io/ko/labs/diagnose-service-dns-access-663118?course=ckad-practice-exam-02)       |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

