# README

## 主な機能

- ログイン
- 画像アップロード (S3)
- DBアクセス

## 利用に際して

### 依存パッケージ

以下、パッケージがインストールされていない場合、インストールしてください。

- ImageMagick
- ImageMagick-devel
- nodejs

### 環境変数

`.env` ファイルを作成し、変数を設定してください。

- AWS_ACCESS_KEY_ID: AWSのアクセスキー ID
- AWS_SECRET_ACCSESS_KEY: AWSのシークレットアクセスキー
- BUCKET_NAME: S3のバケット名
