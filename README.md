# Fix_Sogou

    Ubuntu 14.04 最近搜狗输入法频繁崩溃，重装无效
    在Linux系统下解决搜狗输入法 (基于fcitx) 的选字栏失效、白框、崩溃的问题。
--------------------
    cd ~/.config
    sudo rm -r SogouPY
    sudo rm -r SogouPY.users
    sudo rm -r sogou-qimpanel
    killall fcitx
    killall sogou
    fcitx restart
    sogou-pimpanel
---------------------
执行 `bash ./fix_sogou.sh `
