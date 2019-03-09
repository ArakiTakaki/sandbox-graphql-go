# GraphQL

## 初期設定

1. schemaを設定する
2. `$ go run go run github.com/99designs/gqlgen`を実行
3. `resolver.go`を弄る

## メリット

- スキーマの構成に集中できるので楽
- 参照先がschema.graphqlで完結する(モデル含み)

## デメリット

- スキーマのロジックをどこに置くか
- 煩雑になりそう(マイクロサービス向き)
- Modelを作成する必要
- 最初に全部`schema`を作成しておかないと自分で`resolver.go`のQueryLogicを定義しなければいけないような気がする。
