# pico-color-connect

## ピンアサイン

ATTINYのピンは全てスルーホールの出力しています。

![無題](https://user-images.githubusercontent.com/34668037/59551981-643f3b80-8fbc-11e9-9755-6c964767e744.jpg)

## フォトリフレクタ
切り欠きの位置は左下

![KIRIKAKI](https://user-images.githubusercontent.com/34668037/59607886-24f52400-914f-11e9-92d0-baccbc884ad0.png)

フォトリフレクターを実装した場合、センサー出力はPB4に接続されます。
なお、センサーは赤外線受光でLレベル、受光していないときはHi-Zになります。
したがって、フォトリフレクターを使用する場合、内蔵プルアップをONにしてください。

