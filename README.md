基本的には下記を参考にすればC++コードまで実行できると思います．

ファイル提出するとごっちゃになってしまうのでgithubにあげときました．
使用される方はgithubからcloneしてください．

[Python]KerasをTensorFlowから，TensorFlowをc++から叩いて実行速度を上げる
https://qiita.com/yukiB/items/1ea109eceda59b26cd64

Loading a TensorFlow graph with the C++ API
https://medium.com/jim-fleming/loading-a-tensorflow-graph-with-the-c-api-4caaff88463f#.chz3r27xt

githubからcloneしてくるTensorFlowのバージョンは2で動作確認しています．
また，buildファイルに関しては上記のリンクを参考にしてもうまく行かなかったのでbazelの公式ページのドキュメントを参考にすると良いかと思います．

bazel公式ページ
https://bazel.build/
