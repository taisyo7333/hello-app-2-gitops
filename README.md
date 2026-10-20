# hello-app-2-gitops

このリポジトリは 1 回の払い出し専用です。共有の platform-gitops には置きません。

- Namespace `hello-app-2`
- Deployment `hello-app-2` replicas 2
- ServiceAccount の `eks.amazonaws.com/role-arn` は `arn:aws:iam::977099000999:role/s3read-hello-app-2-hello-app-2`
- Pipeline が CloudFormation でバケット `hello-app-2-1020` と IAM ロールを作り、イメージをビルドします
