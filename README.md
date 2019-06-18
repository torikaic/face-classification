# 「少ないデータで転移学習を用いて画像内の表情を分類する」
* 表情（感情）による画像の分類をします。
* [JAFFE][c]（日本人顔データベース）から、「喜び」「平常状態」「怒り」各クラス30枚の画像をデータセットとし、用途別に分割して使用しました。
* DL4US(Deep Learning for All of US) 1期 修了課題（コード部分のみ）

# Env.
* Python 3.5.2
* Jupyter Notebook

# File.
* face-classification.ipynb

# Libraries.
* tensorflow-gpu 1.4.0
* keras 2.1.2
* numpy 1.13.3
* matplotlib 2.1.0
* h5py 2.7.1

# References.
* [人工知能に関する断創録(VGG16のFine-tuningによる17種類の花の分類)][a]
* [Keras(Tensorflow)の学習済みモデルのFine-tuningで少ない画像からごちうさのキャラクターを分類する分類モデルを作成する][b]
* Michael J. Lyons, Shigeru Akemastu, Miyuki Kamachi, Jiro Gyoba.
Coding Facial Expressions with Gabor Wavelets, 3rd IEEE International Conference on Automatic Face and Gesture Recognition, pp. 200-205 (1998).

[a]:http://aidiary.hatenablog.com/entry/20170131/1485864665
[b]:https://qiita.com/kazuki_hayakawa/items/c93a21313ccbd235b82b
[c]:http://www.kasrl.org/jaffe.html


