# face_recog_min
- 既成モデルを利用して、可能な限り少ない実装量で顔認証の実現を試みたもの
  - 2019年に某所で機械学習についてお話する機会があり、その際作成したものです。
    - 依存ライブラリが各種API変更の波にのまれてしまった感がありますが、それでも`git`にあげていないとやはり不便なので公開しておきます。
    - Web画像を利用したデモと、ラズパイでカメラを利用するデモを用意しましたが、両対応できるようにしました。
- 特徴抽出のコンセプトについては、`deeplearning.ai`のNg先生の解説が一番わかりやすいのですが、簡単なイメージとして当時作成したスライドから以下を添付します。
![Image](github-images/from_slides.png)
### References
- Youtube: “Stanford University School of Engineering”
  - https://www.youtube.com/channel/UCdKG2JnvPu6mY1NDXYFfN0g
- Youtube: “deeplearning.ai”
  - https://www.youtube.com/channel/UCcIXc5mJsHVYTZR1maL5l9w
- “CS231N”(Stanford Univ.)
  - http://cs231n.github.io/
- Qiita『FaceNetの学習済みモデルを使って、女優の顔画像をクラスタリングしてみた』
  - https://qiita.com/yottyann1221/items/c0b2d2591c3e9ce27c84