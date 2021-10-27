# docker-webpack-ts

## 使い方

ホスト側のディレクトリをマウントして監視

/opt/webpack/src/ ホスト側のts入力用

/opt/webpack/dist/ ホスト側のjs出力用

### package.json の ver up

ホストで以下を実行 nodeがインストール済みであること

```sh
cd gulp
npm install -g npm-check-updates
ncu -u
```

### 本番用build

コンテナ内で下記実行

```
npm run build
```