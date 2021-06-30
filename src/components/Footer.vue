<template>
  <div class="footer">
      <div class="footer__wrapper">
          <div class="footer__adress">
              <img src="../assets/img/logo-footer.png" alt="">
              <p class="footer__logo__title">Artificial Intelligence</p>
              <p class="footer__adress__text">Lorem ipsum is placeholder text commonly used in the graphic, print, and layouts and visual mockups.</p>
              <p class="contact-inf"><i class="fa fa-envelope-o icons-adress" aria-hidden="true"></i>Company@gmail.com.com</p>
              <p class="contact-inf"><i class="fa fa-phone icons-adress" aria-hidden="true"></i>Phone: (064) 332-1233</p>
              <p class="contact-inf"><i class="fa fa-map-marker icons-adress" aria-hidden="true"></i>450 Wall Street, USA, New York</p>
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
              <p class="footer__about__text">Lorem ipsum is placeholder text commonly used in the graphic, print, and layouts and visual mockups.</p>
              <p class="footer__link__site">www.company.com</p>
              <p class="footer__social">
                  <i class="fa fa-facebook social-icons" aria-hidden="true"></i>
                  <i class="fa fa-instagram social-icons" aria-hidden="true"></i>
                  <i class="fa fa-twitter social-icons" aria-hidden="true"></i>
                  <i class="fa fa-instagram social-icons" aria-hidden="true"></i>
                  <i class="fa fa-youtube-play social-icons" aria-hidden="true"></i>
              </p>
                <select v-model="selected">
                    <option value="" selected="selected">English</option>
                    <option>Russian</option>
                </select>
          </div>
      </div>
  </div>
</template>

<script>

export default {
    data(){
        return{
            default: 'russi',
            selected: ''
        }
    },
}
</script>

<style>
.footer__social{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    color: white;
    opacity: 0.6;
    margin-bottom: 52px;
    width: 175px;
    height: 15px;
}
.footer__about__text{
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 19px;
    color: #FFFFFF;
    opacity: 0.6;
}
.footer__link__site{
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 19px;
    color: #FFFFFF;
    margin-top: 26px;
    margin-bottom: 20px;
}
option{
    background-color: black;
}
select{
    background-color: transparent;
    color: white;
    border-color: transparent;
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 19px;
}
.social-icons{
    margin-right: 25px;
}
.icons-adress{
    margin-right: 10px;
}
.footer__adress{
    width: 261px;
    height: 284px;
}
.footer__logo__title{
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 22px;
    color: #3A68B8;
    margin-top: 7.83px;
    margin-bottom: 9.86px;
}
.contact-inf:last-child{
    margin-bottom: 0px;
}
.contact-inf{
    margin-bottom: 19px;
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 19px;
    color: #FFFFFF;
}
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
.footer__text:last-child{
    margin-bottom: 0px;
}
.footer__adress__text{
    margin-bottom: 34px;
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 18px;
    color: #FFFFFF;
    opacity: 0.6;
}
.footer__titles{
    margin-bottom: 30px;
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 20px;
    color: #FFFFFF;
}
.footer__about{
    height: 258px;
    width: 261px;
}
.footer__information,.footer__menu,.footer__links{
    display: flex;
    flex-direction: column;
    
    margin-right: 30px;
}
.footer__wrapper{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: flex-end;
    width: 1140px;
    height: 284px;
    margin: 0 auto;
}
</style>