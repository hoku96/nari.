# NARI. ランディングページ（デプロイ用・完全埋め込み版）

## ファイル構成（たった2ファイル＋α）
```
index.html                 … LP本体。画像・ロゴ・診断ツールぜんぶ内蔵。
NARI_free_diagnosis.html   … 無料診断ツール（LPの「無料診断」ボタンの遷移先）
.nojekyll                  … GitHub Pages用の設定ファイル（消さないでください）
```
**画像はすべてHTMLの中に埋め込み済みです。** logoフォルダや画像ファイルは不要になりました。
この2ファイル（＋.nojekyll）をアップするだけで、ロゴも写真も全部表示されます。

## GitHub Pages 公開手順
1. GitHubのリポジトリを開く。
2. 「Add file」→「Upload files」で、**index.html と NARI_free_diagnosis.html と .nojekyll の3つ**をドラッグ＆ドロップ。
   （フォルダは無いので、フォルダのアップミスは起きません）
3. 「Commit changes」で確定。
4. Settings→Pages→Source=「Deploy from a branch」、Branch=main、フォルダ=/(root) でSave。
5. 1〜2分で公開。ロゴも正しく表示されます。

## 以前ロゴが表示されなかった原因
GitHubのブラウザ操作で `logo` フォルダがアップロードされず、ロゴ画像だけ読み込めていませんでした。
今回から画像を全部HTMLに埋め込んだので、フォルダ切れの心配がなくなりました。

## 連絡先（設定済み）
- TEL: 090-7769-0612 ／ MAIL: 0612karinyamashita@gmail.com ／ LINE: QRコード & https://lin.ee/w8XAYTs
