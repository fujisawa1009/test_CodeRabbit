# test_CodeRabbit

以下を作成
TL/test_CodeRabbit/.github/workflows/ai-review.yaml
カスタマイズ設定ファイルを直下に配置
TL/test_CodeRabbit/.coderabbit.yaml

# GitHubのSecretsにOPENAI_API_KEYを設定
「Settings」→「Secrets and variables」→「Actions」
→「New repository secret」
→「Name」フィールドに「OPENAI_API_KEY」と入力します。
→「Secret」フィールドにOpenAI APIキーの値を貼り付け
→「Add secret」ボタンをクリックして保存します。

# OpenAI APIキー作成
https://platform.openai.com/docs/overview
①ホーム画面右上の「Personal」から「View API keys」をクリックします。
②「+Create new secret key」をクリックします。
③「Create secret key」をクリックします。
④生成されたURLを、緑のボタンをクリックしてコピー
