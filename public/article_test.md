---
title: 自己満でApexのbotを作った
tags:
  - ApexLegends
  - Discord
  - Bot
  - discord.js
private: false
updated_at: '2024-01-27T13:09:38+09:00'
id: 256a02b88c9821a7a916
organization_url_name: null
slide: false
ignorePublish: false
---
::: note warn
現在、このbotは動作していません。
:::

# はじめに
こんにちは、Sekibuuunです。
大人気fpsゲーム、Apex Legendsのbotを作ったので紹介します。

# 作った理由
私はかれこれ4年以上、Apex Legendsをプレイしています。
botを作った時のランクマッチでは、3つのマップで1日ごとにマップローテーションが行われていました。
ランクマッチのマップを確認するには、基本的にゲームを起動する必要がありました。
ランクマッチのマップを確認するためだけに、ゲームを起動するのは非常に面倒だったので、botを作ることにしました。

# 仕様
botをメンションすると、
- 今日のランクマッチのマップ
- 明日のランクマッチのマップ
- マップが切り替わるまでの時間

を教えてくれます。
![botの動作](<apex_map_rotation.png>)

# 使用技術
- discord.js
- TypeScript
- Biome
- [ZeaBur](https://zeabur.com/)

# 作った感想
discord.jsを使ってbotを作るのは初めてだったので、とても勉強になりました。
また、ZeaburというHostingサービスは、GitHubと連携してデプロイが出来るので、とても便利でした。
これでわざわざApexを起動しなくても、ランクマッチのマップを確認できるようになったので、とても満足しています。

# 今後の展望
プレイヤーごとに、ランクマッチのポイント(RP)を確認出来るようにしたいです。

# おわりに
今回は、自己満でApexのbotを作ったというお話でした。
最後まで読んでいただき、ありがとうございました。
[リポジトリ](https://github.com/sekibuuun/apex_map_rotation_bot)

