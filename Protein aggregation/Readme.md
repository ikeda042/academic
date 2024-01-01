# 論文情報
## タイトル
Localization of protein aggregation in Escherichia coli is governed by diffusion and nucleoid macromolecular crowding effect
## 著者
Anne-Sophie Coquel et.al (2013)
## リンク
https://pubmed.ncbi.nlm.nih.gov/23633942/

# 概要
ミスフォールドされたタンパク質による凝集体形成は、細胞のage-related diseasesの原因となる特徴である。先行研究によると、老化が進んだ細胞はold poleにタンパク質凝集を形成することがわかっている。この研究では、E.coliの一細胞モデリング（？）、蛍光顕微鏡タイムラプス、自動画像解析系を使用して、寿命に関係のあるタンパク質凝集の局在が拡散的(Diffusive, Brownian)であることを発見した。また、タンパク質凝集を1つの粒子とみなしてそれらを追跡したところ、タンパク質凝集の平均サイズと拡散係数（Stokes-Einstein lawに関する）を計算することができた。結果から、タンパク質凝集はどうやらpassivelyに局在することがわかったが、この原因として、細胞内のnucleoid-freeな領域が関係あることがわかった。（特にPole領域）
これを踏まえて、拡散、凝集、核様体による凝集の移動の障害の3つのパラメータで凝集局在をシミュレートした結果、aging-relatedなタンパク質凝集の局在（特にPole領域）は核様体の位置とブラウン運動によって制御されているという仮説を証明できた。

# 新規性
タンパク質凝集の局在の原因はcontroversialであったが、アブストの3つのパラメータによって計算機的にシミュレーションを行い、それらが決定的な因子であることを証明した。

# メモ
凝集検出方法は自分の研究でのタンパク質凝集形成を検出する熱ショックタンパク質Ibpaを用いている。ただし、GFPではなくYFPを使用している。
ツールについて、この研究用にチームが自前で開発した。
画像解析では局在の追跡のため、局在の軌跡をトラッキングした。
タンパク質凝集局在情報を定量化する方法がfigに載っていたため、これが自分の研究に使えそう。
共焦点レーザー顕微鏡による3Dイメージの組みたて。

## 新出単語
```
hallmark→trait
pave→cover up
diffusive→拡散しやすい
confine→制限する
displacement→移動
hindrance→障害物
```
