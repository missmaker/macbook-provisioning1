# macbook-provisioning
Mac環境構築自動化

・自動化の準備
開発環境の構築を自動化するための準備を行います。

> Xcodeのインストール
以下のコマンドを実行して、Xcodeをインストールします。
$ sudo xcodebuild -license

> Homebrewのインストール
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

・Ansibleのインストール
$ brew update
$ brew install ansible

・プロビジョニング実行
$ ansible-playbook -i hosts -vv localhost.yml

・実行内容を変更するときはlocalhost.ymlをいじる

・参考資料
Mac の開発環境構築を自動化する (2015 年初旬編)
http://t-wada.hatenablog.jp/entry/mac-provisioning-by-ansible
HomebrewとAnsibleでMacの開発環境構築を自動化する
http://mawatari.jp/archives/mac-provisioning-by-homebrew-and-ansible
・キーワード
Ansible
mac環境構築自動化

