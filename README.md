環境を構築しよう

事前条件
・Python３.6インストール済み

1.Pythonの仮想環境を作ろう
$ mkdir -p ~/PycharmProjects/practice
$ cd ~/PycharmProjects/practice/
$ python3.6 -m venv venv

2.Pythonの仮想環境を有効にしよう
$ cd ~/PycharmProjects/practice/
$ source venv/bin/activate
(venv)$

3.Djangoをインストールしよう
(venv)$ pip install django

ーインストール確認コマンドー
(venv)$ pip freeze
Django==1.11.3
pytz==2017.2