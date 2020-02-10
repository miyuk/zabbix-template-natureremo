# zabbix-template-natureremo

Nature Remoのセンサーデータを5分毎に取得してグラフ化するテンプレートです。

`Zabbix HTTP Agentを利用するため、Zabbix4.0以上が必要です`

マクロは下記の通り指定してください。
|Key|Value|
|---|----|
|{$ACCESS_TOKEN}|<"http://swagger.nature.global/"より取得したアクセストークン>|
|{$TARGET_DEVICE}|<取得したいデバイスID(取得したAPIの各機器idを記載)>|

Nature Remo Miniでも利用できますが、そちらは温度しか取得できませんのでご注意ください。
