- 3ブロック目の`path_list1`,`series_list`のみ編集すれば良い.
- 現状`t0p0`,`t0p5`,`t0p-5`,`t0p10`,`t0p-10`の5種類のみ対応している.
  - 種類を増やしたい(角度により変化をつけたい)ならば,以下を編集する必要あり
    - `c1_data_row_min_list`,`c1_data_row_max_list`
    - `c2_data_row_min_list`,`c2_data_row_max_list`
    - `ser`の追加(`Chart1`オプション設定,`Chart2`オプション設定)
- excelファイル保存/画像保存の自動化は`path_list2`,`path_list6`のみ対応
  - 増やしたい場合,ディレクトリ指定を増やすこと