# akki-environment
各パッケージをサブモジュールとしてまとめた管理用リポジトリ
1. git clone https://github.com/akki-F/akki-environment.git
2. git submodule update --init
3. git submodule foreach git pull

# chatアプリの起動 (https://zenn.dev/akkif/articles/cbb9882d476f01 )
1. dockerでmysqlおよびenvoyの起動
2. java側でprotoファイルから自動生成(akki-proto)
3. java側アプリケーション起動(akki-java-chat)
4. react側でnode_moduleの生成
5. react側でprotoファイルから自動生成
6. react側アプリケーション起動(akki-react-chat)

# auth0連携起動 (https://zenn.dev/akkif/articles/2162fdc1f2e94d )
1. react側アプリケーション起動(react-auth0)
