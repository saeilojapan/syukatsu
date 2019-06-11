# syukatu

鮮文大学の生徒の就活をサポートするサイト
1.top
2.自己啓発
3.就活について
4.ES作成
5.FAQとお問い合わせ

就職率を上げるためには
1.大学生活の充実化
2.自己理解
3.自分が輝けるポジション（社会理解）
4.就活のシステム、流れの把握
5.実践スキルの向上（ES、面接、適性検査、エージェント、就活サイト等）

自己啓発ページの目的
・大学生活の充実化
・目標達成（実績作り）のサポート
就活についてページの目的
・日本の大学生の就活事情を知る
・鮮文大学の現状を知る
・就活を上手くこなせる方法の例を提案
ES作成ページの目的
・ES作成のスキル伝授
・自己分析、業界分析の行い方伝授
FAQとお問い合わせページの目的
・就活に関する知識の共有
・大学とのコミュニケーション

ページ構成 
・トップページ　ファイル名： index.html
header:一番上の固定ヘッダー部分
nav-drawer：スマホで見る時に表示されるハンバーガーアイコンとその内容
top：見出しの大きなトップ部分　「thinkout」
about：ページの概要説明部分
select-text：名言部分
select：４つのボタン部分
footer：フッター

・自己啓発ページ　ファイル名：　self-development.html
header
nav-drawer
top
interest:前書き部分
faq:ボタンを押すと内容表示部分（ほかのページと共通している。そのため、名前がfaq)
Download:ボタンを押すとダウンロードが始まる「７つの習慣書式」
footer

・就活についてページ　ファイル名：　syukatsu.html
header
nav-drawer
top
interest
faq
Download:ボタンを押すとFAQページに飛ぶ
footer

・ES作成ページ　ファイル名：　ES.html
header
nav-drawer
top
interest
faq
Download:ボタンを押すとダウンロードが始まる「２０１８年に就活サークルが作った就活book」
footer

・FAQとお問い合わせページ　ファイル名：　FAQ.html
header
nav-drawer
top
interest
faq
form:グーグルフォームと紐づいている。内容を記入してお問い合わせを押すとグーグルフォームの記入が終わる画面にいく。その知らせが守山と佐藤清美さんのメールに通知として飛ぶ。
footer


・stylesheet.css
デザイン部分。修正する場合は、共通の部分は変更するとそこに対応する部分すべて変わるので注意が必要。

・responsive.css
画面幅が変わった時のデザイン部分
1005px以下の時（タブレットで観覧を想定）
720px以下の時（スマホで観覧を想定）

・script.js
jQueryで動的動作の追加
今回jsを使った部分はボタンを押すと中身が表示されるfaq部分の１つだけ。

・
