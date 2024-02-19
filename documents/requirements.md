## 一言サービスコンセプト

ペスコタリアン、オリエンタル・ベジタリアンなど多種多様なベジタリアンに対応！
あらゆるベジタリアンのための"**食**"情報サイト

## 誰のどんな課題を解決するのか？

ベジタリアンの方が、自身のベジタリアンの種類に対応した料理のレシピや、レストランのメニュー、お店の商品を探そうとする際、多種多様なベジタリアンの中の一つである**ヴィーガン**に対応しているか否かといった情報が多少あるだけで、**その他のベジタリアン向けの情報がない**といった、日本のベジタリアン界の課題を解決します。

## なぜそれを解決したいのか？

### 日本のベジタリアン人口

[日本のベジタリアン・ヴィーガン・フレキシタリアン人口調査 by Vegewel](https://vegewel.com/ja/style/statistics3)によると、ベジタリアンもしくはヴィーガンは全体の 5.9％、週に 1 回以上、意識的に動物性食品を減らす食生活を送るフレキシタリアンは全体の 19.9％であり、いずれも 2 年前の調査から増加しています。近年、大豆ミートなどの代替肉や豆乳チーズ食品もスーパーに並ぶようになったことからも、ベジタリアンという食文化が広まっていることが伺えます。

私はインドのヴェーダ哲学に基づくヨーガの修行者です。その関係で、4 年程前に**オリエンタル・ベジタリアン**になりました。

オリエンタル・ベジタリアンとは、日本の精進料理がそれに該当し、肉・魚・卵の他に**五葷（ごくん）**と呼ばれる野菜(玉ねぎ、ねぎ、にんにく、らっきょう、にら)を食べないベジタリアンを指します。一切の動物性食品を避ける**ヴィーガン**とは違い、殺生をしない動物性食品(乳製品やはちみつ)はありがたくいただきます。
その他にも、肉は食べないが魚は食べる**ペスコタリアン**、卵は食べる**オボ・ベジタリアン**、完全に肉を食べないまで行かないものの減らそうと努めている、いわゆる「ゆるベジタリアン」のフレキシタリアンなど、一言に「ベジタリアン」と言っても、実はたくさんの種類のベジタリアンが存在しています。

※ヴィーガンとフレキシタリアンをベジタリアンと別の分類とする考え方もありますが、ここでは大きな枠でのベジタリアンに含まれることとします。

### ベジタリアン向けの食の情報

日本において、ベジタリアンが食べられるものを探そうとした時に参考にできるのは、唯一ヴィーガンの方向けの情報です。ヴィーガン専門レシピサイトであったり、レストランのメニューや商品についているヴィーガンマークといったヴィーガン向けの情報であれば、現在の日本において多少目に入るようになってはきています。

例えば、ペスコタリアンやオボ・ベジタリアンの方であれば、ヴィーガンメニューはすべて食べることができます。ヴィーガンの方が食べられるものに加えて魚も食べられるのがペスコタリアン、ヴィーガンの方が食べられるものに加えて卵も食べられるのがオボ・ベジタリアンだからです。

しかし、オリエンタル・ベジタリアンとなるとそうはいきません。野菜の中でも、先述した五葷を食べないので、ヴィーガンメニューにも食べられないものがあるのです。ヴィーガンメニューは肉などで味を出せないので、特にたまねぎやにんにくが多く使われる傾向があり、ヴィーガンメニューでも意外と食べられないものが多いのです。

また、ヴィーガン以外の「ヴィーガンメニューが食べられるベジタリアン」においても、本来ヴィーガンメニュー以外にも食べられるものがたくさんあるはずなのに、ヴィーガンメニューに限定されてしまいます。

### ベジタリアン以外の方との関わりの中で

ベジタリアンの食の情報が少ないということは、自分だけの問題に留まりません。
家族や友人などと外食に行く際には、少ない情報の中から一緒に行けるレストランを探すか、自分だけ何も食べないといった選択をすることになってしまいます。

もっとレストランの情報たくさんあれば、そういった際の選択肢が広がります。
また、対応するレシピであれば、自分自身はもちろん、ベジタリアンであることに配慮して料理を作ってくれる家族への負担も大きく減らすことができるでしょう。

私自身が実際にこれらの問題に直面しています。
そのため、地域社会の中であらゆる種類のベジタリアンがより良い食生活を送ることができるように、ヴィーガンだけでない様々なベジタリアンの種類に対応した情報が得られるサービスを作りたいと思ったのです。

## 4. どうやって解決するのか？

ベジタリアンの種類に応じたレシピ情報、レストラン情報、ベジタリアン向け商品の情報が得られる Web サイトを作成する。

## 5. 機能要件

【レシピ情報】

- 会員登録すると、お気に入りの情報を保存することができる
- タグを付けることで、どのベジタリアンの種類に対応した情報なのかが分かる
  - よく使われるタグはデフォルトで投稿画面に表示されていて、ワンクリックで付けられる
  - デフォルト以外にも、自分で入力してタグ付けすることができる
  - レシピでは、どのベジタリアンの種類に対応したレシピになっているか、登録された材料から判別して自動でタグ付けされる（確認画面あり）
- レシピの材料をクリックすると、ベジタリアン向け商品情報から該当商品を検索した一覧が表示される
- レシピには他ユーザーがコメントできるようになっており、質問や、作ってみた感想などを投稿できる
- 「いいね」機能がある
- レシピには画像のほか、動画も投稿できる（動画のみは NG）
- レシピ検索は、人気順（いいね数）、新着順でソートできる
- 自分用の非公開レシピも登録できる

【レストラン情報】

- レストランに対して口コミのようにユーザーが情報を投稿する
- レストラン情報は Google マップと紐づいている
- 自身のベジタリアンの種類、食べられるメニュー、コメント、評価等の情報を投稿できる
- レストランマップはベジタリアンの種類などで検索することができる

【ベジタリアン商品情報】

- 購入できる場所、オススメの使い方などを投稿できる
- 投稿に対して、他のユーザーがコメントすることができる
- レシピ情報と紐づけて、その商品を使ったレシピ一覧を表示できる

【本棚機能】

- 「マイルーム」に情報整理のための「本棚」を設置できる
- 「本棚」にはお気に入りのレシピ、レストラン、商品の情報を保存できる
- 「本棚」は複数作ることができ、「お菓子」や「和食」など任意の名前をつけることで情報の整理ができる
- 自身で作成した非公開レシピやメモも登録できる

## 5. 非機能要件