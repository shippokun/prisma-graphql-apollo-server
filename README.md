# Prisma x GraphQL API Server

## 開発準備

```bash
npm install             # 依存関係のインストール
docker-compose up -d    # postgres server の立ち上げ
npm run setup           # セットアップコマンド
```

## 開発

開発サーバーの立ち上げ

```bash
npm run dev
```

マイグレーション

```bash
npm run migrate
```

シード

```bash
npm run seed
```

## etc

HTTP SERVER: apollo-server
GraphQL Schema: @nexus/schema

## docs

- [prisma setup guide](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch-typescript-postgres)
- [prisma graphql intro](https://www.prisma.io/docs/concepts/overview/prisma-in-your-stack/graphql)
