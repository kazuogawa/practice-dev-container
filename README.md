# practive-dev-container

dev container 内で、vibe-kanban を起動してみる project です。

## 手順

1. vscode で Dev Containers を インストールし、新しい開発コンテナを作成してください。

https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers

> [!CAUTION]
> Kiro では dev container は利用できません。VSCode を使う必要があります。
> 
> https://github.com/kirodotdev/Kiro/issues/164

2. 作成後、VS Code で開発コンテナに入ってください

3. 下記コマンドで vibe-kanban を起動できます。ログに出力された URL にアクセスするとカンバンにアクセスできます。

```shell
npx vibe-kanban
```

## 参照元

下記を参考に.devcontainer は作成

https://github.com/anthropics/claude-code/tree/main/.devcontainer
