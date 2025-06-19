# strategy
基本的な構築の方針について。

## Port strategy
各サービスにアクセスするためのホストの外に見せるポート番号は下記のように設定する

- gitlab
  - web 10100
  - ssh 10122
- jenkins
  - web 10200
  - ssh 10222
- gcc
  - ssh 10322
- qemu
  - ssh 10422
  - gdbserver 10444 

