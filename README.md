# multi-container-app

このリポジトリは、複数のコンテナを連携させるDockerアプリケーションのサンプルです。
# Multi Containers App

This is a repo for new users getting started with Docker.

You can try it out using the following command.

```docker compose up -d```

And open http://localhost:3000 in your browser.

## 構成

- Webアプリケーション
- データベース
- その他必要なサービス

## セットアップ方法

1. DockerとDocker Composeをインストールしてください。
2. 以下のコマンドでコンテナを起動します。

```bash
docker-compose up
```

3. ブラウザで `http://localhost` にアクセスして動作を確認できます。

## ディレクトリ構成

- `web/` : Webアプリケーションのソース
- `db/` : データベース関連ファイル
- `docker-compose.yml` : サービス定義ファイル

## ライセンス

MIT