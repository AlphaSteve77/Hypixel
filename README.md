Hypixelのギルドのためのソースです。
指定のEXP以上のプレイヤーをカウントします。
1分間に120までのリクエストしか送れないので時間がかかる場合もあります。ご了承ください。

<各batファイルの効果>
カウント開始.bat
	GEXPを指定以上超えている人をカウントし保存します。

設定変更.bat
	セーブ設定を変更します。
	[APIKEY]
	[ギルド名]
	[必要GEXP]
	の3種類を変更可能です。

スコアを減点する.bat
	mcidで指定した人のスコアを減点させることができます。

アップロード.bat
	アップロード用です。減点直後は反映されません。次のカウント実施時に反映されます。

uuidmcid.json
	これを見てmcidに対応するuuidを見ることができます。
	Ctrl+Fを使うと効果的に検索可能です。

score.json
	スコアが保存されます。

設定.json	
	設定が保存されます。

version 3.00
Coming Soon...

version 2.00
追加機能
セーブ機能を追加しました。
スコアを減点できるようになりました。
	MCIDで指定する必要があります。
	そのため, 紐付けられたMCIDを検索することができる機能を追加しました。

削除機能
矛盾点であるテキストを削除しました。

version 1.00
GEXPを指定以上いる人をカウントできるようになりました。

