# 小説の文字数を数える

　日本語の小説における文字数を数える。

## 書式

* HTML
* プレーンテキスト形式（漢字の直後にある全角括弧をRubyに変換する）
* 中間テキスト形式
    * カクヨム
    * なろう
    * でんでんマークダウン

　中間テキスト形式はルビを表現する方法として`｜漢字《かんじ》`のような特殊記法がある。このとき`｜`や`《》`などをメタ文字と呼称する。

## 数え方

### 数えない文字種

* メタ文字
* ルビ文字
* 空白文字
    * スペース（半角、全角）
        * 行頭のスペースは数える
        * 行頭でも行末でもないスペースは数える
    * 改行（`\n`,`\r`,`\r\n`）
    * タブ（`\t`）
* 括弧
    * 鉤括弧`「」`, 全角／半角
    * 括弧`（）`, 全角／半角
* 三点リーダー`…`
* ダッシュ`―`
* 句読点
    * 句点`。`
    * 読点`、`
* エクスクラメーション: `！`
* クエスチョン: `？`

### 1文字として数える文字

* 3つ以上連続した文字（「あああぁぁぁぁ」=2、「URYYYYYYY！」=4）

