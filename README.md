# AIST_PNP 
神山・鈴木(産総研)作のコードをベースに一部変更したものである。

This is a partial modification based on the code written by Kamiyama and Suzuki (AIST).

# 使い方　How to use
事前に用意するべきデータ

Data to be prepared in advance

1. dat_fileディレクトリの中に、
　　Unity上で作成した「1_26_img_4044_real2model_y.dat」ファイルが入ってる。
   このdatdファイルは、real画像と対応するmodel画像のワールド座標情報が入っている。
   
   Contains the "1_26_img_4044_real2model_y.dat" file created on Unity.
   This datt file contains the world coordinate information of the model image that corresponds to the real image.

2. img_4044.csv ようなcsvファイルを用意する。
   img_4044.csvはreal画像とmodel画像間の対応点座標が入ってる。

   Prepare a csv file like img_4044.csv.
   img_4044.csv contains the coordinates of the corresponding points between the real image and the model image.
   
  
Jupyter notebookで上記のデータを用意すれば、
fnameのpathをdatファイルに指定して、pnp.ipynbコードが実行できると思います。

If you prepare the above data with Jupyter notebook,
I think you can execute the pnp.ipynb code  by specifying the path of fname in the dat file.
