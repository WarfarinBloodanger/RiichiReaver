# RiichiReaver

[PLAY](https://warfarinbloodanger.github.io/RiichiReaver/reaverpro.html).

### これは何？

これは純粋なHTML5+JavaScript+CSSの単一ファイルで作られた麻雀ミニゲームです。

遊び方: 牌河と残り牌山の情報から、6枚の牌の中から放銃しない4枚を選んでください。

レベルは数字が大きいほど難しいわけではなく、連続でクリアしたステージ数を表します。

ブラウザでJavaScriptを有効にしてください。そうしないとゲームが動作しません。

シード値が設定されています。

### 技術について

本当に1つのファイルだけで構成されており、画像リソースやステージデータなどもすべてこのファイルに埋め込まれています。このためHTMLファイルのサイズがMB単位になっています。

こうしたのは、私のような（面倒くさがりの）人間が、ファイルを1つコピーするだけで遊べるようにするためです。

お気に入りのバージョンをローカルに保存すれば、インターネットがなくても遊べます。

ローカルファイルで遊ぶ場合、PCでの利用を推奨しますが、モバイル端末でも問題ありません。iOSではSafari以外のブラウザを使用することをお勧めします。一部のSafariバージョンではローカルのHTMLファイルを開けないようです。

### 意見について

喜んでお聞きします。コードがまだ私の手に負える程度に整理されているうちに（笑）。
ただし私は麻雀に興味がある普通の大学生です（しかも学内で仕事もあります！）。そのため、すべてのメッセージにすぐに対応できるとは限りません。
ステージ内容について

ステージはその場で生成されるのではなく、組み込まれています。公開日（2025年7月29日）時点で約2万のステージが内蔵されています。現在プレイヤー数も多くないので、この数で十分だと思います。

牌譜の考え方が変に思えるのは次の理由によるものです：

-    牌譜は私が開発したAIから取っており、未熟な可能性があります

-    このミニゲームでは場況が十分に反映されておらず、場況に基づく判断が必要なケースがあります（実戦と何切問題の環境の違い）

-    このゲームでは聴牌したら即立直と強制しており、改良を考慮していません。そのためバカみたいな立直があるかもしれません。これは今後改善したいです

このゲームをより豊かにするため、より多くの牌譜を収集したいと考えています。
コードについて

なぜJavaScriptが難読化されているのか：（2025年7月29日現在）一時的に非公開としています。というのも、このコードを使って現在公開できない作業を行う予定があるからです。しかし後で必ず公開しますので、私に忘れないように言ってください。
余談

私が開発しているAIは「北風（Kitakaze）」といいます。科学的な麻雀（牌効率）を非常に重視しています。しかし運が悪いようで、バージョンを2回更新した今でもそうです。

このプロジェクトは北風を開発中に思いつき、少し時間をかけて作った副産物です。予想外に面白かったので公開することにしました。楽しんでいただければ幸いです。

### What is this?

This is a single-file Japanese mahjong mini-game built purely with HTML5+JavaScript+CSS.

How to play: Based on the discard pile and remaining wall tiles information, select 4 tiles out of 6 that won't deal into a winning hand.

Level doesn't indicate difficulty - it just shows how many stages you've cleared consecutively.

Make sure to enable JavaScript in your browser, otherwise the game won't work.

The seed is set.

### Technical Details

It's truly a single file - all image resources and stage data are embedded within this file, which makes the HTML file several MBs in size.

I did this just to make it convenient for lazy people like me - you only need to copy one file to play the game.

You can save any version you like locally and play it offline.

For local files, PC is recommended but mobile works too. For iOS, try using browsers other than Safari as some Safari versions may block local HTML files.

### About Feedback

I'm happy to hear your suggestions while the code is still manageable (lol).
But I'm just an ordinary college student interested in mahjong (and I have work at school too!), so I may not respond to all messages promptly.

### About Stage Content

Stages aren't randomly generated - they're pre-built. As of release date (July 29, 2025), there are about 20,000 built-in stages. With the current player count, this should be sufficient.

If some tile decisions seem strange, it's because:

-    The records come from my AI which might be immature

-    This mini-game doesn't fully reflect real game situations where some decisions are context-dependent (difference between actual play and tile-discard puzzles)

-    The game forces riichi upon tenpai without considering improvement, so some riichi decisions may look dumb. I hope to change this later

I'd love to collect more records to enrich the game.

### About the Code

Why the JavaScript is obfuscated: (As of July 29, 2025) I'm keeping it closed-source temporarily because I need to use this code for some currently confidential work. But I promise to open-source it later - remind me.

### Side Note

The AI I'm developing is called "Kitakaze" (North wind). It strongly emphasizes scientific mahjong (tile efficiency). But it seems to have bad luck, even after two version iterations.

This project was a side product I came up with while developing Kitakaze. Surprisingly fun, so I decided to release it. Hope you enjoy it.
