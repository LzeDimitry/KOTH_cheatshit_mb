1. watch -n 1 w - говрить які де хто юзер
    приклад:
    user@user ~ whatch -n 1 w
    15:52:45 up 3:54, 1 user, load average: 1.38, 1.55, 1.46
    USER TTY LOGIN@ IDLE JCPU PCPU WHAT
    ras tty1 11:58 3:54m 0.06s ? systemctl --user start --wait wayland-session-enve
    whatch - функція лінукс
    -n - це операція в команді watch
    w - показує хто який користувач

2.

pkill -9 -u <username> - нахуй противників кікнути

1.

акриття сесій за TTY / PTS:
Переглянь w, знайди псевдотермінал суперника (наприклад, pts/2) і прибий його:

Bash
fuser -k /dev/pts/2 (тут хз це gemini дав)

1.

systemctl stop <service> якщо прапор не залежить від теяких демонів то виключиті їх нахуй.

1. hot-patching

chmod 000 /var/www/html/vulnerable_script.php
