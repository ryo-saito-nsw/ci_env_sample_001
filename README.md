# ci_env_sample_001
WSL上でDockerを使って、CI環境を構築するために必要そうなことをサンプルとして作ってみる

## 事前準備
dockerがインストールされた環境が前提となるため、WSL上のubuntuの中で、下記を実行して、dockerをインストールしておくこと。

    sudo apt install docker-ce
    sudo apt install docker-compose

githubからファイルをダウンロードするときのためにwgetを使うならば下記も。

    sudo apt install wget
    sudo apt install unzip

## サーバの起動方法
プロジェクトをダウンロードする

    > wget https://github.com/ryo-saito-nsw/ci_env_sample_001/archive/refs/tags/v1.0.0.zip

解凍してci_workshopフォルダの中でdocker_composeを実行する

    > unzip v1.0.0.zip
    > cd ci_env_sample_001-1.0.0/ci_workshop
    > ls
    docker-compose.yaml
    > sudo docker-compose up -d


## サーバの停止方法
docker-composeを使って停止する

    sudo docker-compose down

