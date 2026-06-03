# Обучение CKAD Путь подготовки к сертификации

## Языки

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/ru/learn/ckad"><img width="128px" src="https://file.labex.io/path/izmE8twViI3a.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Начать-путь-whitesmoke?style=for-the-badge)](https://labex.io/ru/learn/ckad)

Готовьтесь к экзамену Certified Kubernetes Application Developer (CKAD) по структурированной практической программе. Акцент на проектирование и создание приложений, развёртывание, наблюдаемость и сопровождение, конфигурация и безопасность, сервисы и сеть в Kubernetes, практических заданиях в стиле CKAD и сценариях из практики. Курсы CKAD, лаборатории и пробные экзамены будут добавляться постепенно.

**Курсы**: 3 · **Лаборатории**: 82

## Курсы

### 1. [Подготовка к CKAD](https://labex.io/ru/courses/ckad-prep)

Курс по подготовке к сертификации CKAD для начинающих, включающий 42 практические лабораторные работы по разработке приложений в Kubernetes: от основ kubectl и объектов до рабочих нагрузок, конфигурации, развертывания, мониторинга и сетевого взаимодействия.

[Начать курс](https://labex.io/ru/courses/ckad-prep) · Лаборатории: 42

#### Kubernetes Application Foundations

|   Индекс | Название                                                  | Сложность   | Практика                                                                                                        |
|----------|-----------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Изучение kubectl, контекстов и пространств имен        | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep)  |
|        2 | 🧩  Изучение ресурсов Kubernetes API                       | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep)         |
|        3 | 🧩  Создание и проверка пода                               | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/create-and-inspect-a-pod-663597?course=ckad-prep)                 |
|        4 | 🧩  Написание манифеста Pod                                | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/write-a-pod-manifest-663628?course=ckad-prep)                     |
|        5 | 🧩  Использование меток (Labels) и селекторов (Selectors)  | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/use-labels-and-selectors-663626?course=ckad-prep)                 |
|        6 | 🧩  Создание и редактирование манифестов с помощью kubectl | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep) |

#### Workload Design and Build

|   Индекс | Название                                              | Сложность   | Практика                                                                                                            |
|----------|-------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Создание Deployment                                | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/create-a-deployment-663596?course=ckad-prep)                          |
|        2 | 🧩  Масштабирование Deployment                         | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/scale-a-deployment-663618?course=ckad-prep)                           |
|        3 | 🧩  Запуск однократных заданий (Jobs)                  | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/run-one-time-jobs-663616?course=ckad-prep)                            |
|        4 | 🧩  Планирование CronJobs                              | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/schedule-cronjobs-663619?course=ckad-prep)                            |
|        5 | 🧩  Выбор подходящего ресурса рабочей нагрузки         | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/choose-the-right-workload-resource-663592?course=ckad-prep)           |
|        6 | 🧩  Добавление Init-контейнеров                        | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/add-init-containers-663589?course=ckad-prep)                          |
|        7 | 🧩  Добавление sidecar-контейнера                      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/add-a-sidecar-container-663588?course=ckad-prep)                      |
|        8 | 🧩  Использование эфемерных и постоянных томов в подах | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep) |

#### Configuration, Storage, and Runtime Settings

|   Индекс | Название                                                       | Сложность   | Практика                                                                                                      |
|----------|----------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------|
|       01 | 🧩  Настройка приложений с помощью ConfigMap                    | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/configure-applications-with-configmaps-663593?course=ckad-prep) |
|       02 | 🧩  Настройка приложений с помощью секретов (Secrets)           | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/configure-applications-with-secrets-663594?course=ckad-prep)    |
|       03 | 🧩  Внедрение переменных окружения                              | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inject-environment-variables-663607?course=ckad-prep)           |
|       04 | 🧩  Монтирование файлов конфигурации                            | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/mount-configuration-files-663609?course=ckad-prep)              |
|       05 | 🧩  Использование проецируемых томов (Projected Volumes)        | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/use-projected-volumes-663627?course=ckad-prep)                  |
|       06 | 🧩  Установка запросов и лимитов ресурсов                       | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/set-resource-requests-and-limits-663620?course=ckad-prep)       |
|       07 | 🧩  Применение квот ресурсов пространства имен                  | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/apply-namespace-resource-quotas-663590?course=ckad-prep)        |
|       08 | 🧩  Запуск с выделенной учетной записью службы (ServiceAccount) | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep)    |
|       09 | 🧩  Усиление контекста безопасности Pod                         | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/harden-a-pod-security-context-663605?course=ckad-prep)          |
|       10 | 🧩  Обнаружение и использование пользовательских ресурсов       | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/discover-and-use-custom-resources-663602?course=ckad-prep)      |

#### Deployment and Packaging

|   Индекс | Название                                                    | Сложность   | Практика                                                                                                       |
|----------|-------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Выполнение последовательного обновления (Rolling Update) | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/perform-a-rolling-update-663610?course=ckad-prep)                |
|        2 | 🧩  Откат ошибочного развертывания                           | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep)           |
|        3 | 🧩  Настройка стратегии обновления развертывания             | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/tune-deployment-update-strategy-663622?course=ckad-prep)         |
|        4 | 🧩  Реализация Canary-релиза                                 | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/implement-a-canary-release-663606?course=ckad-prep)              |
|        5 | 🧩  Переключение трафика по методу Blue-Green                | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/switch-blue-green-traffic-663621?course=ckad-prep)               |
|        6 | 🧩  Развертывание локального чарта Helm                      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/deploy-a-local-helm-chart-663600?course=ckad-prep)               |
|        7 | 🧩  Настройка приложения с помощью Kustomize                 | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/customize-an-application-with-kustomize-663598?course=ckad-prep) |
|        8 | 🧩  Сборка и запуск локального образа приложения             | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/build-and-run-a-local-application-image-663591?course=ckad-prep) |

#### Observability, Debugging, and App Networking

|   Индекс | Название                                                        | Сложность   | Практика                                                                                                               |
|----------|-----------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------|
|       01 | 🧩  Чтение логов и событий                                       | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/read-logs-and-events-663611?course=ckad-prep)                            |
|       02 | 🧩  Использование exec и перенаправления портов для отладки      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep)      |
|       03 | 🧩  Настройка проб готовности (Readiness) и живучести (Liveness) | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep)         |
|       04 | 🧩  Отладка приложения в состоянии CrashLoop                     | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/debug-a-crashlooping-application-663599?course=ckad-prep)                |
|       05 | 🧩  Обновление устаревших манифестов API                         | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/update-deprecated-api-manifests-663623?course=ckad-prep)                 |
|       06 | 🧩  Публикация Deployment с помощью Service                      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep)              |
|       07 | 🧩  Диагностика доступа к DNS сервисов                           | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/diagnose-service-dns-access-663601?course=ckad-prep)                     |
|       08 | 🧩  Маршрутизация HTTP-трафика с помощью Ingress                 | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/route-http-traffic-with-ingress-663615?course=ckad-prep)                 |
|       09 | 🧩  Ограничение трафика приложения с помощью NetworkPolicy       | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep) |
|       10 | 🧩  Исправление маршрутизации именованного порта службы          | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/repair-named-service-port-routing-663612?course=ckad-prep)               |

### 2. [Практический экзамен CKAD 01](https://labex.io/ru/courses/ckad-practice-exam-01)

Практический экзамен CKAD, включающий 20 независимых задач по разработке приложений в Kubernetes. Темы охватывают проектирование и сборку приложений, развертывание, наблюдаемость и обслуживание, настройку окружения и безопасность, а также сервисы и сетевое взаимодействие.

[Начать курс](https://labex.io/ru/courses/ckad-practice-exam-01) · Лаборатории: 20

#### Application Design and Build

|   Индекс | Название                                             | Сложность   | Практика                                                                                                                 |
|----------|------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Сборка и запуск локального образа приложения      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/build-and-run-a-local-application-image-663095?course=ckad-practice-exam-01) |
|        2 | 🎯  Создание запланированного CronJob для очистки     | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/create-a-scheduled-cleanup-cronjob-663098?course=ckad-practice-exam-01)      |
|        3 | 🎯  Добавление Init-контейнеров и Sidecar-контейнеров | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/add-init-and-sidecar-containers-663093?course=ckad-practice-exam-01)         |
|        4 | 🎯  Использование эфемерных и постоянных томов        | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/use-ephemeral-and-persistent-volumes-663112?course=ckad-practice-exam-01)    |

#### Application Deployment

|   Индекс | Название                                                                | Сложность   | Практика                                                                                                          |
|----------|-------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Выполнение безопасного последовательного обновления (Rolling Update) | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/perform-a-safe-rolling-update-663106?course=ckad-practice-exam-01)    |
|        2 | 🎯  Реализация Canary-релиза                                             | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/implement-a-canary-release-663104?course=ckad-practice-exam-01)       |
|        3 | 🎯  Развертывание приложения с помощью Helm                              | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/deploy-a-staged-helm-application-663101?course=ckad-practice-exam-01) |
|        4 | 🎯  Настройка приложения с помощью Kustomize                             | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/customize-an-app-with-kustomize-663099?course=ckad-practice-exam-01)  |

#### Application Observability and Maintenance

|   Индекс | Название                                       | Сложность   | Практика                                                                                                          |
|----------|------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Настройка проб здоровья (Health Probes)     | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/configure-health-probes-663096?course=ckad-practice-exam-01)          |
|        2 | 🎯  Отладка приложения в состоянии CrashLooping | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/debug-a-crashlooping-application-663100?course=ckad-practice-exam-01) |
|        3 | 🎯  Обновление устаревших манифестов            | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/update-deprecated-manifests-663111?course=ckad-practice-exam-01)      |

#### Application Environment, Configuration and Security

|   Индекс | Название                                                       | Сложность   | Практика                                                                                                             |
|----------|----------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Внедрение ConfigMaps и Secrets                              | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/inject-configmaps-and-secrets-663105?course=ckad-practice-exam-01)       |
|        2 | 🎯  Применение запросов ресурсов и квот                         | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/apply-resource-requests-and-quotas-663094?course=ckad-practice-exam-01)  |
|        3 | 🎯  Запуск с выделенной учетной записью службы (ServiceAccount) | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/run-with-a-dedicated-serviceaccount-663109?course=ckad-practice-exam-01) |
|        4 | 🎯  Усиление контекста безопасности пода                        | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/harden-a-pod-security-context-663103?course=ckad-practice-exam-01)       |
|        5 | 🎯  Создание пользовательского ресурса приложения               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/create-an-app-custom-resource-663097?course=ckad-practice-exam-01)       |

#### Services and Networking

|   Индекс | Название                                                  | Сложность   | Практика                                                                                                                 |
|----------|-----------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Предоставление доступа к Deployment через Service      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/expose-a-deployment-with-a-service-663102?course=ckad-practice-exam-01)      |
|        2 | 🎯  Маршрутизация HTTP-трафика с помощью Ingress           | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/route-http-traffic-with-ingress-663108?course=ckad-practice-exam-01)         |
|        3 | 🎯  Ограничение трафика приложения с помощью NetworkPolicy | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restrict-app-traffic-with-networkpolicy-663107?course=ckad-practice-exam-01) |
|        4 | 🎯  Устранение неполадок доступа к конечным точкам сервиса | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/troubleshoot-service-endpoint-access-663110?course=ckad-practice-exam-01)    |

### 3. [Практический экзамен CKAD 02](https://labex.io/ru/courses/ckad-practice-exam-02)

Второй независимый практический экзамен в стиле CKAD, включающий 20 задач по разработке приложений в Kubernetes, которые охватывают все ключевые области сертификации через различные рабочие сценарии.

[Начать курс](https://labex.io/ru/courses/ckad-practice-exam-02) · Лаборатории: 20

#### Application Design and Build

|   Индекс | Название                                         | Сложность   | Практика                                                                                                             |
|----------|--------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Упаковка локального образа рабочего процесса  | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/package-a-local-worker-image-663123?course=ckad-practice-exam-02)        |
|        2 | 🎯  Запуск параллельного задания обработки данных | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/run-a-parallel-data-job-663129?course=ckad-practice-exam-02)             |
|        3 | 🎯  Добавление sidecar-контейнера адаптера        | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/add-an-adapter-sidecar-663113?course=ckad-practice-exam-02)              |
|        4 | 🎯  Монтирование проецируемых и постоянных данных | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/mount-projected-and-persistent-data-663122?course=ckad-practice-exam-02) |

#### Application Deployment

|   Индекс | Название                                        | Сложность   | Практика                                                                                                                 |
|----------|-------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Переключение трафика Blue-Green              | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/switch-blue-green-traffic-663131?course=ckad-practice-exam-02)               |
|        2 | 🎯  Откат ошибочного развертывания               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/roll-back-a-faulty-deployment-663128?course=ckad-practice-exam-02)           |
|        3 | 🎯  Обновление локального релиза Helm            | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/upgrade-a-local-helm-release-663132?course=ckad-practice-exam-02)            |
|        4 | 🎯  Создание производственного оверлея Kustomize | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/generate-a-kustomize-production-overlay-663120?course=ckad-practice-exam-02) |

#### Application Observability and Maintenance

|   Индекс | Название                                               | Сложность   | Практика                                                                                                              |
|----------|--------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Исправление медленных проб запуска (Startup Probes) | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/repair-slow-startup-probes-663127?course=ckad-practice-exam-02)           |
|        2 | 🎯  Отладка неудачного развертывания конфигурации       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/debug-a-failed-config-rollout-663117?course=ckad-practice-exam-02)        |
|        3 | 🎯  Преобразование устаревшего манифеста политики       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/convert-a-deprecated-policy-manifest-663115?course=ckad-practice-exam-02) |

#### Application Environment, Configuration and Security

|   Индекс | Название                                                               | Сложность   | Практика                                                                                                             |
|----------|------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Конфигурация проекта и секретные файлы                              | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/project-config-and-secret-files-663124?course=ckad-practice-exam-02)     |
|        2 | 🎯  Принудительное применение ресурсов по умолчанию в пространстве имен | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/enforce-namespace-resource-defaults-663119?course=ckad-practice-exam-02) |
|        3 | 🎯  Ограничение ServiceAccount для приложения                           | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/limit-an-app-serviceaccount-663121?course=ckad-practice-exam-02)         |
|        4 | 🎯  Защита пода с кэшем для записи                                      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/secure-a-writable-cache-pod-663130?course=ckad-practice-exam-02)         |
|        5 | 🎯  Создание версионированного ресурса приложения                       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/create-a-versioned-app-resource-663116?course=ckad-practice-exam-02)     |

#### Services and Networking

|   Индекс | Название                                               | Сложность   | Практика                                                                                                           |
|----------|--------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Исправление маршрутизации именованного порта службы | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/repair-named-service-port-routing-663126?course=ckad-practice-exam-02) |
|        2 | 🎯  Публикация разделенных путей с помощью Ingress      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/publish-split-paths-with-ingress-663125?course=ckad-practice-exam-02)  |
|        3 | 🎯  Разрешение трафика из одного пространства имен      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/allow-traffic-from-one-namespace-663114?course=ckad-practice-exam-02)  |
|        4 | 🎯  Диагностика DNS-доступа к сервису                   | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/diagnose-service-dns-access-663118?course=ckad-practice-exam-02)       |

## О LabEx

[LabEx](https://labex.io) - это интерактивная практическая обучающая платформа, посвященная программированию и технологиям. Она объединяет лаборатории, ИИ-помощь и виртуальные машины для обеспечения практического обучения без видео. Со строгим подходом 'Учись делая', интерактивными онлайн-средами в браузере с автоматизированными пошаговыми проверками, структурированной организацией контента с системой на основе Дерева Навыков, и растущим учебным ресурсом из 30 Деревьев Навыков и более 6,000 Лабораторий, [LabEx](https://labex.io) предлагает всестороннее практическое образование. Платформа включает ассистента обучения Labby, построенного на последних моделях ИИ, обеспечивающего разговорный опыт обучения.

