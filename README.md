# intermediator-docker-compose-sample
Author: Motofumi Iijima  
docker-compose.ymlは、INTER-Mediatorフレークワークを運用する為、複数のコンテナを定義して実行します。


## 前提条件


## 手順
1. 作業ディレクトリを作成します。    

    ```
    $ mkdir ~/docker && cd ~/docker
    ```

1. intermediator-docker-compose-sampleリポジトリをクローンする。

    ```
    $ git clone https://github.com/motofumi/intermediator-docker-compose-sample
    ```

1. 次のコマンドの『あたらしいパスワード』をパスワードに置き換えて、MariaDBのルートパスワードを変更する。

    ```
    $ sed -e "s/change_mariadb_password/新しいパスワード/" docker-compose.yml
    ```

1. 次のコマンドの『あたらしいパスワード』をパスワードに置き換えて、PostgreSQLのルートパスワードを変更する。

    ```
    $ sed -e "s/change_postgres_password/新しいパスワード/" docker-compose.yml
    ```











