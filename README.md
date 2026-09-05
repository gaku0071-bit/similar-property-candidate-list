# 類似物件候補リスト

営業支援の問い合わせ物件を基準に、リアプロから類似物件候補を作成するChrome拡張機能です。

## 初回導入

1. [最新版ZIPをダウンロード](https://github.com/gaku0071-bit/similar-property-candidate-list/releases/latest/download/similar-property-candidate-list.zip)します。
2. ZIPを任意の固定フォルダへ展開します。
3. Chromeで`chrome://extensions`を開き、デベロッパーモードを有効にします。
4. 「パッケージ化されていない拡張機能を読み込む」を押します。
5. `manifest.json`が入っている展開先フォルダを選択します。

## 更新方法

1. 営業支援画面の「最新版ZIPをダウンロード」を押します。
2. ZIPを展開し、現在Chromeで読み込んでいる拡張機能フォルダへ中身を上書きします。
3. Chromeで`chrome://extensions`を開きます。
4. 「営業支援 類似物件抽出（試作A）」の「再読み込み」を押します。
5. 営業支援画面を再読み込みします。

## 現在のバージョン

`0.10.3`

## 注意

- リアプロなどのID・パスワードは、このリポジトリや配布ZIPに保存していません。
- Chromeへ開発中の拡張機能として読み込むため、ZIPの展開・上書き・拡張機能の再読み込みは手動です。
- 旧バージョンへ戻す場合は、GitHub Releasesから該当バージョンをダウンロードしてください。
