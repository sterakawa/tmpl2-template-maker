# tmpl2-template-maker

GUIでSPIXD / tmpl2用テンプレートを作るための小さなツールです。

## v0.1

- SPIXD向け設定パネル
- スマホ / PCプレビュー切替
- 背景色・文字色
- タイトル画像・タイトル・説明文
- ハッシュタグとコピー文言
- LINE / X / Facebook / Download の表示設定
- 全削除ボタンの表示設定
- tmpl2の `LIST_PHOTO` loopを含むHTML生成

現段階は仕様を固めるためのプロトタイプです。既存SPIXDテンプレートを追加しながら、生成HTMLを実運用形式へ近づけます。

## 方針

「自由なHTMLエディタ」ではなく、SPIXDの共通骨格を保護し、案件ごとの差分だけをGUIで変更できるTemplate Makerを目指します。スマホファーストで、同一HTMLをPCにもレスポンシブ対応させます。
