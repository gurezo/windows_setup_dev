## nodist set up

![nodist](image/nodist/nodist-00.png)

### steps
- [nodist](https://github.com/marcelklehr/nodist)のページを開きます。
- 本サイト内にあるWindows用インストーラーの[リンク](https://github.com/nullivex/nodist/releases)をクリックし、ダウンロードします。
    ![nodist](image/nodist/nodist-01.png)

- インストール前のnodist，nodeの状態
    ```
    $ nodist -v
    $ node -v
    ```
    ![nodist](image/nodist/nodist-09.png)
- インストーラーで、Nodistをインストールします。  
    ![nodist](image/nodist/nodist-02.png)
- ライセンスに同意する  
    ![nodist](image/nodist/nodist-03.png)
- デフォルトのまま　特に指定なし  
    ![nodist](image/nodist/nodist-04.png)
- デフォルトのまま　特に指定なし  
    ![nodist](image/nodist/nodist-05.png)
- インストール開始  
    ![nodist](image/nodist/nodist-06.png)
- インストール完了  
    ![nodist](image/nodist/nodist-07.png)
- nodist -vでバージョンが表示されれば、OKです。
    ```
    $ nodist -v
    ```
    ![nodist](image/nodist/nodist-08.png)
- node は、まだ環境構築されていない
    ```
    $ node -v
    ```
    ![nodist](image/nodist/nodist-10.png)
- nodist + v0.12.2を行い、v0.12.2をダウンロードします。
    ```
    $ nodist + v0.12.2
    ```
    ![nodist](image/nodist/nodist-11.png)
- 上記手順後でもnode は、まだバージョン表示されない
    ```
    $ node -v
    ```
    ![nodist](image/nodist/nodist-12.png)
- nodist 0.12.2でバージョン指定を行います。
    ```
    $ nodist 0.12.2
    ```
    ![nodist](image/nodist/nodist-13.png)
- node -vでバージョンが表示されれば、OKです。
    ```
    $ node -v
    ```
    ![nodist](image/nodist/nodist-14.png)
