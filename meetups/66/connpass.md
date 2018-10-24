# Shinjuku.rb って何？

Shinjuku.rbは新宿周辺のRuby技術者たちが気軽に相談することを目的としたコミュニティです。
ミートアップは、参加者全体でのディスカッションを大事にしており、毎月第４水曜日に開催されます。

[Qiita - Shinjuku.rbに行こう！](https://qiita.com/treby/items/c11da012f4dacb02f5cc)

過去の発表や雰囲気については[メモ](https://github.com/shinjukurb/meetups/meetups) より参照できます。

# テーマ: frontend

おそらく、「Rubyエンジニア」の9割以上が触ったことのあるだろうRailsアプリケーション。

その中でも見た目を司るfrontendについて、ここ1, 2年に開始したプロジェクトであれば元から分離することを意識した作りになっているかもしれませんが、それ以上前であったりMVP(Minimum Viable Product)を意識して開始したプロジェクトだといわゆるセオリー通りにできていないことも少なくありません。
例えば、

- jQuery / CoffeeScriptとの付き合い方
    - 使っていますか？それとも脱却しました？
- frontendエコシステムの分離
    - gem化されているものを使っています？
    - それともfrontendは独立してパッケージ管理しています？
- Railsのhelperとの付き合い方
    - 利用しています？それとも脱却しちゃいました？CSRF tokenとかどうしてます？
- Railsからfrontendへの値の受け渡し
    - 完全SPA化されています？
    - それともグローバル空間を使って値の受け渡しをしています？
    - APIエンドポイントだけ知らせてます？APIはRESTですか？GraphQLですか？それとも独自？
- frontend componentの画面へのアタッチ
    - 都度都度scriptタグ内でアタッチしてます？
    - それとも何らかの規約を作っています？

などで、悩んでいるチームも少なくないのではないでしょうか。

今回のShinjuku.rbではそんな理想(「こうあるべきだよね！」)と現実(「とはいえ、こういう事情があるから今はこうなっている」)、そしてその差を埋めるための取り組み(「自分たちのチームではこうしています／こういう風に変えていっています」)の知見を共有していければと思います。

技術的な新しさよりも、チームにおけるフロントエンドの立ち位置(「ガッツリ開発」なのか「片手間開発」なのか)や実際の事業においてどう生かしているのか、どう折り合いをつけているかのお話ができると嬉しいです。

# トーク(LT) & ディスカッション

LTをしていただける方を募集します! LT参加をご希望の方は、LTタイトルが決まりましたらconnpass feedへLTのタイトルをご記入下さい。


- Vueのバージョンアップをしている際に得られた知見とVuexの使いどころ by [treby006](https://twitter.com/treby006)
- 段階的にフロントエンド開発 by [@tomlla_92](https://twitter.com/tomlla_92)

また、Shinjuku.rbではディスカッションを大事にしています。 そのため、トーク中にコレってどうしたらよさそう？などの質問が随時発生する点了承ください

# タイムテーブル

時間 | 内容
--- | ---
19:00 | 開場
19:30 | はじめに・自己紹介
20:00 | LT(トーク) & ディスカッション * 4
21:00 | 振り返りと次回内容のアイディア出し
21:10 | 懇親会
22:30 | 順次解散!

# 会場

[Repro株式会社](https://repro.io/)

- JR線「新宿駅」南口から徒歩10分
- JR線・都営地下鉄大江戸線「代々木駅」北口から徒歩1分

## 設備

- WiFiあります。
    - SSID/PWは会場前方に書いてあります。
- 喫煙所は9Fにあります
- コーヒーマシンあり。コーヒーは自由に飲んで頂いて結構です
- 飲食可能です。
    - フロアに自販機はありませんが、1Fにコンビニやマクドナルドがあります
- 電源あります。足りない場合はお声がけください

## アクセス

こちらの建物の6Fです

![](https://raw.githubusercontent.com/shinjukurb/meetups/master/assets/images/sponsers/repro-access-1.png)

エレベーターから降りて左に進み、会場にお入りください

![](https://raw.githubusercontent.com/shinjukurb/meetups/master/assets/images/sponsers/repro-access-4.png)

迷いましたら、[slack](http://shinjukurb-slackin.herokuapp.com/)もしくは、twitterにて #shinjukurb 付きのtweetでご連絡ください

# スポンサー

会場・飲食の提供

[Repro株式会社](https://repro.io/)

# 留意事項

- どなたでもblogなどにあげられるよう写真撮影を許可していますので、その点ご了承ください
- 質問・疑問などは、[slack](http://shinjukurb-slackin.herokuapp.com/)もしくは、twitterにて #shinjukurb 付きのtweetでご連絡ください
