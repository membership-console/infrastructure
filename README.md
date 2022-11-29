# Infrastructure

本リポジトリでは Membership Console のインフラ設定を管理します。

## 開発

### 開発環境

- Docker
- Kubernetes

### 起動方法

```shell
$ kubectl apply -f k8s
```

### リソースの削除

```shell
$ kubectl delete -f k8s
```