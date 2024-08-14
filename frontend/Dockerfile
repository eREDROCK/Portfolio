FROM node:22-slim

# 作業ディレクトリの設定
WORKDIR /usr/src/app

# # package.jsonとyarn.lockをコピーして依存関係をインストール
# COPY frontend/package.json frontend/yarn.lock ./
# RUN yarn install

# アプリケーションのソースコードをすべてコピー
COPY . ./

# # Next.jsアプリケーションのビルド
# RUN yarn build

# # アプリケーションをデフォルトで起動するコマンド
# CMD ["yarn", "start"]