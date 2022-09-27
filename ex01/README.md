# 第 1 回

## サザエさんクイズ(ex01/quiz.py)

### 遊び方

- コマンドライン上で quiz.py を実行すると、ターミナル上で問題が出力される。
- ターミナル上で解答を入力する。
- 正解だと「正解！」、不正解だと「不正解！」が表示される。
- 最後に、所要時間が表示される。
- 正解、不正解に関わらず出題は 1 回。

### プログラム内の解説

- main 関数: クイズプログラムの全体の流れを実行。
- syutudai 関数: ランダムに問題を出力、kaito 関数に正解を渡す。
- kaito 関数: 回答と正解をチェックし、結果を出力する。