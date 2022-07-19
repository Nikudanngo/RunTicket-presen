---
theme: apple-basic
layout: intro-image
image: '/img/phoneMockBack.png'
---

<div class="absolute bottom-50">
  <h1>RunTicket</h1>
  <p>学食モバイルオーダー.app</p>
</div>
<div>
  <span class="absolute bottom-10 right-10">
    2022実践ソフトウェア開発部 2班
  </span>
</div>

---
layout: statement
---

# 学食が好きだ
でも...

---
layout: image-right
image: '/img/graphProblem.svg'
---

# 今の学食の問題点
## アンケートを実施しました．

<v-clicks>

- 混雑している
- 並んでいては授業に遅れてしまうことがある
- 注文機の画面デザインが分かりにくい
- 決済方法が現金と楽天Edyしかない

</v-clicks>
---
layout: statement
---
# RunTicket

---
layout: statement
---
<video controls>
  <source src="/mov/Demo.mp4" type="video/mp4">
</video>
---
layout: image-right
image: '/img/UserClient.svg'
---
# ユーザークライアント側のシステム図

- フロントエンド : React
- バックエンド : Firebase (Hosting,Functions,Database)
- 決済処理 : PayPay API , Stripe API
- チケット発券 : Raspberry Pi