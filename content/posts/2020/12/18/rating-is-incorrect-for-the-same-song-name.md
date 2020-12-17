---
title: "[OngekiScoreLog]不具合情報 同名の楽曲がレーティング対象曲となると正しい値が表示されない"
date: 2020-12-18T00:15:13+09:00
draft: false

tags: ["不具合", "OngekiScoreLog_issue_open"]
categories: ["OngekiScoreLog"]
---

OngekiScoreLogをご利用いただきありがとうございます。  
現在以下の不具合を確認しております。

<!--more-->

<!-- ## 追記

本不具合の修正が完了いたしました。  
ご利用中の皆様にご迷惑をおかけしましたことを深くお詫び申し上げます。 -->

## 不具合内容

「Hand in Hand」や「Singularity」など、同じ名前の楽曲がレーティング対象として存在すると正しいレーティング値が算出されない

## 発生期間

2020/12/18 11:00 ～

## 本不具合に該当するユーザー

以下のいずれかを満たす方

- 「Hand in Hand（POPS＆ANIME）」と「Hand in Hand（niconico）」が同時にレーティング対象となっている
- 「Singularity（VARIETY）」と「Singularity（オンゲキ）」が同時にレーティング対象となっている

## 対象のGitHub Issue

{{< github_issue repository="project-primera/ongeki-score" id="294" >}}

今回の不具合はツールの根本から改修を行わなければいけない対応となっておりますため、改善には長くお時間を頂く可能性があります。  
何卒ご了承くださいますようお願い申し上げます。

この度はご迷惑をおかけし、誠に申し訳ございません。  
引き続きOngekiScoreLogをよろしくお願いいたします。
