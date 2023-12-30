# discord-py-template
discordのボットを作成する際の環境構築テンプレートです

# 環境構築
## 仮想環境の作成
以下のコマンドで仮想環境を作成します
```bash
python -m venv .venv
```

作成した仮想環境を有効化します
```bash
. ./.venv/bin/activate
```

## 必要なライブラリのインストール
`requirements.txt`を使用して開発に必要なライブラリをインストールします
```bash
pip install -y -r requirements.txt
```

## botアカウントの作成・トークンの設定
- [Botアカウント作成](https://discordpy.readthedocs.io/ja/latest/discord.html)ページを参考に、Botアカウントを作成します
- Botごとにtokenが発行されるので、コピーします
- 同リポジトリ内、`.env.example`をコピーし、`.env`という名前に変更します
- `.env`内、`TOKEN`にコピーしておいたtokenを設定します

# botの構築
環境構築が完了次第、botの構築に取り掛かります
