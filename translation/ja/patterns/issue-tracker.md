## Title

イシュートラッカーの使い方を多様化する

## Patlet

インナーソースのホストチームは、計画や進捗だけでなく、変更の背景も透明化することができていません。これは、プロジェクトのイシュートラッカーのユースケースを増やし、ブレーンストーミング、実装の議論、機能設計にも使えるようにすることで解決することができます。

## 問題

あるチームが、組織内の多くのチームが依存するコンポーネントを開発しています。このチームは、未解決のバグや機能要求を追跡するために、標準的なイシュートラッキングシステムを使用しています。しかし、各エントリのコンテキストは非常に限られています。その結果、潜在的なコントリビューターは、各課題がどのような変更について話しているのかを知る術がありません。

## 状況

インナーソースのプロジェクトツールはすべてセットアップされています。しかし、プロジェクトのイシュートラッキングシステムは、主に進捗の共有のために使用されます。インナーソースプロジェクトでは、リモートでの非同期通信を容易にするために、イシュートラッカーが使用できるユースケースは他にもたくさんあります。

## 組織に働く力学

* コントリビューターは、自分たちが必要としている機能がすでにロードマップにあるかどうかを理解したいと思っています。しかし、イシューには多くの文脈が欠落しており、既存のイシューがコントリビューターのニーズに合致しているかどうかを判断することは不可能です。
* その結果、多くの重複したイシューがオープンされ、ホストチームがそれに対処しなければならなくなります。
* オープンなイシューの文脈は非常に限られているため、コントリビューターはすでにオープンになっている簡単なイシューを実装して、ホストチームを助けることができません。その結果、多くの作業がホストチームの手に委ねられることになります。
* 口頭でのコミュニケーションに重点を置いているため、数ヶ月後や数年後に、なぜとある機能が実装に選ばれたのかを見極めることができません。その結果、リファクタリング、特にコンポーネントの簡略化は、プロジェクト考古学そのものとなり、議論されたことを覚えている人たちの脳を巻き戻して考えるしかなくなります。

## ソリューション

純粋なソフトウェア開発だけでなく、新機能の企画段階でも「言葉より文字」の哲学を受け入れましょう。

* バグ、計画された機能、機能のアイデアについては、それぞれ別のイシューを作成します。それぞれのイシューには、外部の潜在的なコントリビューターが文脈を理解できるように、可能な限り多くの情報を含めるようにします。理想的には、特に簡単な変更については、外部のコントリビューターが問題の機能を実装することでホストチームをサポートできるよう、十分な情報を含めることです。
* 質問するためのチャネルとして、イシュートラッキングシステムを利用することができます。これは、ユーザーの質問に対応するための他のコミュニケーション源が不足している場合に、特に有用です。
* 異なる目的で使用されるイシューを区別するために、タグやカテゴリーを使用します。
* 非同期でブレーンストーミングを始めるには、アイデアを集めるためにイシューを開きます。議論が落ち着いてきたら、このイシューで指摘されたことを別の文書にまとめます。それをプルリクエストとして投稿し、まだ説明が必要な個々のポイントについて掘り下げます。出来上がった文書は、他の適切なチャンネルで結果を公表したり、将来の参考資料として使用したりすることができます。
* ほとんどのイシュートラッキングシステムで、イシューのテンプレートを作成することができます。バグレポートに必要な情報を集めるだけでなく、他の用途でどのような情報が必要なのかのヒントも含めて活用しましょう。

## 結果の状況

* プロジェクトのイシュートラッキングシステムをコミュニケーションに活用することで、外部のコントリビューターがプロジェクトの動向を把握し、何をコントリビュートすべきかをより的確に判断することができるようになります。
* 文書によるコミュニケーションに重点を置くことで、ホストチームのメンバーがリモートで参加できるようになった。
* 常に文書でコミュニケーションすることで、プロジェクトの決定事項に関する受動的な文書が副産物として蓄積され、特別な注意を必要としなくてすみます。
* 公開コミュニケーションチャネルを一貫して使用することで、より多くの人間が議論に参加することになります。つまり、質問に答えたり、未解決の問題を指摘したり、計画中の機能の欠点を指摘したりできる、より多くの知識を持った人間を巻き込むことができるようになります。
* ディスカッションを公開の場に移すことで、将来のコントリビューターとなる可能性のあるメンバーがが、プロジェクトに参加する必要が生じるずっと前に、プロジェクトに潜り込み、フォローし、慣れ親しみ、プロジェクトのやり方を学ぶ機会を作ることができます。

## 事例

* Europace AG - ブログをご覧ください [Issue Use Cases](https://tech.europace.de/post/using-issues-for-asking-questions-and-tracking-work/)

## 著者

Isabel Drost-Fromm

## ステータス

Structured

## 翻訳の履歴

- **2022-06-06** - 翻訳 [Yuki Hattori](https://github.com/yuhattor)
- **2022-06-13** - レビュー [@kanazawazawa](https://github.com/kanazawazawa)
