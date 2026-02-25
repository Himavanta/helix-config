```shell
npm i -D @vue/language-server
npm i -g oxfmt prettier typescript typescript-language-server @vue/typescript-plugin vscode-langservers-extracted

git clone https://github.com/Himavanta/helix-config.git ~/.config/helix
```

vscode lit-html 支持

```shell
npm i -s ts-lit-plugin
```

```json
// tsconfig.json
{
  "compilerOptions": {
    "plugins": [
      {
        "name": "ts-lit-plugin"
      }
    ]
  }
}
```
