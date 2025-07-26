---
title: AtCoderの環境
tags:
  - AtCoder
  - 環境構築
  - 競プロ
private: false
updated_at: ''
id: null
organization_url_name: null
slide: false
ignorePublish: true
---
# 競プロとは
日本語で普通の変換をかけると「今日プロ」となる、厄介なやつです。

与えられた問題に対して、自分がプログラムを書いて、実用的な実行時間で正しい答えを出せるプログラムを作成します。

# 環境構築
[こんな感じ](https://github.com/rotarymars/atcoder-competitive_programming)で出来上がります。

使っているツールは
- oj
- atcoder-cli

という感じです。
## oj
次のコマンドでインストールできます。
```bash
pip install git+https://github.com/online-judge-tools/oj
```

最近(2025/07/25)はAtCoderがReCaptchaを導入したので、簡単にはログインできなくなりましたが、少し調べるとoj用にログインできるようにしてくれるツールも存在します(あまり公にして良いものなのかわからないので紹介しません)。

ojで自分のアカウントにログインします。

## atcoder-cli
ojのラッパーみたいなやつです。

