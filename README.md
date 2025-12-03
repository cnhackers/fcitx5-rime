sudo apt update

sudo apt install fcitx5 fcitx5-rime

修改候选词

sudo nano /usr/share/rime-data/default.yaml

修改 page_size 5 改成9

menu:
  page_size: 9

然后重新部署rime

或直接重启fcitx5

没用就修改这个

/home/kali/.local/share/fcitx5/rime/build/default.yaml 【次要】

~/.local/share/fcitx5/rime/default.yaml【kali路径不对】
