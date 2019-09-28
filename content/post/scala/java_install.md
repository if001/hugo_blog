+++
title="JAVAのインストールメモ"
slug="java-install"
tags=["scala","JAVA"]
+++
PCを新調したのでJAVAを入れ直す必要があったので、そのときのメモ  

## JREインストール
インストール

```bash
$ sudo apt-get install default-jre 
```

入ってるかの確認

```bash
$ java -version
```

## JDKインストール
インストール

```bash
$ sudo apt-get install default-jdk
```

入ってるかの確認

```bash
$ javac -version
```

### OpenJDK

```bash
$ sudo apt-get install openjdk-8-jre
```

## JAVAの確認

以下のコマンドで利用するJAVAを選択できる

```bash
$ sudo update-alternatives --config java
```

```bash
alternative java (/usr/bin/java を提供) には 2 個の選択肢があります。

  選択肢    パス                                          優先度  状態
------------------------------------------------------------
* 0            /usr/lib/jvm/java-11-openjdk-amd64/bin/java      1101      自動モード
  1            /usr/lib/jvm/java-11-openjdk-amd64/bin/java      1101      手動モード
  2            /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java   1081      手動モード

現在の選択 [*] を保持するには <Enter>、さもなければ選択肢の番号のキーを押してください:
```

## JAVA_HOMEの設定

インストール済みのJAVAは以下のコマンドで確認できる。  

```bash
$ sudo update-alternatives --list java
```


```bash
/usr/lib/jvm/java-11-openjdk-amd64/bin/java
/usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java
```


