# これは何

プログラミング言語処理系が好きな人の集まり(slack)向けのポータルサイト



# ローカルで開発する

```
git checkout dev
pip install mkdocs mkdocs-material
mkdocs serve
```

# devブランチとmasterブランチ

現在，devブランチにpushするとGitHub Actionsが勝手に``mkdocs build``などを自動で実行してできあがったもの(静的サイト)をmasterブランチへpushするようになっています．