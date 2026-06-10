# CKAD 培训 Certification Prep Path

## 支持语言

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/zh/learn/ckad"><img width="128px" src="https://file.labex.io/path/izmE8twViI3a.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/开始路径-whitesmoke?style=for-the-badge)](https://labex.io/zh/learn/ckad)

通过结构化的动手学习路径备考 Certified Kubernetes Application Developer（CKAD）考试。本路线图侧重 Kubernetes 上的应用设计与构建、部署、可观测性与维护、配置与安全，以及服务与网络，以及贴近 CKAD 风格的性能型考试任务与真实场景。后续将逐步加入 CKAD 课程、实验环境与模拟考试练习，帮助你建立与 CKAD 目标一致的能力。

**课程**: 3 · **实验**: 82

## 课程

### 1. [CKAD 备考指南](https://labex.io/zh/courses/ckad-prep)

这是一门面向初学者的 CKAD 备考课程，包含 42 个引导式 Kubernetes 应用开发实验。内容涵盖从 kubectl 和对象基础，到工作负载、配置、部署、可观测性及网络等核心知识点。

[开始课程](https://labex.io/zh/courses/ckad-prep) · 实验: 42

#### Kubernetes 应用基础

|   序号 | 名称                      | 难度   | 练习                                                                                                |
|------|-------------------------|------|---------------------------------------------------------------------------------------------------|
|    1 | 🧩  探索 kubectl、上下文与命名空间  | 初级   | [开始实验](https://labex.io/zh/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep)  |
|    2 | 🧩  检查 Kubernetes API 资源 | 初级   | [开始实验](https://labex.io/zh/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep)         |
|    3 | 🧩  创建并检查 Pod            | 初级   | [开始实验](https://labex.io/zh/labs/create-and-inspect-a-pod-663597?course=ckad-prep)                 |
|    4 | 🧩  编写 Pod 清单            | 初级   | [开始实验](https://labex.io/zh/labs/write-a-pod-manifest-663628?course=ckad-prep)                     |
|    5 | 🧩  使用标签与选择器             | 初级   | [开始实验](https://labex.io/zh/labs/use-labels-and-selectors-663626?course=ckad-prep)                 |
|    6 | 🧩  使用 kubectl 生成和编辑清单   | 初级   | [开始实验](https://labex.io/zh/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep) |

#### 工作负载设计与构建

|   序号 | 名称                           | 难度   | 练习                                                                                                    |
|------|------------------------------|------|-------------------------------------------------------------------------------------------------------|
|    1 | 🧩  创建 Deployment             | 初级   | [开始实验](https://labex.io/zh/labs/create-a-deployment-663596?course=ckad-prep)                          |
|    2 | 🧩  扩展 Deployment             | 初级   | [开始实验](https://labex.io/zh/labs/scale-a-deployment-663618?course=ckad-prep)                           |
|    3 | 🧩  运行一次性任务 (Jobs)            | 初级   | [开始实验](https://labex.io/zh/labs/run-one-time-jobs-663616?course=ckad-prep)                            |
|    4 | 🧩  调度 CronJob                | 初级   | [开始实验](https://labex.io/zh/labs/schedule-cronjobs-663619?course=ckad-prep)                            |
|    5 | 🧩  选择合适的工作负载资源               | 初级   | [开始实验](https://labex.io/zh/labs/choose-the-right-workload-resource-663592?course=ckad-prep)           |
|    6 | 🧩  添加初始化容器 (Init Containers) | 初级   | [开始实验](https://labex.io/zh/labs/add-init-containers-663589?course=ckad-prep)                          |
|    7 | 🧩  添加 Sidecar 容器             | 初级   | [开始实验](https://labex.io/zh/labs/add-a-sidecar-container-663588?course=ckad-prep)                      |
|    8 | 🧩  在 Pod 中使用临时卷和持久卷          | 初级   | [开始实验](https://labex.io/zh/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep) |

#### 配置、存储与运行时设置

|   序号 | 名称                           | 难度   | 练习                                                                                              |
|------|------------------------------|------|-------------------------------------------------------------------------------------------------|
|   01 | 🧩  使用 ConfigMap 配置应用程序       | 初级   | [开始实验](https://labex.io/zh/labs/configure-applications-with-configmaps-663593?course=ckad-prep) |
|   02 | 🧩  使用 Secret 配置应用程序          | 初级   | [开始实验](https://labex.io/zh/labs/configure-applications-with-secrets-663594?course=ckad-prep)    |
|   03 | 🧩  注入环境变量                    | 初级   | [开始实验](https://labex.io/zh/labs/inject-environment-variables-663607?course=ckad-prep)           |
|   04 | 🧩  挂载配置文件                    | 初级   | [开始实验](https://labex.io/zh/labs/mount-configuration-files-663609?course=ckad-prep)              |
|   05 | 🧩  使用投射卷 (Projected Volumes) | 初级   | [开始实验](https://labex.io/zh/labs/use-projected-volumes-663627?course=ckad-prep)                  |
|   06 | 🧩  设置资源请求与限制                 | 初级   | [开始实验](https://labex.io/zh/labs/set-resource-requests-and-limits-663620?course=ckad-prep)       |
|   07 | 🧩  应用命名空间资源配额                | 初级   | [开始实验](https://labex.io/zh/labs/apply-namespace-resource-quotas-663590?course=ckad-prep)        |
|   08 | 🧩  使用专用 ServiceAccount 运行应用  | 初级   | [开始实验](https://labex.io/zh/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep)    |
|   09 | 🧩  加固 Pod 安全上下文              | 初级   | [开始实验](https://labex.io/zh/labs/harden-a-pod-security-context-663605?course=ckad-prep)          |
|   10 | 🧩  发现并使用自定义资源                | 初级   | [开始实验](https://labex.io/zh/labs/discover-and-use-custom-resources-663602?course=ckad-prep)      |

#### 部署与打包

|   序号 | 名称                      | 难度   | 练习                                                                                               |
|------|-------------------------|------|--------------------------------------------------------------------------------------------------|
|    1 | 🧩  执行滚动更新               | 初级   | [开始实验](https://labex.io/zh/labs/perform-a-rolling-update-663610?course=ckad-prep)                |
|    2 | 🧩  回滚故障部署               | 初级   | [开始实验](https://labex.io/zh/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep)           |
|    3 | 🧩  调整 Deployment 更新策略   | 初级   | [开始实验](https://labex.io/zh/labs/tune-deployment-update-strategy-663622?course=ckad-prep)         |
|    4 | 🧩  实现金丝雀发布              | 初级   | [开始实验](https://labex.io/zh/labs/implement-a-canary-release-663606?course=ckad-prep)              |
|    5 | 🧩  切换蓝绿部署流量             | 初级   | [开始实验](https://labex.io/zh/labs/switch-blue-green-traffic-663621?course=ckad-prep)               |
|    6 | 🧩  部署本地 Helm Chart      | 初级   | [开始实验](https://labex.io/zh/labs/deploy-a-local-helm-chart-663600?course=ckad-prep)               |
|    7 | 🧩  使用 Kustomize 自定义应用程序 | 初级   | [开始实验](https://labex.io/zh/labs/customize-an-application-with-kustomize-663598?course=ckad-prep) |
|    8 | 🧩  构建并运行本地应用程序镜像        | 初级   | [开始实验](https://labex.io/zh/labs/build-and-run-a-local-application-image-663591?course=ckad-prep) |

#### 可观测性、调试与应用网络

|   序号 | 名称                          | 难度   | 练习                                                                                                       |
|------|-----------------------------|------|----------------------------------------------------------------------------------------------------------|
|   01 | 🧩  读取日志与事件                  | 初级   | [开始实验](https://labex.io/zh/labs/read-logs-and-events-663611?course=ckad-prep)                            |
|   02 | 🧩  使用 exec 和端口转发进行调试        | 初级   | [开始实验](https://labex.io/zh/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep)      |
|   03 | 🧩  配置存活探针与就绪探针              | 初级   | [开始实验](https://labex.io/zh/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep)         |
|   04 | 🧩  调试 CrashLooping 应用       | 初级   | [开始实验](https://labex.io/zh/labs/debug-a-crashlooping-application-663599?course=ckad-prep)                |
|   05 | 🧩  更新已弃用的 API 清单            | 初级   | [开始实验](https://labex.io/zh/labs/update-deprecated-api-manifests-663623?course=ckad-prep)                 |
|   06 | 🧩  使用 Service 暴露 Deployment | 初级   | [开始实验](https://labex.io/zh/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep)              |
|   07 | 🧩  诊断 Service DNS 访问        | 初级   | [开始实验](https://labex.io/zh/labs/diagnose-service-dns-access-663601?course=ckad-prep)                     |
|   08 | 🧩  使用 Ingress 路由 HTTP 流量    | 初级   | [开始实验](https://labex.io/zh/labs/route-http-traffic-with-ingress-663615?course=ckad-prep)                 |
|   09 | 🧩  使用 NetworkPolicy 限制应用流量  | 初级   | [开始实验](https://labex.io/zh/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep) |
|   10 | 🧩  修复命名服务端口路由               | 初级   | [开始实验](https://labex.io/zh/labs/repair-named-service-port-routing-663612?course=ckad-prep)               |

### 2. [CKAD 模拟考试 01](https://labex.io/zh/courses/ckad-practice-exam-01)

这是一场实战型 CKAD 模拟考试，包含 20 个独立的 Kubernetes 应用开发挑战，涵盖应用设计与构建、部署、可观测性与维护、环境配置与安全，以及服务与网络等核心领域。

[开始课程](https://labex.io/zh/courses/ckad-practice-exam-01) · 实验: 20

#### 应用设计与构建

|   序号 | 名称                      | 难度   | 练习                                                                                                           |
|------|-------------------------|------|--------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  构建并运行本地应用程序镜像        | 初级   | [开始挑战](https://labex.io/zh/labs/build-and-run-a-local-application-image-663095?course=ckad-practice-exam-01) |
|    2 | 🎯  创建定时清理 CronJob       | 初级   | [开始挑战](https://labex.io/zh/labs/create-a-scheduled-cleanup-cronjob-663098?course=ckad-practice-exam-01)      |
|    3 | 🎯  添加 Init 和 Sidecar 容器 | 初级   | [开始挑战](https://labex.io/zh/labs/add-init-and-sidecar-containers-663093?course=ckad-practice-exam-01)         |
|    4 | 🎯  使用临时卷和持久卷            | 初级   | [开始挑战](https://labex.io/zh/labs/use-ephemeral-and-persistent-volumes-663112?course=ckad-practice-exam-01)    |

#### 应用部署

|   序号 | 名称                    | 难度   | 练习                                                                                                    |
|------|-----------------------|------|-------------------------------------------------------------------------------------------------------|
|    1 | 🎯  执行安全的滚动更新          | 初级   | [开始挑战](https://labex.io/zh/labs/perform-a-safe-rolling-update-663106?course=ckad-practice-exam-01)    |
|    2 | 🎯  实现金丝雀发布            | 初级   | [开始挑战](https://labex.io/zh/labs/implement-a-canary-release-663104?course=ckad-practice-exam-01)       |
|    3 | 🎯  部署分阶段的 Helm 应用     | 初级   | [开始挑战](https://labex.io/zh/labs/deploy-a-staged-helm-application-663101?course=ckad-practice-exam-01) |
|    4 | 🎯  使用 Kustomize 自定义应用 | 初级   | [开始挑战](https://labex.io/zh/labs/customize-an-app-with-kustomize-663099?course=ckad-practice-exam-01)  |

#### 应用可观测性与维护

|   序号 | 名称                    | 难度   | 练习                                                                                                    |
|------|-----------------------|------|-------------------------------------------------------------------------------------------------------|
|    1 | 🎯  配置健康探针             | 初级   | [开始挑战](https://labex.io/zh/labs/configure-health-probes-663096?course=ckad-practice-exam-01)          |
|    2 | 🎯  调试 CrashLooping 应用 | 初级   | [开始挑战](https://labex.io/zh/labs/debug-a-crashlooping-application-663100?course=ckad-practice-exam-01) |
|    3 | 🎯  更新已弃用的清单           | 初级   | [开始挑战](https://labex.io/zh/labs/update-deprecated-manifests-663111?course=ckad-practice-exam-01)      |

#### 应用环境、配置与安全

|   序号 | 名称                        | 难度   | 练习                                                                                                       |
|------|---------------------------|------|----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  注入 ConfigMap 和 Secret  | 初级   | [开始挑战](https://labex.io/zh/labs/inject-configmaps-and-secrets-663105?course=ckad-practice-exam-01)       |
|    2 | 🎯  应用资源请求与配额              | 初级   | [开始挑战](https://labex.io/zh/labs/apply-resource-requests-and-quotas-663094?course=ckad-practice-exam-01)  |
|    3 | 🎯  使用专用 ServiceAccount 运行 | 初级   | [开始挑战](https://labex.io/zh/labs/run-with-a-dedicated-serviceaccount-663109?course=ckad-practice-exam-01) |
|    4 | 🎯  加固 Pod 安全上下文           | 初级   | [开始挑战](https://labex.io/zh/labs/harden-a-pod-security-context-663103?course=ckad-practice-exam-01)       |
|    5 | 🎯  创建应用自定义资源              | 初级   | [开始挑战](https://labex.io/zh/labs/create-an-app-custom-resource-663097?course=ckad-practice-exam-01)       |

#### 服务与网络

|   序号 | 名称                          | 难度   | 练习                                                                                                           |
|------|-----------------------------|------|--------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用 Service 暴露 Deployment | 初级   | [开始挑战](https://labex.io/zh/labs/expose-a-deployment-with-a-service-663102?course=ckad-practice-exam-01)      |
|    2 | 🎯  使用 Ingress 路由 HTTP 流量    | 初级   | [开始挑战](https://labex.io/zh/labs/route-http-traffic-with-ingress-663108?course=ckad-practice-exam-01)         |
|    3 | 🎯  使用 NetworkPolicy 限制应用流量  | 初级   | [开始挑战](https://labex.io/zh/labs/restrict-app-traffic-with-networkpolicy-663107?course=ckad-practice-exam-01) |
|    4 | 🎯  排查服务端点访问问题               | 初级   | [开始挑战](https://labex.io/zh/labs/troubleshoot-service-endpoint-access-663110?course=ckad-practice-exam-01)    |

### 3. [CKAD 模拟考试 02](https://labex.io/zh/courses/ckad-practice-exam-02)

这是第二套独立的 CKAD 风格模拟考试，包含 20 个 Kubernetes 应用开发挑战，涵盖了 CKAD 认证考试大纲中涉及的各类实际操作场景。

[开始课程](https://labex.io/zh/courses/ckad-practice-exam-02) · 实验: 20

#### 应用设计与构建

|   序号 | 名称                | 难度   | 练习                                                                                                       |
|------|-------------------|------|----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  打包本地 Worker 镜像 | 初级   | [开始挑战](https://labex.io/zh/labs/package-a-local-worker-image-663123?course=ckad-practice-exam-02)        |
|    2 | 🎯  运行并行数据作业       | 初级   | [开始挑战](https://labex.io/zh/labs/run-a-parallel-data-job-663129?course=ckad-practice-exam-02)             |
|    3 | 🎯  添加适配器 Sidecar  | 初级   | [开始挑战](https://labex.io/zh/labs/add-an-adapter-sidecar-663113?course=ckad-practice-exam-02)              |
|    4 | 🎯  挂载投影卷与持久化数据    | 初级   | [开始挑战](https://labex.io/zh/labs/mount-projected-and-persistent-data-663122?course=ckad-practice-exam-02) |

#### 应用部署

|   序号 | 名称                           | 难度   | 练习                                                                                                           |
|------|------------------------------|------|--------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  切换蓝绿部署流量                  | 初级   | [开始挑战](https://labex.io/zh/labs/switch-blue-green-traffic-663131?course=ckad-practice-exam-02)               |
|    2 | 🎯  回滚故障部署                    | 初级   | [开始挑战](https://labex.io/zh/labs/roll-back-a-faulty-deployment-663128?course=ckad-practice-exam-02)           |
|    3 | 🎯  升级本地 Helm Release         | 初级   | [开始挑战](https://labex.io/zh/labs/upgrade-a-local-helm-release-663132?course=ckad-practice-exam-02)            |
|    4 | 🎯  生成 Kustomize 生产环境 Overlay | 初级   | [开始挑战](https://labex.io/zh/labs/generate-a-kustomize-production-overlay-663120?course=ckad-practice-exam-02) |

#### 应用可观测性与维护

|   序号 | 名称            | 难度   | 练习                                                                                                        |
|------|---------------|------|-----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复缓慢的启动探针  | 初级   | [开始挑战](https://labex.io/zh/labs/repair-slow-startup-probes-663127?course=ckad-practice-exam-02)           |
|    2 | 🎯  调试失败的配置发布  | 初级   | [开始挑战](https://labex.io/zh/labs/debug-a-failed-config-rollout-663117?course=ckad-practice-exam-02)        |
|    3 | 🎯  转换已弃用的策略清单 | 初级   | [开始挑战](https://labex.io/zh/labs/convert-a-deprecated-policy-manifest-663115?course=ckad-practice-exam-02) |

#### 应用环境、配置与安全

|   序号 | 名称                     | 难度   | 练习                                                                                                       |
|------|------------------------|------|----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  项目配置与密钥文件           | 初级   | [开始挑战](https://labex.io/zh/labs/project-config-and-secret-files-663124?course=ckad-practice-exam-02)     |
|    2 | 🎯  强制执行命名空间资源默认值       | 初级   | [开始挑战](https://labex.io/zh/labs/enforce-namespace-resource-defaults-663119?course=ckad-practice-exam-02) |
|    3 | 🎯  限制应用 ServiceAccount | 初级   | [开始挑战](https://labex.io/zh/labs/limit-an-app-serviceaccount-663121?course=ckad-practice-exam-02)         |
|    4 | 🎯  保护可写缓存 Pod          | 初级   | [开始挑战](https://labex.io/zh/labs/secure-a-writable-cache-pod-663130?course=ckad-practice-exam-02)         |
|    5 | 🎯  创建版本化的应用资源          | 初级   | [开始挑战](https://labex.io/zh/labs/create-a-versioned-app-resource-663116?course=ckad-practice-exam-02)     |

#### 服务与网络

|   序号 | 名称                     | 难度   | 练习                                                                                                     |
|------|------------------------|------|--------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复命名服务端口路由          | 初级   | [开始挑战](https://labex.io/zh/labs/repair-named-service-port-routing-663126?course=ckad-practice-exam-02) |
|    2 | 🎯  使用 Ingress 发布拆分路径   | 初级   | [开始挑战](https://labex.io/zh/labs/publish-split-paths-with-ingress-663125?course=ckad-practice-exam-02)  |
|    3 | 🎯  允许来自特定命名空间的流量       | 初级   | [开始挑战](https://labex.io/zh/labs/allow-traffic-from-one-namespace-663114?course=ckad-practice-exam-02)  |
|    4 | 🎯  诊断 Service DNS 访问问题 | 初级   | [开始挑战](https://labex.io/zh/labs/diagnose-service-dns-access-663118?course=ckad-practice-exam-02)       |

## 关于 LabEx

[LabEx](https://labex.io) 是一个专注于编程和技术的交互式动手学习平台。它结合了实验室、AI 辅助和虚拟机，提供无视频的实践学习体验。采用严格的'边学边做'方法，浏览器内的交互式在线环境具有自动化的逐步检查，基于技能树的结构化内容组织系统，以及不断增长的学习资源（包含 30 个技能树和超过 6,000 个实验），[LabEx](https://labex.io) 提供全面的实践教育。该平台包含基于最新 AI 模型构建的学习助手 Labby，提供对话式学习体验。

