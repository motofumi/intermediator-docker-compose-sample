# intermediator-docker-compose-sample
Author: Motofumi Iijima  
docker-compose.ymlは、INTER-Mediatorフレークワークを運用する為、複数のコンテナを定義して実行します。


## 前提条件


## 手順
###手順1 (docker-compose実行前)
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

1. INTER-Mediator/INTER-Mediatorリポジトリをフォークする。

    参考: [GitHub Docs - リポジトリをフォークする](https://docs.github.com/ja/github/getting-started-with-github/fork-a-repo)
    


### 手順2 (docker-composeの実行)



### 手順3 (docker-compose実行後)

1. 自分のGithub名/INTER-Mediatorをクローンする。

    ```
    $ hoge
    ```

1. 必要に応じてサンプルデータを変更する

    ```
    $ mysql/init/sample_schema_mysql.sql
    $ postgres/init/sample_schema_pgsql.sql
    ```

1. INTER-Mediatorのparams.phpを下記のように変更する。

    ```
    $ hoge
    ```

1. hoge

    ```
    $ hoge
    ```










