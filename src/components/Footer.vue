<template>
  <div class="footer">
      <div class="footer__wrapper">
          <div class="footer__adress">
              <img src="" alt="">
              <p></p>
              <p></p>
              <p></p>
              <p></p>
          </div>
          <div class="footer__information">
              <p class="footer__titles">INFORMATION</p>
              <p class="footer__text">New Collection</p>
              <p class="footer__text">About Store</p>
              <p class="footer__text">Contact Us</p>
              <p class="footer__text">Latest News</p>
              <p class="footer__text">Our Sitemap</p>
              <p class="footer__text">Orders History</p>
          </div>
          <div class="footer__menu">
              <p class="footer__titles">FOOTER MENU</p>
              <p class="footer__text">Instagram profile</p>
              <p class="footer__text">New Collection</p>
              <p class="footer__text">Contact Us</p>
              <p class="footer__text">Latest News</p>
              <p class="footer__text">Terms & Conditions</p>
              <p class="footer__text">Purchase Theme</p>
          </div>
          <div class="footer__links">
              <p class="footer__titles">USEFUL LINKS</p>
              <p class="footer__text">Instagram profile</p>
              <p class="footer__text">New Collection</p>
              <p class="footer__text">Contact Us</p>
              <p class="footer__text">Latest News</p>
              <p class="footer__text">Terms & Conditions</p>
              <p class="footer__text">Purchase Theme</p>
          </div>
          <div class="footer__about">
              <p class="footer__titles">ABOUT THE STORE</p>
              <p class="footer__text">Lorem ipsum is placeholder text commonly used in the graphic, print, and layouts and visual mockups.</p>
              <p class="footer__text">www.company.com</p>
              <p class="footer__text">тут иконки</p>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.footer{
    width: 100%;
    height: 508px;
    margin-top: 170px;
}
.footer__text{
    margin-bottom: 20px;
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 18px;
    color: #FFFFFF;
    opacity: 0.6;
}
.footer__titles{
    margin-bottom: 32px;
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 20px;
    color: #FFFFFF;
}
.footer__about{
    width: 261px;
}
.footer__information,.footer__menu,.footer__links{
    margin-right: 30px;
}
.footer__wrapper{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 1140px;
    height: 284px;
    margin: 0 auto;
}
</style>