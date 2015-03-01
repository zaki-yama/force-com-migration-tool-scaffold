Force.com Migration Tool Scaffold
=================================

Force.com Migration Tool (Force.com 移行ツール) を使用するための初期ファイル群です。

### Usage

- 事前に Force.com Migration Tool をインストール
	- https://help.salesforce.com/apex/HTViewSolution?id=000176910&language=ja
- `build.properties.sample` に自分の組織のusername, password を入力し、`build.properties` として保存
- `build.xml` に記載されたコマンドを実行
	- `retrieveCode`: コードを取得
	- `deployCode`: コードをデプロイ
	- `removeCode`: コードを削除
