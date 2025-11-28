sudo apt update

sudo apt install fcitx5 fcitx5-rime

修改候选词

nano /usr/share/rime-data/default.yaml

修改 page_size 5 改成9

menu:
  page_size: 9

然后重新部署rime

或直接重启fcitx5
