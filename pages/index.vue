<template>
  <div class="tracking-widest ">
    <header class="ml-4">
      <div class="header-title">
        <h1>Labbit</h1>
      </div>
    </header>

    <div class="main pl-4 opacity-80">
      <p>企業理念</p>
    </div>

    <div class="mission py-20 text-center">
      <p>企業理念</p>
      <h2 class="text-4xl pt-1 pb-8">Corporate Mission</h2>
      <p>テキストテキストテキストテキストテキストテキストテキストテキスト </p>
    </div>

    <div class="service">
      <div class="service-img text-4xl text-slate-50">
        <h2 class="text">SERVICE</h2>
      </div>

      <div class="service-contents text-center py-20">
        <h3 class="text-2xl">事業内容</h3>
        <p class="py-6">株式会社Labbitの公式企業サイトの事業内容をご紹介します</p>
        <button type="button" class="btn border-2 rounded-lg p-2">REED MORE</button>
      </div>
    </div>

    <div class="company">
      <div class="company-img text-4xl font-bold">
        <h2>COMPANY</h2>
      </div>
      <div class="company-contents text-center py-20">
        <h3 class="text-2xl">会社概要</h3>
        <p class="py-6">株式会社Labbitの公式企業サイトの会社情報をご紹介します</p>
        <button type="button" class="btn border-2 rounded-lg p-2">REED MORE</button>
      </div>
    </div>

    <div class="recruit">
      <div class="recruit-img text-4xl">
        <h2>RECRUIT</h2>
      </div>
      <div class="recruit-contents text-center py-20">
        <h3 class="text-2xl">採用情報</h3>
        <p class="py-6">株式会社Labbitの採用情報について紹介しています</p>
        <button type="button" class="btn border-2 rounded-lg p-2">REED MORE</button>
      </div>
    </div>

    <div class="contact">
      <div class="contact-img text-4xl">
        <h2>CONTACT</h2>
      </div>
      <div class="service-contents text-center py-20">
        <h3 class="text-2xl">お問い合わせ</h3>
        <p class="py-6">株式会社Labbitに関するお問い合わせはこちらから</p>
        <button type="button" class="btn border-2 rounded-lg p-2">REED MORE</button>
      </div>
    </div>

    <div class="news px-20">
      <div class="news-title text-center py-20">
        <p>最新情報</p>
        <h2 class="text-4xl">News</h2>
      </div>
      <div class="news-contents">
        <img src="../img/company.jpg" alt="" class="w-64 ">
        <p class="pl-20">テキストテキストテキストテキスト</p>
      </div>
      <div class="news-contents py-10">
        <img src="../img/company.jpg" alt="" class="w-64" >
        <p class="pl-20">テキストテキストテキストテキスト</p>
      </div>
      <div class="news-contents">
        <img src="../img/company.jpg" alt="" class="w-64">
        <p class="pl-20">テキストテキストテキストテキスト</p>
      </div>
    </div>

    <footer>
      <div class="contact-us my-20  py-20 text-center">
        <div class="text2">
          <div class="contact-title py-10">
            <p>お問い合わせ</p>
            <h2 class="text-4xl font-bold">CONTACT US</h2>
          </div>
        <p>お電話からのお問い合わせはこちら(電話番号)までご連絡をお願い致します。<br> インターネットからのお問い合わせはこちらのお問い合わせフォームをご利用ください。後日、担当者からお返事させて頂きます。</p>
        <button type="button" class="btn my-20 border-2 rounded-lg p-2">CONTACT US</button>
        </div>

      </div>
      <div class="info py-10 px-20 text-1xl">
        <h3 class="border-b-2 pb-4 mb-4">株式会社Labbit</h3>
        <p>〒xxx-xxxx 住所</p>
        <p>Telxxx-xxxx-xxxx</p>
      </div>
      <div class="footer-contents py-20 px-20 text-1xl">
        <h3 class="border-b-2 pb-4 mb-4">CONTENTS</h3>
        <div class="nav flex flex-col">
          <nuxt-link class="nav-item" to="/">HOME</nuxt-link>
          <nuxt-link class="nav-item" to="/service">SERVICE</nuxt-link>
          <nuxt-link class="nav-item" to="/company">COMPANY</nuxt-link>
          <nuxt-link class="nav-item" to="/recruit">RECRUIT</nuxt-link>
          <nuxt-link class="nav-item" to="/contact">CONTACT</nuxt-link>
        </div>
      </div>
    </footer>
</div>
</template>>


<style>
  header {
    height: 100px;
  }

  header h1 {
    font-size: 1.6rem;
    line-height: 100px;
  }

  .main {
    background-image: url(../img/company.jpg);
    background-size: cover;
    width: 100%;
    height: 500px;
    display: flex;
    align-items: center;
  }

  .service-img , .company-img , .recruit-img , .contact-img {
    background-image: url(../img/company.jpg);
    background-size: cover;
    width: 100%;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
  }

  .service-img::before {
  content: '';
  background-color: rgba(0, 0, 0, 0.4);
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: block;
}

  .text{
  position: absolute;
  color: #fff;
  font-weight: bold;
}
  .text2{
  position: absolute;
  color: #fff;
  width: 100%;
  margin: 0 auto;
}

  .news-contents {
    display: flex;
  }

  .contact-us {
    background-image: url(../img/company.jpg);
    background-size: cover;
    width: 100%;
    height: 500px;
    position: relative;
  }

  .contact-us::before {
  content: '';
  background-color: rgba(0, 0, 0, 0.4);
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: block;
}

.nav-item {
  padding-bottom: 10px;
}


</style>
