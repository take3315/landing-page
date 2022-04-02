+++
author = ""
date = 2021-07-16T15:00:00Z
excerpt = ""
image = "/images/blog/yamto_ogp.png"
image_alt = ""
layout = "post"
subtitle = ""
tags = "コミュニティブログ"
thumb_image = "/images/blog/yamto_ogp.png"
thumb_image_alt = ""
title = "Yamato Protocol - 初心者向け基礎解説"
[seo]
description = ""
title = ""
[[seo.extra]]
keyName = "property"
name = "og:image"
value = "https://defigeek.xyz/images/blog/yamto_ogp.png"

+++
**※**⚠️**記事の内容は投稿時点のものです。  
開発中につき、担保率・手数料を含む全ての仕様はメインネットローンチまで変更になる可能性があります。正式な仕様は公式ドキュメントで公開される予定です。**

### はじめに

DeFiGeek Community JAPANはいくつもの分散型金融アプリケーションの構築を進めています。

その中核となる第一の分散型アプリケーションが「**Yamato Protocol**」です。

※「分散型」とは管理運営する権限を持った責任主体が存在せず、コンピュータプログラムのみによって決まった動作をするものです。

### Q＆A

#### Q,Yamato Protocolは何ができるのか？

暗号資産を担保にして、日本円と等価の"**CJPY**"（Convertible Japanese Yen）トークンを借りることができます。

コンバーチブル（Convertible）は、兌換を意味します。兌換できるトークンということです。

兌換できるとは、価値が担保されていることと、交換が容易なことの意味を含ませています。

#### Q,どの暗号資産が担保にできるのか？

初めはETHを担保にできます。

順次主要な暗号資産を担保にできようバージョンアップが計画されています。

#### Q,CJPYは何に使えるのか？

当初のユースケースは多くないことが想定されますが、CJPYは誰でも借りることができ、転送や流通の制限もありません。どのように流通しようとも1CJPYは1円の価値があります。

分散型交換所（DEX）にてCJPYによる交換ペアの流動性プールを設置します。（誰でも自由に行えますが、DeFiGeek Community JAPAN主導で大規模な流動性を確保する計画です。）

これにより、理論上はほぼすべての流通トークンと交換が可能になります。  
また、既存の分散型金融アプリケーションとの連携や提携もコミュニティの拡大と働きかけによって実現していくでしょう。

将来的には国内取引所や暗号資産系金融サービス企業などでCJPYが取り扱われることが想定されます。

あらゆる価値交換の基軸の一つとしてCJPYが役に立つことを願っています。  
また、1CJPY＝1円を担保する仕組み上、蓄財の方法の一つとしてもその価値があると提案できます。

#### Q,CJPYを借りるルールは？

最小の担保率は、担保評価額110％です。

例えば110円分の担保があれば、100円分のJPYCを借りることができます。

借り入れに対して年利の発生は無く、借入時一回きりの手数料制です。

手数料は担保率により変動しますが最大20％～最小0.1％です。（担保率150％で2%、200％で1%、300％で0.4％、500％以上は0.1％となる独自の数式にて計算されます。）

手数料は借りたCJPYから徴収されます。

#### Q,返済のルールは？

返済期限はありません。借りたCJPYは無期限に利用できます。CJPYを返すことで、いつでも担保を引き出すことができます。

また、最小担保率110％以上を維持していれば、余剰担保をいつでも引き出すことができます。

(注：借入操作後72時間は担保の引出ができません。これはプロトコルの悪用を防ぐための設定です。)

#### Q,CJPYを貸してくれているのはDeFiGeek Community JAPANですか？

違います。

DeFiGeek Community JAPAN及びYamato Protocolは、あなたの担保にもCJPYにも一切触れることができません。

あなたはYamato Protocolを通じて、イーサリアムと直接取引を行っています。

Yamato Protocolはイーサリアムと契約を実行するためのアプリケーションです。

人間が一切仲介しないことで不正が起こる余地がなく、プログラムは誰にも止められることなく設定した通りに働きます。

#### Q,担保資産が値下がりし、必要担保が足りなくなったらどうなりますか？

第一に、最小担保率110％以上を維持できるように、CJPYを返済するか担保を積み増すことをおススメします。

最小担保率110％を下回った契約は、誰もが担保資産を時価で買い取り、あなたに代わってCJPYを返済することができます。（つまり、担保資産が時価で売却される可能性があるということです。）

強制的にすべての担保が買い取られるわけではなく、仕組み上いつでも時価売却によるCJPY返済が可能な状態になる、ということです。

これが可能なのは、CJPYを持っているすべてのユーザーと、YamatoCoreという手数料を蓄積している契約です。（YamatoCoreからの担保買取と返済は、誰でもその実行ボタンを押すことができます。実行したユーザーは担保買取量の1%を実行報酬として得ることができます。（実行にはGas代を払う必要があります。））

担保の値下がり状況によっては、すべての担保を売却してもCJPYが返済しきれない場合があるでしょう、

担保を全て売却しCJPYの借金だけが残った場合は、YamatoCore(手数料を蓄積している契約)が、あなたに代わってすべての借金を返済します。（YamatoCoreからの借金代理返済は、誰でもその実行ボタンを押すことができます。実行したユーザーは代理返済額の1%のCJPYを実行報酬として得ることができます。（実行にはGas代を払う必要があります。））

#### Q,CJPYのユースケースを増やすためにどのような営業活動が計画されていますか？

まず第一に日本円ペッグトークンの需要が高まっていくことは間違いないと思います。日本人又は日本の市場の分散型経済が拡大していくからです。（世界的な流れでも。）

集権的なペッグトークンの方が、そういった交渉ごとに早く決着できるという見方もできるかもしれませんが、真実は逆だと見ています。

誰もが自由に同じルールで利用することができ、不正も誤作動も起こらず、ダウンタイムも仲介者もないシステムから発行されるペッグドトークンは、正当なものだと認識されることで、サードパーティの誰もがCJPYを使ってビジネスを起こす又はビジネスに利用することができます。

それはBTCやETHを使うことと同義だからです。

Yamato Protocolはそのためのクラウド機能になります。

営業活動ではなく認知活動によって、その可用性を高めていきたいと考えています。