# 公式のNode.js LTSイメージをベースに採用
FROM node:18-bullseye

# 作業ディレクトリを設定
WORKDIR /workspace

# グローバルにVite CLIをインストール（必要に応じて）
RUN npm install -g vite

# コンテナ内の作業ユーザーを node に切り替え
USER node
