# program-to-divide-31-syllable-Japanese-poem.
和歌を５７５７７に区分けし、句切れを見つけます。

前半のコードで５７５７７への区分けを行っております。結果として７割ほどの精度となりました。

後半のコードでは和歌の句切れを文法的規則 [1]によって求め、人力による評価[2]と比較しました。
古今和歌集、新古今和歌集ともに高い相関（相関係数にして約０．９）となる高い相関を示すことができました。


和歌のデータは以下のオープンソースから取得
データベースの作成者である勢田勝郭氏にこの場をお借りして感謝を申し上げます。
https://www.nichibun.ac.jp/ja/db/category/waka/
（百人一首のデータはhttp://linkdata.org/work/rdf1s5297i　さんから
こちらもこの場をお借りして感謝を申し上げます）
参考文献
[1]浅岡純朗「和歌の句切れに関する一考察-新しい認定基準私案の構想-」(二松学舎大学人
文論叢,vol.78,2007) pp.113-pp.122
[2]紙宏行「新古今における三句切れの表現構造」（研究紀要 vol.29、1985）
