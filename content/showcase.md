---
title: "Showcase"
date: 2021-03-07T23:51:14+09:00
draft: false
---
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v6.0.0/css/all.css">
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP&display=swap" rel="stylesheet">
<style>
div {
    font-family: 'Fira Mono', 'Noto Sans JP', monospace;
}
</style>

作成したものの紹介です．
## ソフトウェア
### Discord Spamming Button <a href="https://github.com/unyacat/DiscordSpammingButton"><i class="fab fa-github"></i></a>
<!-- [サンプルはこちら](https://dark-pub.web.app/)   -->
定型文を登録して Discord に Webhook を通じてコメントできる Web アプリケーション．  
コピペを連投するのに便利．WebApp としてスマートフォンでも気軽に使える．  
データベースに Firebase Cloud Firestore を利用しており(無駄に)リアルタイムに登録して遊べる．  
<div style="text-align: center" >
<img src="/images/dsb-sample.png" width="600px">
</div>


### Swarm Checkins Plotter <a href="https://odekake.unyacat.net"><i class="fa fa-link"></i></a>
URL: https://odekake.unyacat.net  
Swarmのチェックインを地図にプロットする．日時指定もできる．  

<div style="text-align: center" >
<img src="/images/swarm-log-sample.png" width="600px">
</div>

### MH-Z14A-WebUI <a href="https://github.com/unyacat/MH-Z14A-WebUI"><i class="fab fa-github"></i></a>
NDIR 二酸化炭素センサー「MH-Z14A」と Python + Flask，Vue.js + Vuetify を利用した定期的な二酸化炭素濃度の計測および簡易的な WebUI の実装．  
定期的に自動更新されるのでこのまま放置するだけでグラフが描画される．Grafana と連携することもできる．  

<div style="text-align: center" >
<img src="/images/mh-z14a-sample.png" width="600px">
</div>


### 秒給メーター <a href="https://github.com/unyacat/kyuryo-meter"><i class="fab fa-github"></i></a>
[https://secpay.netlify.app/]()  
時給があるなら秒単位で給料が出てもいいじゃない，とバイト中の暇なときに思ったので作成した．  
2 日で公開までできたので満足．  

<!-- <div style="text-align: center" >
<img src="/images/second-pay-sample.png" width="600px">
</div> -->

### Spotify Nowplaying Tweeter<a href="https://github.com/unyacat/nowplaying.unyacat.net"><i class="fab fa-github"></i></a>
[https://nowplaying.unyacat.net/]()  
Spotifyで再生中の曲の情報を取得してツイートするだけのWebサイト．  
半日で公開までできたので満足．  


### WestJR <a href="https://github.com/unyacat/westjr"><i class="fab fa-github"></i></a>
JR西日本列車走行位置非公式 API を利用しやすくする Python ライブラリ
```python
import westjr
jr = westjr.WestJR(line='kobesanyo', area='kinki')

print(jr.get_trains())
# {'update': '2021-03-31T08:14:34.313Z', 'trains': [{'no': '798T', 'pos': '0414_0415', ...
print(jr.convert_pos(jr.get_trains()["trains"][2]))
# ('新大阪', '大阪')  ← 新大阪-大阪間を走行中
```

<br />
<br />
<br />

## ハードウェア
### NFC基板名刺 <a href="https://unyacat.net/2022/02/06/pcb-business-card/"><i class="fas fa-newspaper"></i></a>
Suica風コイルをPCBに内蔵した名刺．チップを載せることでNFCタグとして利用できる．
<div style="text-align: center" >
<img src="/images/nfc-bussiness-card.jpeg" width="600px">
</div>


### 3Dアイコン <a href="https://unyacat.net/2021/07/12/making-3d-icon/"><i class="fas fa-newspaper"></i></a>
3Dプリンタで印刷した物理アイコン．ストラップにもなる．
<div style="text-align: center" >
<img src="/images/3d-icon.jpg" width="600px">
</div>

