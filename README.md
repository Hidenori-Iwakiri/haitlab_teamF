# haitlab_teamF
HAIT Lab東京3期, チームFのリポジトリです.


※バグが多数あったので, 修正を行いました。**2020/4/1 19:00**以前にこのリポジトリを利用した方は、再度```git clone```してください。

私たちは, 大手うどんチェーンのメニュー判別を行うプロダクトを開発しました. (開発期間: 2週間, 開発メンバー: 4人) 

・課題の背景
以前大手うどんチェーン店を訪れたとき, レジの店員がお客さんが注文した天ぷらの種類を区別するのに苦戦し, 時には間違えそうになっていたのを見て, この作業を自動化できればいいのに, と思った.
また、昼時お客さんが殺到すると, どうしてもレジがボトルネックになってしまうので, レジ作業を自動化し、高速化することで, お店の回転率も上がるのでは, と考えた.

・プロダクト概要
お盆に載せられた商品の画像を読み込み, どの商品が注文されたかを識別.
そこから注文された商品名と精算額を割り出し, 表示する.

商品は,
うどん: 6種類
天ぷら: 3種類
の計9種類. 物体認識のアルゴリズムとしてはYOLO(v3)を利用.
