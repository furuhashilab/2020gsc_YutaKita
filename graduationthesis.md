# ２０２０年度　卒業論文/ゼミ論文
## 東京都渋谷区の公衆トイレに関する調査


２０２０年２月１日

青山学院大学 地球社会共生学部 地球社会共生学科

木多 祐太/Yuta Kita

学生番号 1A116180

指導教員　古橋 大地 教授

© Furuhashi Laboratory/Yuta Kita, CC BY 4.0

# 全体構成(IMRAD形式)

## 序論:
What are you studying and why? 何を研究したのか？ 何故それを研究したのか？(500文字以内で簡単に記述する)

　現状として、渋谷区が一般公開しているオープンデータがあるが、公衆トイレに関するCSVファイルには抜けている部分が多い事に気がついた。現在、渋谷区では17箇所に新たな公衆トイレを建設する「THE TOKYO TOILET」というプロジェクトを行っている。このプロジェクトは、渋谷区と日本財団が協力をし、性別、年齢、障害を問わず、誰もが快適に使用できる公共トイレを設置するというものである。そのため、このプロジェクトをより有効に活用するために、渋谷区の公衆トイレに関するデータを集め、足りないデータを補完したCSVファイルを作成し、それを地図化するという研究を行った。

## 研究方法:
What did you do? 具体的には何をしたのか？
　まずは、渋谷区が公開している公衆トイレのCSVファイルをダウンロードし、どのデータが足りていないのかを確認していった。その結果、渋谷区が公開しているオープンデータには位置情報や多目的トイレの有無といったデータは記載されていたが、段差やオストメイト設備は備えられているのかなどの情報は不足していたため、それらの不足データを実際に渋谷区内にある82箇所の公衆トイレを周り、データを集めていった。また、国土交通省が平成28年に行った、日常でよく利用するトイレに関するアンケート調査では、公衆トイレに対する不満第３位に「トイレ内やトイレ周辺の環境により、安心して利用できない」という意見が挙げられたため、公衆トイレ周辺にどれ程の人がいるのかという情報も、定性的ではあるが、多・中・少の三段階に分けて記載していった。
 　実際に公衆トイレを回る前に、渋谷区が公開しているCSVファイルの中から位置情報だけを取り出し、そのデータを地図に落とし込むことで効率に公衆トイレを回るためのルートを作成した。また、コロナ禍及び、緊急事態宣言下での屋外調査となるため、人との接触をなるべく避ける必要があるため、調査時間は午後11時から午前6時までの深夜のみとし、移動手段も目的地周辺までは車を使用し、その先は徒歩とすることで人との接触をなるべく減らして調査を行った。
　そして全82箇所を回って集めたデータを、渋谷区が公開していたCSVファイルに補完し、渋谷区公衆トイレデータの改良版を作成した。
 https://docs.google.com/spreadsheets/d/1uAAhvEPcMdVw_hDVX1hvDGTixkBHfhDWoXfLwtvKAOg/edit?usp=sharing
 <img width="1380" alt="トイレデータ" src="https://user-images.githubusercontent.com/62396370/105613882-bbe49080-5e08-11eb-98de-c849c6031bf7.png">
 
 次にそのファイルをuMapとGoogleマップに落とし込んでいった。

<img width="500" alt="スクリーンショット 2021-01-24 6 00 45" src="https://user-images.githubusercontent.com/62396370/105614013-a6bc3180-5e09-11eb-9a61-9b940f1860b9.png"><img width="500" alt="スクリーンショット 2021-01-24 5 59 56" src="https://user-images.githubusercontent.com/62396370/105614060-18947b00-5e0a-11eb-8f58-9ac89f785727.png">
uMap=<iframe width="100%" height="300px" frameborder="0" allowfullscreen src="//umap.openstreetmap.fr/ja/map/120-ver2_550586?scaleControl=false&miniMap=false&scrollWheelZoom=false&zoomControl=true&allowEdit=false&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=undefined&captionBar=false"></iframe><p><a href="//umap.openstreetmap.fr/ja/map/120-ver2_550586">フルスクリーン表示</a></p>
Googleマップ=<iframe src="https://www.google.com/maps/d/u/1/embed?mid=17mLCI1Uou2l6ZBaFHTB7wwoUdHOCuUWY" width="640" height="480"></iframe>

 また、オストメイト設備がある公衆トイレ、車椅子で利用することが可能な公衆トイレのレイヤーも作成し、それぞれの利用者が必要とする公衆トイレをすぐに見つけることが出来る地図を作成した。最後に、今回収集したデータを元に、オープンストリートマップと、Wheelmapにもこれらの情報を追加した。

## 研究結果:
What did you find? 何がわかったのか? 
 今回データを収集して分かった事は、車椅子利用者やオストメイトの方にとって、使用できるトイレが近くにあるという状況は普通ではないということだ。渋谷区は「ダイバーシティとインクルージョン」という考え方を大切にしており、人種、性別、年齢、障害を超えて全ての人が住みやすい街という目標を掲げている。しかしそんな渋谷区でも、多目的トイレがあるのは82箇所中３６箇所、オストメイト設備があるトイレに至っては、82箇所中14箇所と、かなり少ないことが判明した。
## 考察:
What do your findings mean? あなたが見つけたことは何を意味するのか？どんな議論をしたか。

## まとめ:
What have you learned from the study? この研究を通じて得られたものは？次に引き継ぐべき課題は？

## 参考文献:
卒業論文本文中に記載。




卒論本文
https://github.com/furuhashilab/2020gsc_YutaKita/blob/master/graduationthesis.md

レポジトリ
https://github.com/furuhashilab/sotsuron2020/projects/16


