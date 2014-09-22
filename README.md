IBus
====

Linux 输入法<br/>
    apt-get install ibus ibus-clutter ibus-gtk ibus-gtk3 ibus-qt4
    im-switch -s ibus
重新启动Computer
    apt-get install ibus-pinyin
    ibus-setup
在输入法选项卡中添加 Chinese-pinyin
添加开机启动项 system->preferences->Startup Applications-Add
    Name: IBus daemon
    Command: /usr/bin/ibus-daemon -d
    Comment: start IBus daemon when Gnome starts
