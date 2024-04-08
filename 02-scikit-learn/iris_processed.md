iris_processed.csvファイルについて
==================================

「あやめ」の演習用データセット
------------------------------

このデータセットは、[UC Irvine Machine Learning Repositoryにある「あやめ」のデータセット](https://archive.ics.uci.edu/dataset/53/iris)を加工して作成したものです。

### 元のデータセット

* 制作者：R. A. Fisher
* タイトル：The use of multiple measurements in taxonomic problems, Annual Eugenics, 7, Part II, 179-188.
* 公開年： 1936（UCI Machine Learning Repositoryに提出されたのは1988年6月30日）
* URL： <https://doi.org/10.24432/C56C76>

詳しくは「[Iris Dataset：あやめ（花びら／がく片の長さと幅の4項目）の表形式データセット：AI・機械学習のデータセット辞典 - ＠IT](https://atmarkit.itmedia.co.jp/ait/articles/2206/13/news032.html)」を参照してください。

### 加工内容

* 3行2列目（［Sepal Width］列）のデータを欠損させました（削除前の内容：`4.7, 3.2. 1.3, 0.2, setosa`の`3.2`）
* 全ての列名を独自に書き直しました（`Sepal Length, Sepal Width, Petal Length, Petal Width, Class`）
* ［Class］列の全内容から「Iris-」という接頭辞を削除しました（例：`Iris-setosa`→`setosa`）

### 加工日

2024-03-22

### ライセンス

このデータセットは、[CC BY 4.0（Creative Commons Attribution 4.0 International）ライセンス](https://creativecommons.org/licenses/by/4.0/legalcode.ja)のもとで配布されています。

### 元のデータセットへのリンク

<https://doi.org/10.24432/C56C76>
