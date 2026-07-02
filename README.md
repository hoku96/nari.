# NARI. ランディングページ

成田市のローカルビジネス支援「NARI.」の公式ランディングページ一式です。

## ファイル構成
```
index.html                 … LP本体（トップページ）
NARI_free_diagnosis.html   … 無料診断ツール（LPの「無料診断」ボタンの遷移先）
temple-hall.jpg            … ヒーロー背景（新勝寺 本堂）
temple-sunset.jpg          … 街紹介セクション（新勝寺 夕景）
diag-preview.png           … 診断バナーのスマホプレビュー画像
line-qr.png                … 連絡先の公式LINE QRコード
founder/karin3_avatar.jpg  … 代表 山下果林 の写真
```
※ 画像はHTMLから相対パスで参照しています。**フォルダ構成を変えずにそのままアップロードしてください。**

## GitHub Pages での公開手順
1. GitHub で新しいリポジトリを作成（例: `nari-lp`）。Public を選択。
2. このフォルダの中身（`index.html` を含む全ファイル・`founder` フォルダごと）をリポジトリのルートにアップロード。
   - ブラウザ操作の場合: リポジトリの「Add file」→「Upload files」で全ファイルをドラッグ＆ドロップ（`founder` フォルダもフォルダごとドラッグ可）。
3. リポジトリの「Settings」→左メニュー「Pages」を開く。
4. 「Build and deployment」の Source で「Deploy from a branch」を選択。
5. Branch を `main`（または `master`）、フォルダを `/ (root)` に設定して Save。
6. 1〜2分待つと、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

## 公開後にやること
- LP・診断ツールの内容修正は `index.html` / `NARI_free_diagnosis.html` を直接編集して再アップロードすればOK。
- 独自ドメイン（例: nari-narita.com など）を使う場合は、Settings→Pages の「Custom domain」で設定。

## 連絡先（設定済み）
- TEL: 090-7769-0612（`tel:` リンク済み）
- MAIL: 0612karinyamashita@gmail.com（`mailto:` リンク済み）
- LINE: line-qr.png のQRコードで友だち追加

## メモ
- `.nojekyll` ファイルは、GitHub Pages が `founder/` フォルダ等をそのまま配信するために置いています。削除しないでください。
