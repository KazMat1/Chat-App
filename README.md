# chat_app

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## git 操作 20231005
## 概要
- gitコマンドの説明をします
- ターミナルでも、VSCode上でもどちらでも操作できます。

# コマンド一覧
## よく使う
### ブランチ関係（後で）
- branch
- fetch
- switch/checkout

### 開発するとき
*自分の変更をアップロードするときに使う*
- add
```
# 1つのファイルをaddする
git add {file_name}

# すべてのファイルをaddする
git add .
```

- commit
```
# コミットメッセージと一緒にコミットする
git commit -m "{write_massage_here}"
```

- push
```
# プッシュするとき
git push origin {branch_name}

# よく使うブランチ名
git push origin main or git push origin master
```

*他人の変更をダウンロードくるときに使う*
- pull
- merge
## 時々使う
### ヘルプ
- git help

### 確認
- ログ（履歴）を見るとき
  - git log
    ```
    git log
    ```

- 差分を見るとき
    - git diff
    ```
    git diff
    ```

## 作業手順
*自分の変更をアップロードするときに使う*
- 変更したファイルをaddする
- addしたファイルをcommitする
- commitしたファイルをpushする
