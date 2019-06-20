# blogdown-site

## インストール

1. Rを入れる
2. Rstudioを入れる
3. Rstudio上で以下のコマンドを打つ

    ```r
    install.packages("blogdown")
    blogdown::install_hugo()
    ```

4. git bashを入れる
5. git bash上で以下のコマンドを打つ（プロジェクトを作るディレクトリ※にて）

    ```git
    git clone https://github.com/tpt-ochanomizu/blogdown-site.git
    ```

6. Rstudioの右上のbuttomをクリックしてOpen Projectをクリック
7. ※のディレクトリを選択
8. Rstudioにて以下のコマンドを入力

    ```r
    blogdown:::serve_site()
    ```

特に設定のしていないRstudioならば右下にT/Tのwebsiteのプレビューが表示されたはずである。
ビューのヘッダーにある４つのアイコンのうち左から３つ目をクリック→ブラウザでT/Tのwebsiteが確認できます。

## 使い方

blogdownのDoc参照
