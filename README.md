向後研究室が一般公開している Web 教材で統計学を学びつつ、Python の分析関連ライブラリを学習する

http://kogolab.chillout.jp/elearn/index.html

このリポジトリでは教材の内容を実装した Jupyter Notebook を管理する

# 動作環境について

2019/05/03 時点で最新の anaconda（anaconda3-2019.03）を利用している。

## セットアップ手順

* OS : macOS 10.14
* python バージョン管理 : pyenv
* python パッケージ管理 : pipenv

```
$ brew install pyenv pipenv
$ pyenv install anaconda3-2019.03
$ pipenv --python=$HOME/.pyenv/versions/anaconda3-2019.03/bin/python --site-packages
$ echo 'layout_pipenv
PATH=$PATH:$HOME/.pyenv/versions/anaconda3-2019.03/bin' > .envrc
$ direnv allow
```

## Jupyter Lab の起動

```
$ jupyter lab
```

Jupyter Lab が起動すると自動でブラウザで Jupyter Lab が開かれる
