# 修了証・評価レポートのサンプル

このディレクトリには、Honeycomeエンジニア研修プログラムで生成される修了証と評価レポートのサンプルが含まれています。

## ファイル一覧

- **certificate-example.md**: 修了証のMarkdown版サンプル
- **certificate-example.html**: 修了証のHTML版サンプル（PDF生成用）
- **report-example.md**: 評価レポートのサンプル

## 使用方法

これらのサンプルは、実際の修了証と評価レポートの出力形式を確認するためのものです。

新しいサンプルを生成するには、以下のコマンドを実行してください：

```bash
cd automation/certificate-generator
node generate-example.js
```

生成されたファイルは自動的にこのディレクトリに移動されます。
