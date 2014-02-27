Mojolicious::Lite + WebSocket でチャット
===================

## 使い方
1. git clone https://github.com/ymko/mojo-websocket-chat.git
2. carton install
3. サーバーのIPアドレス変更
	--- app.pl ---
	- my $addr = "192.168.1.10:8080";
	+ my $addr = "サーバーIP:サーバーport";
4. carton exec -- morbo -l http://*:8080 app.pl

enjoy!

## 参考
* [Perl - CentOS6.4上でMojolicious+WebSocket+SSL環境構築 - Qiita](http://qiita.com/nkns165/items/6605c0bc192f2f94eb45)
* [Mojolicious::Lite で WebSocket を使ったチャットを作る(現時点：2012年3月10日で動くコード) - 僕の車輪の再発明](http://kazuph.hateblo.jp/entry/20120310/1331396492)


