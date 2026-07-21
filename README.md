# 殴性格診断

8問の4択質問に答えると、メンバーの中から最も近いタイプが診断される性格診断Webアプリ。

- HTML / CSS / JavaScript の単一ファイル構成(ビルド不要)
- 結果はテキストまたは画像としてクリップボードにコピー可能(画像化には [html2canvas](https://html2canvas.hertzen.com/) を使用)

詳しい仕様は [spec.md](spec.md) を参照。

## ローカル確認

```bash
npx serve .
```

## デプロイ

`index.html` がリポジトリ直下にあるため、Vercelにインポートするだけでビルド設定なしに公開可能。
