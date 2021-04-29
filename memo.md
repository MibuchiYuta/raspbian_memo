# Macからsshできなくなった時の対処法

'''bash

@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

'''
 
 これが出るとき以下のようにする。ip　addrはraspberry pi のもの
 
 '''bash
 ssh-keygen -R "192.168.11.10"
 '''
 
 参考 https://qiita.com/wnoguchi/items/690f3f4651f8f11e4ed3
