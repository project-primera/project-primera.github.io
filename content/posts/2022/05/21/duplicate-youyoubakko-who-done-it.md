---
title: "[OngekiScoreLog]不具合情報 「妖々跋扈 ～ Who done it!」が重複して登録されてしまう"
date: 2022-05-21T05:58:25+09:00
draft: false

tags: ["不具合", "OngekiScoreLog_issue_close"]
categories: ["OngekiScoreLog"]
---

OngekiScoreLogをご利用いただきありがとうございます。  
以下の不具合を確認しておりました。  
現在は修正が完了しております。

<!--more-->

## 不具合内容

「妖々跋扈 ～ Who done it!」と「妖々跋扈 ～ Who done it！！！」が重複して登録されてしまう

## 発生期間

2022/05/20 16:36:22 ～ 2022/05/22 7:20

## 本不具合に該当するユーザー

上記期間にスコア登録を行ったユーザー

## 対応内容

現在どちらの楽曲名が正しい情報かを判断しかねるため対応を検討中です。  
暫定対応のため一時的に「妖々跋扈 ～ Who done it！！！」をレーティング集計の対象外としております。  
当該楽曲のスコアを更新しレーティング対象となっている場合、表示されるレーティング情報に誤りが発生します。

## 対応内容 （追記：2022/05/22 7:20）

- 楽曲データを「妖々跋扈 ～ Who done it!」から「妖々跋扈 ～ Who done it！！！」に変更いたしました
- 変更前の「妖々跋扈 ～ Who done it！！！」としてスコア登録を行っていた方の該当データを削除いたしました
- 称号データを「妖々跋扈 ～ Who done it!」から「妖々跋扈 ～ Who done it！！！」に変更いたしました。
- 変更前の「妖々跋扈 ～ Who done it！！！」として称号を獲得していた方の該当データを削除いたしました

### 該当時間にスコア登録を行っていない方

データはすべて引き継がれておりますので、追加の対応は必要ありません。

### 該当時間にスコア登録を行い、「妖々跋扈 ～ Who done it！！！」を登録した方

該当ユーザー数: 1457人

旧楽曲名の「妖々跋扈 ～ Who done it!」を正しいデータとし、変更前の「妖々跋扈 ～ Who done it！！！」として登録されたデータを削除しております。  
次回ブックマークレット実行時に、スコアの更新がある場合は記録されます。

### 該当時間にスコア登録を行い、「妖々跋扈 ～ Who done it！！！」の称号を登録した方

該当ユーザー数: 2人

旧称号名の「妖々跋扈 ～ Who done it!」を正しいデータとし、変更前の「妖々跋扈 ～ Who done it！！！」として登録されたデータを削除しております。  
次回ブックマークレット実行時に、旧称号を獲得していない場合は記録されます。

---

この度はご迷惑をおかけし、誠に申し訳ございません。  
引き続きOngekiScoreLogをよろしくお願いいたします。
