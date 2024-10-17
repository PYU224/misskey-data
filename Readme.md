# Misskey「<a href="https://misskey.nukumori-sky.net/">ぬくもりすきー</a>」のルールとマナー

- ここではアングラネタを受け入れていますが犯罪予告はしてはいけません
- 荒らし行為をする者は荒らしとして凍結します
- 今は特に年齢制限を設けず個人の自由と責任を尊重したいので、利用者の皆さんには未成年でも一定の常識と節度を持った大人として振る舞っていただきたいです
- パズルのピース（特定の材料となる情報）を出してしまった方がいても、その方に非が無ければ助言をして見逃してあげてください
- R-18画像を投稿される際は「センシティブとして設定」する設定をしてください<br>
（悲しい事に、現在の日本国の法の問題で修正は必須です・・・）
- あからさまに性的な話題や暴力的な発言をする場合は、できればCW機能でワンクッション置いてから発言するようお願いします
- 当サーバーが関与するサービス等に対し攻撃と判断される負荷をかける行為を禁じます
- 実在する児童のポルノの投稿は絶対ダメですし、AIによって生成した児童のポルノもダメです。
- 海外のサーバを使っている＋CloudFlareの影響で画像添付までに時間がかかる事があります。
- 掲示板とは異なり、MisskeyはFediverseという相互に接続されて見えるサーバー群です。<br>
犯罪実況は論外で（してはいけない）、政治思想を過度に出している発言はチャンネル機能（後述）等で公開範囲を限定するか、「内容を隠す」機能等を使って配慮してください。（基準については後述します）
- Tor等の仕様変更によるせいか、簡単に匿名化ができる<b>Tor Browserが使えなくなりました。<br>
匿名化したまま利用したい方はノーログVPNを使うか、後述の方法でTorプロキシを通して利用してください。</b>
- 他にも色々と追加するかも
<br>

- プラグインとかメモ書きとかは下記に追加予定です<br>
https://github.com/PYU224/misskey-data<br>

- サーバーのテーマ「Tesuya」（コピペで使えます）<br>
[Tesuyaのテーマスクリプト](./ServerTheme"Tesuya".dat)<br>

- Misskeyのチャンネルについての解説<br>
https://whiteblackspace.hatenablog.com/entry/2023/02/28/232319<br>

- Misskeyの基本的な使い方（チャンネルなどの使い方も含む）<br>
https://note.com/spoonail/n/n79b820b7cd95<br>
<br>
色々と制限を付けましたが創作や技術についての話題、特にプログラミング・サーバといった話題については大歓迎です。<br>
<br>

## 「政治思想を過度に出している」とは何か
定義するのは難しい上に情勢によって変化するでしょうが、一応以下と定義します。<br>
- 特定の人物・集団に対して<b>大きな負の感情をぶつける</b>表現<br>
（ネタにするのは一応セーフですが取り扱いには注意してください。後述します。）
- 逆に言えば上記の条件を満たさない、下記のようなもの（事実に基づいた批評、皆の見識を深められるような意見等）は大丈夫です。
<br>
<p>大丈夫であろう例：弁護士バッジを持っている○○○○はその場その場でおだててくれる相手についていくだけで、確固たる信念や思想を持たない風見鶏である。</p>
<br>

- ここのサーバーは色々な文化や背景を持った方々が集う場所で、また他のサーバー（外部）からも発言が見える場所です。<br>
特定のコミュニティでのネタについて、異なる背景を持った方も見ているという事を念頭に入れて発言してください。<br>
<br>
<p>危うい例：「<b>○○で核実験（○○で地震）</b>」、「<b>†安倍晋三†</b>」（スタンプはまだOK）</p>
<br>
故安倍氏だけでなく核実験ネタについても注意を要する表現で、過去にとある方がそのネタを元となったコミュニティとは関係ない場所で出した結果、その場所を追放されたという話があります。<br>
なのでこうした掲示板等を由来とする、不謹慎ネタは大丈夫ではない場合があります。<br>
「内容を隠す」機能やTDN表記とかで<b>クッションを付けて</b>ください。</p>
<br>

### おおよそセーフな感じのコミュニティの例（多分）
- だいぶ溜まってんじゃんアゼルバイジャン - ニコ百<br>
https://dic.nicovideo.jp/id/5531153<br>
<br>

## 匿名化したままTorを使う方法について
Socks5でTorネットワークに接続します。まずは下記のページより「Tor Expert Bundle」をダウンロードして解凍してください。<br>
https://www.torproject.org/download/tor/<br>
<br>
解凍したフォルダより「Tor.exe」を起動してTorネットワークに接続したまま、Torブラウザ以外からのブラウザでプロキシの設定画面に入り、Socks5のプロキシを「<b>127.0.0.1:9050</b>」に設定しましょう。（FireFoxは設定からいけますし、Chromeはプラグイン等を使えば簡単に設定できます）<br>
<br>

## Twitterから初めて来た方々へ
とりあえずツイートは「ノート」から行え、他人のノートにリアクションを付ける事もできます。<br>
「ホーム」ではフォローしている方のTLが見れ、「ローカル」では同じサーバーにいる方々の投稿を見る事ができ、「ソーシャル」や「グローバル」ではフォローしていない他人のノートを見る事ができます。ややこしいですが・・・<br>
あとマークダウン記法が使えますので良かったら活用してみてください。<br>
<br>
- 参考URL<br>
https://misskey-hub.net/docs/features/timeline.html<br>
https://qiita.com/tbpgr/items/989c6badefff69377da7<br>
<br>

## パスワード再発行機能があります
アカウントにメールアドレスを登録すると、万一アカウントのパスワードを忘れた際にパスワードの再発行ができる機能があります。<br>
メールアドレスを登録していないよ！という方は管理者の私にDMをください。パスワードをリセットして再発行します。<br>
<br>

### おすすめプラグイン
各個人のメニュー欄にある「設定」から「プラグイン」でMisskeyの機能を拡張する事ができます。<br>
良さそうなプラグインを下記に紹介していきます。<br>

- ノートの画像ファイル名をランダム化するプラグイン<br>
https://misskey.io/notes/9k8p1owleu<br>
<br>

## 寄付について
サーバの運営や勉強代の為に寄付を常時募集しています<br>
寄付したい方は私にメッセージを送ってくださると幸いです<br>
VプリカやAmazonギフト券を中心に寄付を受け付けております。<br>
（TwitterでもメールでもMisskeyのDMでもたぶん大丈夫ですが、きれいなお金限定です）<br>
PayPayやKyashでも受け付けています<br>
<b>PayPayとKyashのID： pyu224</b><br>
<br>
Pixiv Fanboxの有料プラン契約や、メロンブックスから同人誌やグッズを購入する形でも支援ができます。<br>
https://pyu224.fanbox.cc/<br>
https://www.melonbooks.co.jp/circle/index.php?circle_id=41217<br>
<br>
<b>寄付などでこのサーバーに貢献していただいた方でそれを名乗り出ていただくとその方に専用のロール（役割）を付与したいと思います。<br>
ドライブの容量が多いといった特典がありますのでご検討してくださると嬉しいです。</b><br>
<br>

### 仮想通貨での寄付はこちら
<b>Litecoin： ltc1q48xp7ftvvzqyjdljmfq8kq63k98ck8q98rz558</b><br>
<b>BAT: 0x53686a67285eeD7D6e33C24838B446AD2F0654e6</b><br>
<b>Monero: 839MD2wtRGDW5kaCwTpBMpaDZUji2nvzTX6w4H8P23sLG2H9uqCGSEsiQ6whWFkHhLFAWWXAukapGfM5nq3KornhE3RRYsn</b><br>
<b>Zcash: t1drHvETYxYzLgsFo5Wf2XAX5eUSkemXftT</b><br>
<br>

### 「仕事を依頼する」という形で私を支援したい場合はこちら<br>（もちろん仕事は可能な限り真面目にやります）
https://onaco.jp/profile/PYU224<br>
https://skeb.jp/@PYU224<br>
<br>

### 私のアカウント（質問やサポート等はこちらでお願いします）
https://misskey.nukumori-sky.net/@PYU224<br>
https://twitter.com/PYU224<br>
<br>

### 私のサイトやブログ、自作ゲームの紹介ページ（こちらでも質問やサポート等のコメントがあればできるだけ対応します）
https://33-4.me/<br>
https://33-4.me/blog/<br>
https://w.atwiki.jp/vahren_ency/pages/1006.html<br>
<br>

## このサーバーをホストしているサーバマシンについて
このサーバーほホストしているVPS（仮想サーバ）はモルドバ共和国🇲🇩にある、某ホスティング会社のものを利用しています。<br>
理由は比較的安価で規約が緩くて性能の良いサーバをレンタルでき、VPSのレンタルを通じて真面目で勤勉な彼らの支援がしたいからです。

### 維持費について
<p>2023年11月14日時点でのおおよその数値です。色々な方々の参考になると幸いです。</p>
<p>
Kindworld（閉鎖済み）の場合<br>
- Misskey本体とデータベース担当のVPS代： <b>約20ドル/月</b><br>
- メディア保管担当のオブジェクトストレージ代： <b>約12ドル/月</b><br>
- 匿名ドメイン会社からのドメイン代： <b>約30ユーロ/年</b>
</p>
<p>
ぬくもりすきーの場合<br>
- Misskey本体とデータベース担当のVPS代： <b>約20ドル/月</b><br>
- メディア保管担当のオブジェクトストレージ代： <b>10GB/月まで無料</b><br>
- 匿名ドメイン会社からのドメイン代： <b>約15ユーロ/年</b>
</p>
<br>

## 参加・協力しているプロジェクト</h1>
- ぜろちゃんねるプラスの再開発プロジェクト等<b>（EXぜろちゃんねる（ex0ch））</b><br>
https://github.com/PrefKarafuto/ex0ch<br>
- Tor Project<br>
https://www.torproject.org<br>
<br>

## 参考と勉強にさせていただいているコミュニティや掲示板など
- 恒心綜合大学医学部付属病院掲示板<br>
https://jbbs.shitaraba.net/study/12712/<br>

- アングラツクスレ板<br>
https://jbbs.shitaraba.net/game/59519/<br>

- ヴァーレントゥーガ避難所<br>
https://jbbs.shitaraba.net/computer/42292/<br>
<br>

## 出入り禁止ユーザー
当サーバーの規約が守れない等の理由で、こちらではどうしても受け入れられなかったユーザーリストです。<br>
[受け入れないユーザーリスト（banned-user.md）](./banned-user.md)
