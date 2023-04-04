# Tmux-tutorial
## tmux ：终端复用器，可以一直打开某一些终端

现实当前后台正在运行的终端：tmux ls

进入名为name的终端：tmux attach -t name

退出打开的终端（该操作不会导致终端关闭）：先按ctrl + B再按D

删除并终止终端（此操作会删除终端并终止终端内正在运行的进程）：tmux kill-session -t 0

## tmux使用快捷键:

左右分屏：Ctrl + b, % (分割当前窗口)

上下分屏：Ctrl + b, " (分割当前窗口)

关闭分屏：Ctrl + b, x (关闭所在分屏窗口)

显示分屏编号：Ctrl + b, q (显示分屏编号)

分屏切换：Ctrl + b, 方向键(基本可以自由切换)

ctrl ＋ｂ，松开，然后再按 [ 键进入翻屏模式后，PgUp PgDn 实现上下翻页， q退出翻屏模式
