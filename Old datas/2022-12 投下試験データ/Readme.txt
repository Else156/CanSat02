1．このフォルダの目的
2022年12月10日に実施した投下試験のデータを保管する。

2．投下試験実施日当日の一日
実験について
ガムテープでキャリアを固定し、手で持って投下した。
（キャリアを入れる円筒状のものから投下はできなかった）←その段階に行く前にドアノブにパラシュートが引っかかり破れてしまったため
また、床にマットを引き、引き上げ用のひもをキャリアに付けた

１回目の実験では、小さいパラシュートで6メートル上から投下。
結果はパラシュートによる速度の低下をする前に地面と衝突したため衝撃でssh接続が途切れ、csvファイルが出ない結果となった。
２回目の実験では、パラシュートの大きさを大きくし、再度それ以外の条件は同じ状況で投下した。
結果は１回目と同じものになった。
３回目の実験では、パラシュートの真ん中に穴をあけ、それ以外の条件は２回目と同じで投下した。結果はほぼ２回目と同じものになった。（目視で確認した結果若干落下速度が遅くなった。）
４回目の実験では、高さを13mにし、そこから投下した。結果は、落下位置がずれドアノブにパラシュートが引っかかったため落下の衝撃などは計算できないが、ログはcsvファイルで撮ることができた。

実験結果についての留意点
九軸センサの値を求めるプログラムが間違っていたため、本実験で求めた加速度は参考にならないものになっていると考えられる
プログラムは一応の完成ができたため柏木が動作確認をしている最中（２０２３年１月７日現在）

実験当日の一連の流れの動画
https://photos.app.goo.gl/QNRU6Km4w3YjvVqb8


3．収容データとその説明
全てのファイルはUTF-8でエンコードされている。

＊＊＊ファイル名.拡張子＊＊＊　
投下試験（12月10日）1回目投下.txt　
＊＊＊内容＊＊＊
衝撃によりssh接続が切れたため、ログをコピペして残した。
実験での条件や結果、ログが書いてある
ログの見方→日時、x軸の加速度、y軸の加速度、z軸の加速度

＊＊＊ファイル名.拡張子＊＊＊
投下試験（12月10日）2回目投下.txt
＊＊＊内容＊＊＊
衝撃によりssh接続が切れたため、ログをコピペして残した。
実験での条件や結果、ログが書いてある
ログの見方→日時、x軸の加速度、y軸の加速度、z軸の加速度

＊＊＊ファイル名.拡張子＊＊＊
投下試験（12月10日）3回目投下.txt　　
＊＊＊内容＊＊＊
衝撃によりssh接続が切れたため、ログをコピペして残した。
実験での条件や結果、ログが書いてある
ログの見方→日時、x軸の加速度、y軸の加速度、z軸の加速度

＊＊＊ファイル名.拡張子＊＊＊
投下試験（12月10日）4回目投下.txt
log_20221210_102757.csv
＊＊＊内容＊＊＊
パラシュートでの減速がうまくいったためcsvファイルを保存することができた。
実験についての条件とその結果がテキストファイルに書いてある
csvファイルにはログが入っている
