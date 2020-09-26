#  初期設定

日本語設定
sudo apt install language-pack-ja
sudo update-locale LANG=ja_JP

#Macからsshできなくなった時の対処法

@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
  https://qiita.com/wnoguchi/items/690f3f4651f8f11e4ed3

  ssh-keygen -R "192.168.11.10" のようにする
