# CKAD トレーニング 認定試験準備パス

## 言語

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/ja/learn/ckad"><img width="128px" src="https://file.labex.io/path/izmE8twViI3a.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/パスを開始-whitesmoke?style=for-the-badge)](https://labex.io/ja/learn/ckad)

Certified Kubernetes Application Developer（CKAD）試験に向けた、体系的かつ実践的な学習パスです。Kubernetes におけるアプリケーション設計と構築、デプロイ、可観測性とメンテナンス、構成とセキュリティ、サービスとネットワーク、および CKAD 形式のパフォーマンスベースのタスクと現実的なシナリオに焦点を当てます。CKAD コース、ラボ、模擬試験の演習は順次追加され、CKAD の目標に沿ったスキルを育成します。

**コース**: 3 · **ラボ**: 82

## コース

### 1. [CKAD対策コース](https://labex.io/ja/courses/ckad-prep)

初心者向けのCKAD対策コースです。kubectlの基本操作やオブジェクトの基礎から、ワークロード、設定、デプロイ、可観測性、ネットワークに至るまで、42のガイド付きKubernetesアプリケーション開発実験を通じて体系的に学習できます。

[コースを開始](https://labex.io/ja/courses/ckad-prep) · ラボ: 42

#### Kubernetes Application Foundations

|   インデックス | 名前                              | 難易度   | 練習                                                                                                 |
|----------|---------------------------------|-------|----------------------------------------------------------------------------------------------------|
|        1 | 🧩  kubectl、コンテキスト、およびネームスペースの探索 | 初級    | [ラボを開始](https://labex.io/ja/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep)  |
|        2 | 🧩  Kubernetes API リソースの調査       | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep)         |
|        3 | 🧩  Pod の作成と調査                   | 初級    | [ラボを開始](https://labex.io/ja/labs/create-and-inspect-a-pod-663597?course=ckad-prep)                 |
|        4 | 🧩  Pod マニフェストの作成                | 初級    | [ラボを開始](https://labex.io/ja/labs/write-a-pod-manifest-663628?course=ckad-prep)                     |
|        5 | 🧩  ラベルとセレクターの使用                 | 初級    | [ラボを開始](https://labex.io/ja/labs/use-labels-and-selectors-663626?course=ckad-prep)                 |
|        6 | 🧩  kubectl を使用したマニフェストの生成と編集    | 初級    | [ラボを開始](https://labex.io/ja/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep) |

#### Workload Design and Build

|   インデックス | 名前                               | 難易度   | 練習                                                                                                     |
|----------|----------------------------------|-------|--------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Deployment の作成                | 初級    | [ラボを開始](https://labex.io/ja/labs/create-a-deployment-663596?course=ckad-prep)                          |
|        2 | 🧩  Deployment のスケーリング            | 初級    | [ラボを開始](https://labex.io/ja/labs/scale-a-deployment-663618?course=ckad-prep)                           |
|        3 | 🧩  ワンタイムジョブの実行                   | 初級    | [ラボを開始](https://labex.io/ja/labs/run-one-time-jobs-663616?course=ckad-prep)                            |
|        4 | 🧩  CronJob のスケジュール設定             | 初級    | [ラボを開始](https://labex.io/ja/labs/schedule-cronjobs-663619?course=ckad-prep)                            |
|        5 | 🧩  適切なワークロードリソースの選択              | 初級    | [ラボを開始](https://labex.io/ja/labs/choose-the-right-workload-resource-663592?course=ckad-prep)           |
|        6 | 🧩  Init コンテナの追加                  | 初級    | [ラボを開始](https://labex.io/ja/labs/add-init-containers-663589?course=ckad-prep)                          |
|        7 | 🧩  サイドカーコンテナの追加                  | 初級    | [ラボを開始](https://labex.io/ja/labs/add-a-sidecar-container-663588?course=ckad-prep)                      |
|        8 | 🧩  Pod でエフェメラルボリュームと永続ボリュームを使用する | 初級    | [ラボを開始](https://labex.io/ja/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep) |

#### Configuration, Storage, and Runtime Settings

|   インデックス | 名前                                 | 難易度   | 練習                                                                                               |
|----------|------------------------------------|-------|--------------------------------------------------------------------------------------------------|
|       01 | 🧩  ConfigMap を使用したアプリケーションの設定      | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-applications-with-configmaps-663593?course=ckad-prep) |
|       02 | 🧩  Secret を使用したアプリケーションの設定         | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-applications-with-secrets-663594?course=ckad-prep)    |
|       03 | 🧩  環境変数の注入                         | 初級    | [ラボを開始](https://labex.io/ja/labs/inject-environment-variables-663607?course=ckad-prep)           |
|       04 | 🧩  設定ファイルのマウント                     | 初級    | [ラボを開始](https://labex.io/ja/labs/mount-configuration-files-663609?course=ckad-prep)              |
|       05 | 🧩  Projected Volume（投影ボリューム）の使用    | 初級    | [ラボを開始](https://labex.io/ja/labs/use-projected-volumes-663627?course=ckad-prep)                  |
|       06 | 🧩  リソースの要求（Requests）と制限（Limits）の設定 | 初級    | [ラボを開始](https://labex.io/ja/labs/set-resource-requests-and-limits-663620?course=ckad-prep)       |
|       07 | 🧩  Namespace リソースクォータの適用           | 初級    | [ラボを開始](https://labex.io/ja/labs/apply-namespace-resource-quotas-663590?course=ckad-prep)        |
|       08 | 🧩  専用の ServiceAccount で実行する        | 初級    | [ラボを開始](https://labex.io/ja/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep)    |
|       09 | 🧩  Pod セキュリティコンテキストの強化             | 初級    | [ラボを開始](https://labex.io/ja/labs/harden-a-pod-security-context-663605?course=ckad-prep)          |
|       10 | 🧩  カスタムリソースの発見と利用                  | 初級    | [ラボを開始](https://labex.io/ja/labs/discover-and-use-custom-resources-663602?course=ckad-prep)      |

#### Deployment and Packaging

|   インデックス | 名前                                  | 難易度   | 練習                                                                                                |
|----------|-------------------------------------|-------|---------------------------------------------------------------------------------------------------|
|        1 | 🧩  ローリングアップデートの実行                   | 初級    | [ラボを開始](https://labex.io/ja/labs/perform-a-rolling-update-663610?course=ckad-prep)                |
|        2 | 🧩  障害が発生したデプロイメントのロールバック            | 初級    | [ラボを開始](https://labex.io/ja/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep)           |
|        3 | 🧩  Deployment の更新戦略を調整する            | 初級    | [ラボを開始](https://labex.io/ja/labs/tune-deployment-update-strategy-663622?course=ckad-prep)         |
|        4 | 🧩  カナリアリリースの実装                      | 初級    | [ラボを開始](https://labex.io/ja/labs/implement-a-canary-release-663606?course=ckad-prep)              |
|        5 | 🧩  Blue-Green デプロイメントによるトラフィックの切り替え | 初級    | [ラボを開始](https://labex.io/ja/labs/switch-blue-green-traffic-663621?course=ckad-prep)               |
|        6 | 🧩  ローカル Helm チャートのデプロイ              | 初級    | [ラボを開始](https://labex.io/ja/labs/deploy-a-local-helm-chart-663600?course=ckad-prep)               |
|        7 | 🧩  Kustomize を使用したアプリケーションのカスタマイズ   | 初級    | [ラボを開始](https://labex.io/ja/labs/customize-an-application-with-kustomize-663598?course=ckad-prep) |
|        8 | 🧩  ローカルアプリケーションイメージのビルドと実行          | 初級    | [ラボを開始](https://labex.io/ja/labs/build-and-run-a-local-application-image-663591?course=ckad-prep) |

#### Observability, Debugging, and App Networking

|   インデックス | 名前                                  | 難易度   | 練習                                                                                                        |
|----------|-------------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|       01 | 🧩  ログとイベントの読み取り                     | 初級    | [ラボを開始](https://labex.io/ja/labs/read-logs-and-events-663611?course=ckad-prep)                            |
|       02 | 🧩  exec とポートフォワードを使用したデバッグ          | 初級    | [ラボを開始](https://labex.io/ja/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep)      |
|       03 | 🧩  Liveness プローブと Readiness プローブの設定 | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep)         |
|       04 | 🧩  CrashLooping アプリケーションのデバッグ       | 初級    | [ラボを開始](https://labex.io/ja/labs/debug-a-crashlooping-application-663599?course=ckad-prep)                |
|       05 | 🧩  非推奨 API マニフェストの更新                | 初級    | [ラボを開始](https://labex.io/ja/labs/update-deprecated-api-manifests-663623?course=ckad-prep)                 |
|       06 | 🧩  Service を使用した Deployment の公開     | 初級    | [ラボを開始](https://labex.io/ja/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep)              |
|       07 | 🧩  Service DNS アクセスの診断              | 初級    | [ラボを開始](https://labex.io/ja/labs/diagnose-service-dns-access-663601?course=ckad-prep)                     |
|       08 | 🧩  Ingress を使用した HTTP トラフィックのルーティング | 初級    | [ラボを開始](https://labex.io/ja/labs/route-http-traffic-with-ingress-663615?course=ckad-prep)                 |
|       09 | 🧩  NetworkPolicy を使用したアプリケーション通信の制限 | 初級    | [ラボを開始](https://labex.io/ja/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep) |
|       10 | 🧩  名前付きサービスポートルーティングの修復             | 初級    | [ラボを開始](https://labex.io/ja/labs/repair-named-service-port-routing-663612?course=ckad-prep)               |

### 2. [CKAD 模擬試験 01](https://labex.io/ja/courses/ckad-practice-exam-01)

CKAD 試験に向けた実践的な模擬試験です。アプリケーションの設計・構築、デプロイ、可観測性とメンテナンス、環境設定とセキュリティ、サービスとネットワークという CKAD の主要分野を網羅した、20 の独立した Kubernetes アプリケーション開発の課題に挑戦できます。

[コースを開始](https://labex.io/ja/courses/ckad-practice-exam-01) · ラボ: 20

#### Application Design and Build

|   インデックス | 名前                              | 難易度   | 練習                                                                                                               |
|----------|---------------------------------|-------|------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ローカルアプリケーションイメージのビルドと実行      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/build-and-run-a-local-application-image-663095?course=ckad-practice-exam-01) |
|        2 | 🎯  スケジュールされたクリーンアップ CronJob の作成 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-a-scheduled-cleanup-cronjob-663098?course=ckad-practice-exam-01)      |
|        3 | 🎯  Init コンテナとサイドカーコンテナの追加       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/add-init-and-sidecar-containers-663093?course=ckad-practice-exam-01)         |
|        4 | 🎯  エフェメラルボリュームと永続ボリュームの使用       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/use-ephemeral-and-persistent-volumes-663112?course=ckad-practice-exam-01)    |

#### Application Deployment

|   インデックス | 名前                                | 難易度   | 練習                                                                                                        |
|----------|-----------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|        1 | 🎯  安全なローリングアップデートの実行              | 初級    | [チャレンジを開始](https://labex.io/ja/labs/perform-a-safe-rolling-update-663106?course=ckad-practice-exam-01)    |
|        2 | 🎯  カナリアリリースの実装                    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/implement-a-canary-release-663104?course=ckad-practice-exam-01)       |
|        3 | 🎯  ステージングされた Helm アプリケーションのデプロイ   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/deploy-a-staged-helm-application-663101?course=ckad-practice-exam-01) |
|        4 | 🎯  Kustomize を使用したアプリケーションのカスタマイズ | 初級    | [チャレンジを開始](https://labex.io/ja/labs/customize-an-app-with-kustomize-663099?course=ckad-practice-exam-01)  |

#### Application Observability and Maintenance

|   インデックス | 名前                            | 難易度   | 練習                                                                                                        |
|----------|-------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ヘルスプローブの設定                 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/configure-health-probes-663096?course=ckad-practice-exam-01)          |
|        2 | 🎯  CrashLooping アプリケーションのデバッグ | 初級    | [チャレンジを開始](https://labex.io/ja/labs/debug-a-crashlooping-application-663100?course=ckad-practice-exam-01) |
|        3 | 🎯  非推奨マニフェストの更新               | 初級    | [チャレンジを開始](https://labex.io/ja/labs/update-deprecated-manifests-663111?course=ckad-practice-exam-01)      |

#### Application Environment, Configuration and Security

|   インデックス | 名前                            | 難易度   | 練習                                                                                                           |
|----------|-------------------------------|-------|--------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ConfigMap と Secret の注入     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/inject-configmaps-and-secrets-663105?course=ckad-practice-exam-01)       |
|        2 | 🎯  リソースリクエストとクォータの適用          | 初級    | [チャレンジを開始](https://labex.io/ja/labs/apply-resource-requests-and-quotas-663094?course=ckad-practice-exam-01)  |
|        3 | 🎯  専用の ServiceAccount を使用した実行 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/run-with-a-dedicated-serviceaccount-663109?course=ckad-practice-exam-01) |
|        4 | 🎯  Pod セキュリティコンテキストの強化        | 初級    | [チャレンジを開始](https://labex.io/ja/labs/harden-a-pod-security-context-663103?course=ckad-practice-exam-01)       |
|        5 | 🎯  App カスタムリソースの作成            | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-an-app-custom-resource-663097?course=ckad-practice-exam-01)       |

#### Services and Networking

|   インデックス | 名前                                  | 難易度   | 練習                                                                                                               |
|----------|-------------------------------------|-------|------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Service を使用した Deployment の公開     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/expose-a-deployment-with-a-service-663102?course=ckad-practice-exam-01)      |
|        2 | 🎯  Ingress を使用した HTTP トラフィックのルーティング | 初級    | [チャレンジを開始](https://labex.io/ja/labs/route-http-traffic-with-ingress-663108?course=ckad-practice-exam-01)         |
|        3 | 🎯  NetworkPolicy を使用したアプリトラフィックの制限  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restrict-app-traffic-with-networkpolicy-663107?course=ckad-practice-exam-01) |
|        4 | 🎯  サービスエンドポイントアクセスのトラブルシューティング      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/troubleshoot-service-endpoint-access-663110?course=ckad-practice-exam-01)    |

### 3. [CKAD 模擬試験 02](https://labex.io/ja/courses/ckad-practice-exam-02)

CKAD 試験の出題範囲を網羅した、全 20 問の Kubernetes アプリケーション開発に関する実践的な模擬試験（第 2 弾）です。多様な運用シナリオを通じて、試験対策を行うことができます。

[コースを開始](https://labex.io/ja/courses/ckad-practice-exam-02) · ラボ: 20

#### Application Design and Build

|   インデックス | 名前                     | 難易度   | 練習                                                                                                           |
|----------|------------------------|-------|--------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ローカルワーカーイメージのパッケージ化 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/package-a-local-worker-image-663123?course=ckad-practice-exam-02)        |
|        2 | 🎯  並列データジョブの実行         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/run-a-parallel-data-job-663129?course=ckad-practice-exam-02)             |
|        3 | 🎯  アダプターサイドカーの追加       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/add-an-adapter-sidecar-663113?course=ckad-practice-exam-02)              |
|        4 | 🎯  投影ボリュームと永続データのマウント  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/mount-projected-and-persistent-data-663122?course=ckad-practice-exam-02) |

#### Application Deployment

|   インデックス | 名前                            | 難易度   | 練習                                                                                                               |
|----------|-------------------------------|-------|------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Blue-Green トラフィックの切り替え     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/switch-blue-green-traffic-663131?course=ckad-practice-exam-02)               |
|        2 | 🎯  障害が発生したデプロイメントのロールバック      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/roll-back-a-faulty-deployment-663128?course=ckad-practice-exam-02)           |
|        3 | 🎯  ローカル Helm リリースのアップグレード     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/upgrade-a-local-helm-release-663132?course=ckad-practice-exam-02)            |
|        4 | 🎯  Kustomize プロダクションオーバーレイの生成 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/generate-a-kustomize-production-overlay-663120?course=ckad-practice-exam-02) |

#### Application Observability and Maintenance

|   インデックス | 名前                   | 難易度   | 練習                                                                                                            |
|----------|----------------------|-------|---------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  低速なスタートアッププローブの修復 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-slow-startup-probes-663127?course=ckad-practice-exam-02)           |
|        2 | 🎯  失敗した設定ロールアウトのデバッグ | 初級    | [チャレンジを開始](https://labex.io/ja/labs/debug-a-failed-config-rollout-663117?course=ckad-practice-exam-02)        |
|        3 | 🎯  非推奨のポリシーマニフェストの変換 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/convert-a-deprecated-policy-manifest-663115?course=ckad-practice-exam-02) |

#### Application Environment, Configuration and Security

|   インデックス | 名前                           | 難易度   | 練習                                                                                                           |
|----------|------------------------------|-------|--------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  プロジェクト設定とシークレットファイル       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/project-config-and-secret-files-663124?course=ckad-practice-exam-02)     |
|        2 | 🎯  Namespace リソースのデフォルト設定の強制 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/enforce-namespace-resource-defaults-663119?course=ckad-practice-exam-02) |
|        3 | 🎯  App ServiceAccount の制限    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/limit-an-app-serviceaccount-663121?course=ckad-practice-exam-02)         |
|        4 | 🎯  書き込み可能なキャッシュ Pod のセキュア化   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/secure-a-writable-cache-pod-663130?course=ckad-practice-exam-02)         |
|        5 | 🎯  バージョン管理されたアプリリソースの作成      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/create-a-versioned-app-resource-663116?course=ckad-practice-exam-02)     |

#### Services and Networking

|   インデックス | 名前                              | 難易度   | 練習                                                                                                         |
|----------|---------------------------------|-------|------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Named Service Port ルーティングの修復 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/repair-named-service-port-routing-663126?course=ckad-practice-exam-02) |
|        2 | 🎯  Ingress を使用したパス分割の公開         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/publish-split-paths-with-ingress-663125?course=ckad-practice-exam-02)  |
|        3 | 🎯  特定の名前空間からのトラフィックを許可する        | 初級    | [チャレンジを開始](https://labex.io/ja/labs/allow-traffic-from-one-namespace-663114?course=ckad-practice-exam-02)  |
|        4 | 🎯  Service DNS アクセスの診断          | 初級    | [チャレンジを開始](https://labex.io/ja/labs/diagnose-service-dns-access-663118?course=ckad-practice-exam-02)       |

## LabEx について

[LabEx](https://labex.io) は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ、ブラウザ内のインタラクティブなオンライン環境で自動化されたステップバイステップのチェック機能、スキルツリーベースのシステムによる構造化されたコンテンツ組織、30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソースにより、[LabEx](https://labex.io) は包括的な実践教育を提供します。プラットフォームには、最新の AI モデルを基盤とした学習アシスタント Labby が含まれており、対話型学習体験を提供します。

