# scratch-hmc
スクラッチでハミルトニアンモンテカルロ法

# memo 実装すべき事項


1. ハミルトニアンの定義
2. リープフロッグ法の実装
   - 運動量の0.5単位分の更新
   - 位置の1単位分の更新
   - 運動量の1単位分の更新
3. 標準正規乱数の準備
    -N(0,1)
4. 実際の例の準備
  - ここら辺でいいんじゃない
        http://rstudio-pubs-static.s3.amazonaws.com/14127_efa1253766424ab2ac71d9c34ebcbc41.html
5. 受容を決める関数の準備
    - min(1, 前のハミルトン - 提案あミルトン)　==> 理論上は1
6. 初期パラメータを保持するクラスの実装
    - バーンイン期間, リープフロッグ回数L, 繰り返し回数T,学習係数的なε


仮想環境でjupyter notebookを使用する

http://starpentagon.net/analytics/conda_env_jupyter_notebook/　参照。