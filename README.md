# NLP100knock
https://nlp100.github.io/ja/

模範解答として、[【言語処理100本ノック 2020】Pythonによる解答例まとめ](https://qiita.com/yamaru/items/0cac24710626333bd693#%E3%81%AF%E3%81%98%E3%82%81%E3%81%AB)を用いる

## ch01
05. ngram<br>
模範解答の　**list(zip(*[list[i:] for i in range(n)]))** 賢いな〜<br>
競プロやってそう(小並感)


## ch02
pandasを用いてファイル操作を行う方法が楽そうだと感じたが、それだと出題者の趣旨(UNIXコマンドを用いて欲しい)とズレてしまうと思ったので、両方やりました。<br><br>
14. 先頭からN行を出力<br>
UNIXのheadの行数指定引数(-n ●)に文字を使えないので、input()して行数指定はできなそう？
