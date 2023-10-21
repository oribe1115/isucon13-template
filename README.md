# ISUCON12 Template

ISUCON12用リポジトリテンプレート

`/home/isucon`に展開する前提

```bash
task -g --list # Taskfile.yamlにある使えるコマンド一覧
task -g {コマンド} # コマンドの実行
```

## taskコマンドを実行できるまでにセットアップ

```bash!
sh -c "$(curl --location https://taskfile.dev/install.sh)" -- -d -b /usr/local/bin
```