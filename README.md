# Redmine用テーマ "farend basic"

## このテーマについて

Redmine用のカスタムテーマです。日本語環境で見やすい画面を実現することを目的に、Redmine付属のデフォルトテーマを元に作成したものです。

デフォルトテーマに対する変更は必要最小限としていますので、見た目が大きく変わることはありません。既にRedmineを運用中の組織でも利用者を混乱させずにスムーズに移行できます。

このテーマは、Redmimeのクラウドサービス [My Redmine](https://hosting.redmine.jp/) のサービス提供用に開発し、OSSとして公開したものです。

[<img src="https://www.farend.co.jp/files/myredmine-logo/hz/myredmine-logo-hz.png" width="250">](https://hosting.redmine.jp/)

## 特徴

* 日本語フォントを優先して使用するよう設定を行いました。これにより、￥記号がバックスラッシュとして表示されていた問題が解決します（WindowsおよびメイリオがインストールされているMacのみ）
* メイリオフォントがインストールされている環境ではメイリオを使って文字が表示されますので、画面上の文字が読みやすくなります
* 文字と背景のコントラストを高めて読みやすくするために、文字の色を全体的に見直しました
* チケット一覧画面において優先度に対応した色分け表示を行うための設定をRedmine標準添付のAlternateテーマから取り込みました
* チケット一覧画面において期限が超過したチケットをオレンジ色で表示するよう変更しました
* チケット一覧画面において担当者・作者欄の自分の名前を太字で表示するよう変更しました

## 利用環境

## インストール方法

### 1: テーマが格納されたディレクトリを作成

Redmineのインストールディレクトリで以下のコマンドを実行してください。

```
git clone https://github.com/farend/redmine_theme_farend_basic.git themes/farend_basic
```

#### Redmine 6.0 の場合

Redmineのインストールディレクトリで以下のコマンドを実行してください。

```
git clone -b redmine6.0 https://github.com/farend/redmine_theme_farend_basic.git themes/farend_basic
```

#### Redmine 5.1 以前の場合

Redmineのインストールディレクトリで以下のコマンドを実行してください。

```
git clone -b redmine5.1 https://github.com/farend/redmine_theme_farend_basic.git public/themes/farend_basic
```

### 2: テーマの設定を変更

Redmineの管理画面で新しいテーマを利用する設定を行います。

「管理」→「設定」→「表示」画面内の項目「テーマ」で「Farend basic」を選
択、画面最下部の「保存」ボタンをクリックしてください。
