+++
title="Vue.jsからFirebase StorageとDatabaseを使う"
slug="book_reports_storage_firestore"
tags=["WebApp", "Firebase"]
date="2019-09-29T00:00:00+09:00"
draft="true"
+++

## はじめに
Authentication、Hostingに続いて、Vue.jsからFirebaseのCloud Storage、FireStoreをつかってみました。  
それぞれの、簡単な使い方をまとめておきます。すべて同じプロジェクト上のものを利用するので、連携はとても楽でした。  

ざっくりとした流れは以下になります。

画像

Vue.jsで画像を生成、Cloud Storageに保存、保存したURLを取得し、URLやその他の情報をFireStoreに保存という流れです。  

## Cloud Storage


## FireStore