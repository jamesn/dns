---
copyright:
  years: 1994, 2017
lastupdated: "2017-10-12"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# リバース DNS について

リバース DNS とは、ドメイン・ネーム・システム (DNS) がドメイン・ネームを関連する IP アドレスに解決するのと同様に、IP アドレスをドメイン・ネームに解決するための方式です。リバース DNS の応用の 1 つに、スパム・フィルターがあります。スパム送信者は通常、ドメイン・ネームに一致しない、無効な IP アドレスを使用します。リバース DNS 参照プログラムは、着信メッセージの IP アドレスを DNS データベースに入力します。IP アドレスに一致する有効な名前が見つからない場合、サーバーはメッセージをブロックします。リバース DNS は、ネットワーク・トラブルシューティング呼び出し (`ping`など) やネットワーク・モニター・ツールなどにも使用されます。
