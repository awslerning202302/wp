Docker学習用のymlファイルです。
Wordpress及びmariadbのコンテナを起動します。

環境変数にdbの認証情報が設定されていますので、利用する際は任意の情報に変更することを推奨します。
なお、以下の設定値はそれぞれ同一の値を設定してください。
MYSQL_DATABASE = WORDPRESS_DB_NAME      #データベース名
MYSQL_USER = WORDPRESS_DB_USER          #アカウント名
MYSQL_PASSWORD = WORDPRESS_DB_PASSWORD  #パスワード
