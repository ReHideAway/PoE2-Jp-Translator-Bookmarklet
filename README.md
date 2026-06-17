# 対応状況
- PoE2 バージョン： 0.5.2

# PoE2-Jp-Translator-Bookmarklet
- PoE2 Jp-Translator Bookmarklet: A lightweight browser tool that instantly replaces English PoE2 terms with Japanese translations on any web page.
- このブックマークレットはPoE2向けの英語Webサイトのスキルジェムやパッシブスキルを単語単位で日本語化するブックマークレットです。

# 使用イメージ
![mobalytics イメージ](mobalytics.png "mobalytics")

# 使用方法
※詳細は後で書く
bookmarklet.jsをブックマークに保存する。
1. ブックマークを右クリック
2. ページを追加...
3. 名前は適当にJpTran等
4. URLにBookmarklet.jsの内容をコピペして保存
  - javascript:(functi........();とかなり長いが関係なくコピペして問題無し
5. 単語変換したいWebページで先ほど作ったブックマークを押す

# 辞書の変更方法
※詳細は後で書く
特定の辞書のみにしたり、自作辞書を追加など
github gistでindex.jsonで読み込む辞書を登録しているので、自分で準備すれば変更可能

# 注意
- 辞書が変更されてもブラウザのキャッシュの影響ですぐに更新されない可能性があります。

# 対応状況・更新
- 2026/06/17 - Support Gem に対応
- 2026/06/16 - Active Skill に対応
- 2026/06/16 - Passive Skill に対応
