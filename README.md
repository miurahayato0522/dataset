# dataset
学習用に作成したデータセット
bboxラベリングにはlabelImgを使用(https://github.com/HumanSignal/labelImg)

book_detection : yolo物体検出用に作成した本の背表紙データセット
    bbox情報はxml形式

japanese_coin_detection : yolo物体で検出用に作成した、日本硬貨のデータセット
    bbox情報はtxt形式

voice_actor_pic : 女性声優の顔画像データ
    スクレイピングで収集後、顔領域をopencvで切り取り、64*64にリサイズしたもの。
    詳細 : https://qiita.com/paru0806/items/a567c87cb470879cea1a