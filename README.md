# ChlorinePrediction

残留塩素濃度予測モデルに使用します．

## 使い方
### LSTM.ipynb
LSTMモデルを学習するコードです。

wtp_in：目的変数1　送水地点の残留塩素濃度

wtp_out：目的変数2　受水地点の残留塩素濃度

time_steps：ブロック

future：予測時間

df1：学習データのcsv

df2：検証データのcsv

df3：テストデータのcsv


### hakohige.ipynb
箱ひげ図を使用して、異常値を削除します。
