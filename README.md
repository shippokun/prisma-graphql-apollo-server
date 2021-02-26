# Prisma x GraphQL API Server

## init

```bash
npm install             # 依存関係のインストール
docker-compose up -d    # postgres server の立ち上げ
npx prisma generate     # prisma によるライブラリの生成
```

## development

開発サーバーの立ち上げ

```bash
npm run dev
```

マイグレーション

```bash
npx prisma migrate dev --preview-feature
```

シード

```bash
npx prisma db seed
```