Firebase Cloud Messagingを使ったチャットアプリの作成という感じで素振りした跡地です。
ついでにいくつか触ってみたい技術も使ってみました。
## 構成
### Front

Next.js

TypeScript

### Backend

tRPC + Zod

Prisma

### DB
planetscale

## 画面

<img width="1794" alt="スクリーンショット 2022-12-31 0 41 53" src="https://user-images.githubusercontent.com/36734151/210087795-9ab2b67f-4ce8-478e-a541-34211b113666.png">

## その他
PWA対応しており、ブラウザからアプリとしてダウンロードすると対応しているブラウザならチャット送信時にバックグラウンド通知が飛ぶようになっている（はず）
