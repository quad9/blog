## memo

### 200518
> markdownのnpmをどれにするか迷ったが、「react-markdown」「react-mde」の組み合わせで進めることにする。

なお、以下のサイトを参照した。『[ReactでMarkdownエディタを実装する方法](https://harkerhack.com/react-markdown-editor/)』

### 200520

react-md-editorでのMD部の構築をする。

### 200523

decide library react-simple-mde-editor. try to deproy github pege.

```
$ npm install gh-pages --save-dev
```

__modify package.json__

```
"homepage": "http://username.github.io/react-pages"

"scripts": {
  ...
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

```
$ npm run deploy
```
