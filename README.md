# nginxSetupTutorial

1. ec2インスタンスを作成（インターネットからの HTTPs トラフィックを許可する/インターネットからの HTTP トラフィックを許可する）この二つにチェックを入れる
2. sshで接続
3. sudo bash
4. amazon-linux-extras install -y nginx1.12 // インストールしてる
5. sudo systemctl start nginx　// 起動するようにコマンド（命令）
6. sudo systemctl enable nginx // インスタンスが起動するとnginxも自動的に起動するように設定するようにコマンド(命令)
7. インスタンスを再起動
8. パブリックIPをブラウザのアドレスバーに打ち込み、nginxが起動していることを確認する
