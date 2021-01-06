<template>
  <div id="main">
    <div class="eyecatch">
      <p class="catchcopy">機械にはできない仕事を</p>
      <div class="news flex">
        <div class="news-content">
          <p class="news_date">2019/01/01</p>
          <p class="news_title">
            ニュースタイトルがここに入ります。三月の決算報告書。
          </p>
        </div>
        <div class="news-icon">news</div>
      </div>
    </div>
    <div class="mission">
      <div class="mission-content">
        <h2 class="mission_title">
          お客様のために進化する成長企業であり続ける
        </h2>
        <p class="mission_text">
          顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。
        </p>
        <a href="" class="common-btn mission-btn">ミッション詳細</a>
      </div>
      <div class="mission-img">
        <img src="../assets/mission-img.jpg" alt="" />
      </div>
    </div>
    <div class="service">
      <h2 class="service-title section-title">service</h2>
        <div class="service-content">
        <div class="service-img">
          <img src="../assets/service2.jpg" alt="" />
        </div>
        <div class="service-content_inner">
          <h3 class="mgb-15">web制作事業</h3>
          <p class="mgb-15">コーチングのミッション</p>
          <p class="mgb-15">
            ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
          </p>
          <a href="" class="common-btn service-btn">サービス詳細</a>
        </div>
      </div>
      <div class="service-content">
        <div class="service-img service-img_second">
          <img src="../assets/service1.jpg" alt="" />
        </div>
        <div class="service-content_inner service-content_inner-second">
          <h3 class="mgb-15">web制作事業</h3>
          <p class="mgb-15">コーチングのミッション</p>
          <p class="mgb-15">
            ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
          </p>
          <a href="" class="common-btn service-btn">サービス詳細</a>
        </div>
      </div>
    </div>
    <div class="company">
      <div class="recruit-company flex">
        <div class="recruit-company_size company-img">
          <h2 class="company-title section-title">
            company<br /><span>会社概要</span>
          </h2>
        </div>
        <div class="recruit-company_size recruit-img">
          <h2 class="company-title section-title">
            recruit<br /><span>採用情報</span>
          </h2>
        </div>
      </div>
    </div>
    <div class="faq">
      <h2 class="faq-title">FAQ</h2>
      <p class="faq-title-jp">良くある質問</p>
    </div>
    <div class="contact">
      <h2 class="contact-title section-title">
        contact<br /><span>お問い合わせ</span>
      </h2>
      <p class="contact-subtitle section-title">
        お気軽にお問い合わせください。
      </p>
      <p class="contact-text">
        資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。
      </p>
      <a href="" class="common-btn contact-btn">お問い合わせへ</a>
    </div>
<!--   <footer class="top-footer">
    <div class="footer-bar">
      <div class="flex">
        <h1 class="header-logo">estra inc.</h1>
        <nav class="header-nav">
          <ul>
            <li><a href="#">home</a></li>
            <li><a href="#">about</a></li>
            <li><a href="#">service</a></li>
            <li><a href="#">works</a></li>
            <li><a href="#">price</a></li>
            <li><a href="#">contact</a></li>
          </ul>
        </nav>
      </div>
    </div>
    <small>Copyright 2019 estra inc. All Rights Reserved.</small>
  </footer> -->
  </div>
  
</template>

<style scoped>

#main {
  height: auto;
}

html{
  height: 100%;
}

a {
  color: #333333;
  text-decoration: none;
}

img {
  width: 100%;
  height: 100%;
  display: block;
}

.flex {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

body {
  color: #333333;
  height: 100%;
}

.mgb-15 {
  margin-bottom: 15px;
}

.common-btn {
  display: block;
  width: 130px;
  height: 40px;
  line-height: 40px;
  background: #fff;
  padding: 0 20px;
  color: #000;
  text-align: center;
}

.section-title {
  font-size: 40px;
  line-height: 1;
}

.section-title span {
  font-size: 20px;
}

.eyecatch{
  height: calc(100vh - 70px);
  background: url(../assets/eyecatch.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}

.catchcopy {
  position: absolute;
  top: 60%;
  left: 10%;
  font-size: 60px;
  font-style: italic;
  font-weight: bold;
  color: #fff;
  line-height: 1;
}

/*------------------------*/
/*         news           */
/*------------------------*/
.news {
  height: unset;
  position: absolute;
  bottom: 0;
  right: 0;
  width: 50%;
}
.news-content {
  background: #fff;
  width: 80%;
  height: 70px;
}

.news_date {
  height: unset;
  padding: 5px;
}

.news_title {
  height: unset;
  padding: 0 15px;
  line-height: 20px;
}
.news-icon {
  background: #000;
  width: 20%;
  height: 70px;
  line-height: 70px;
  text-align: center;
  color: #fff;
}

/*------------------------*/
/*         mission        */
/*------------------------*/
.mission {
  height: unset;
  position: relative;
  background: #000;
  margin-bottom: 10%;
  z-index: 999;
}

.mission-content {
  padding: 10% 0 10% 20%;
  box-sizing: border-box;
  width: 70%;
}

.mission_title,
.mission_text {
  line-height: 25px;
  margin-bottom: 30px;
  color: #fff;
}

.mission_title {

  line-height: 50px;
  font-size: 30px;
}

.mission-img {
  width: 40%;
  height: auto;
  position: absolute;
  bottom: -10%;
  right: 5%;
  z-index: -999;
}

/*------------------------*/
/*         service        */
/*------------------------*/
.service {
  height: unset;
  background: #e5e5e5;
  margin-bottom: 10%;
}

.service-title {
  text-align: center;
  padding: 20px 0;
}

.service-content {
  position: relative;
  padding-bottom: 15%;
}

.service-img {
  width: 50%;
  margin-left: 50%;
}

.service-img_second {
  margin: 0 50% 0 0;
}

.service-content_inner {
  height: unset;
  position: absolute;
  top: 15%;
  left: 20%;
  background: #fff;
  width: 40%;
  padding: 5% 5%;
  box-sizing: border-box;
  line-height: 25px;
}

.service-content_inner-second {
  left: 40%;
}

.service-btn {
  border: 1px solid #000;
  margin: 0 0 0 auto;
}

/*------------------------*/
/*        recruit         */
/*------------------------*/
.company {
  height: unset;
  margin-bottom: 10%;
}

.recruit-company_size {
  width: 48%;
  height: 300px;
  position: relative;
}

.company-img {
  background: url(../assets/company.jpeg) center/cover no-repeat;
}

.recruit-img {
  background: url(../assets/recruit.jpg) center/cover no-repeat;
}

.company-title {
  text-align: center;
  color: #fff;
  position: absolute;
  top: 85%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.company-title span {
  color: #fff;
}

/*------------------------*/
/*        faq             */
/*------------------------*/
.faq {
  height: unset;
  width: 70%;
  background: #000;
  margin: 0 auto 10%;
  padding: 70px;
}

.faq-title,
.faq-title-jp {
  display: inline-block;
  color: #fff;
}

.faq-title {
  font-size: 40px;
  width: 10%;
}

.faq-title-jp {
  font-size: 20px;
  width: 80%;
  text-align: center;
}

/*------------------------*/
/*        contact         */
/*------------------------*/
.contact {
  height: unset;
  background: url(../assets/contact-bg.jpg) center/cover no-repeat;
  padding: 10%;
}

.contact-title,
.contact-title span,
.contact-subtitle,
.contact-text {
  color: #fff;
  text-align: center;
}

.contact-title,
.contact-subtitle,
.contact-text {
  margin-bottom: 40px;
}

.contact-btn {
  margin: 0 auto;
  background: none;
  border: 1px solid #fff;
  color: #fff;
}

/*------------------------*/
/*         Footer         */
/*------------------------*/

/* .top-footer{
  position: relative;
  height: 90px;
  text-align: center;
  background-color: #000;
  color: #fff;
}

.footer-bar {
  height: 70px;
  line-height: 70px;
}

.top-footer small {
  text-align: center;
  color: #fff;
}

.header {
  height: 70px;
  background: #000;
}

.header-wrap {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #f2f2f2;
  line-height: 70px;
}

.header-nav ul {
  display: flex;
}

.header-nav li {
  margin-right: 35px;
  font-size: 16px;
}

.header-nav a {
  color: #f2f2f2;
} */


@media screen and (max-width: 768px) {
  .header-nav {
    display: none;
  }
  .catchcopy {
    top: 85%;
    left: 50%;
    width: 80%;
    text-align: center;
    transform: translate(-50%, -50%);
  }
  .news {
    width: 100%;
  }
  .mission-content {
    padding: 10% 0;
    margin: 0 auto;
  }
  .service-content_inner {
    width: 60%;
    left: 10%;
  }
  .service-img {
    width: 70%;
    margin-left: 30%;
  }
  .service-img_second {
    margin: 0 30% 0 0;
  }
  .service-content_inner-second {
    left: 30%;
  }
  .service-content {
    margin: 0 auto;
  }
  .service-content_inner {
    width: 90%;
    position: inherit;
    background: rgba(255, 255, 255, 0.8);
    left: 5%;
  }
  .service-img {
    width: 90%;
    margin: 0 auto;
  }
  .recruit-company_size {
    width: 100%;
  }

  .faq{
    width: 60%;
  }

  .faq-title {
    margin-left:-10px;
    margin-right: 20px;
    font-size: 30px;
  }
  .top-footer .header-logo {
    margin: 0;
    width: 100%;
    text-align: center;
  }
}
</style>