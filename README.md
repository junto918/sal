# はじめに

趣味の熱帯魚(主にレッドビーシュリンプ)の飼育が全然うまく行かないので,
ラズベリーパイ3を使って、飼育環境ログを取り、IoTでなんとかしようとしています。

ネットで探せば、関連する有益な情報はいくらでもでてくるのですが、勉強がてらGitHubで飼育ログのPythonスクリプトを公開することにしました(恥ずかしながら)。

各スクリプトの簡単な説明
・DS18B20.py
水温取得のためスクリプトです。 [DS18B20][1]の使用を前提としています。
amazonで購入できます。
[1]https://www.amazon.co.jp/gp/product/B01DCY9G0K/ref=as_li_qf_asin_il_tl?ie=UTF8&tag=junto918-22&creative=1211&linkCode=as2&creativeASIN=B01DCY9G0K&linkId=d63da8cc97cbcdef0137f46d14494234

・bme280.py
気温・湿度・気圧の取得のためスクリプトです。 [bme280][1]の使用を前提としています。

[2]https://www.amazon.co.jp/gp/product/B01M98R905/ref=as_li_qf_asin_il_tl?ie=UTF8&tag=junto918-22&creative=1211&linkCode=as2&creativeASIN=B01M98R905&linkId=b019add497ceb26fd588ea69d38708c3