# digital-1
ex.text
カメラ画像を取得して表示

ex2.text
カメラ画像を取得して表示するだけでなく、valueというトラックバーを
作成して、それに応じてカメラ画像が変化するプログラム。今回はvalueの値に応じて画像の
色調が低くなるようなコードを書いた。
元の方ではcam1.pyという名称であるため、ターミナルで $ python cam1.pyと入力して実行をする。
pythonのバージョンは
koutoukousei-no-MacBook-Air:~ takayuki$ python --version
Python 3.6.5
である。
cv2.imshow('title',frame-2*v) 
以外のコードは全てサンプルコードと同一である。
以下動画のリンク。https://youtu.be/GTsyVHGkVOU

ex3.text
カメラ画像を取得して表示し、リアルタイムに検出した物体を追尾するといったプログラムである。
前回のプログラムのvalueを使い、周りの環境が暗くてもこのvalueを操作することで物体の追尾を
行いやすくした。
元の方ではcam2.pyという名称であるため、ターミナルで $ python cam2.pyと入力して実行をする。
pythonのバージョンは
koutoukousei-no-MacBook-Air:~ takayuki$ python --version
Python 3.6.6
である。
以下動画のリンク。

