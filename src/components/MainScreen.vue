<template>
   <header class="header">
        <div class=header__wrapper>
          <div class="header__logo">
              <img src="../assets/img/logo.png" alt="">
          </div>
          <ul class="header__item">
              <li class="header__list"><a href="" class="header__link">Home</a></li>
              <li class="header__list"><a href="" class="header__link">About</a></li>
              <li class="header__list"><a href="" class="header__link">Services</a></li>
              <li class="header__list"><a href="" class="header__link">Blog</a></li>
              <li class="header__list"><a href="" class="header__link">Contact</a></li>
          </ul>
          <button class="header__button">Sign In</button>
        </div>
    <div class="HeroArea__wrapper">
      <div class="HeroArea">
          <div class="HeroArea__wrapper__text">
            <p class="HeroArea__title__one">Next genaretion platform</p>
            <p class="HeroArea__title">Artificial intelligence & Syber security</p>
            <p class="HeroArea__text">Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.</p>
            <div class="HeroArea__wrapper__buttons">
              <button class="HeroArea__button__getstarted">Get Started</button>
              <button class="HeroArea__button__watch">
                <img src="../assets/img/Play.png" alt="" class="button__img__play">
                <span>Watch Video</span>
              </button>
            </div>
          </div>
          <div class="HeroArea__banner__shape__wrapper">
            <div class="HeroArea__banner__shape"></div>
          </div>
      </div>
    </div>
     <div class="HeroArea__footer">
        <ul class="HeroArea__footer__item">
          <li class="HeroArea__footer__list"><img src="../assets/img/logo1.png" alt="" class="HeroArea__footer_imgs"></li>
          <li class="HeroArea__footer__list"><img src="../assets/img/logo2.png" alt="" class="HeroArea__footer_imgs"></li>
          <li class="HeroArea__footer__list"><img src="../assets/img/logo3.png" alt="" class="HeroArea__footer_imgs"></li>
          <li class="HeroArea__footer__list"><img src="../assets/img/logo4.png" alt="" class="HeroArea__footer_imgs"></li>
        </ul>
      </div>
          </header>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.HeroArea__banner__shape__wrapper{
  width: 632px;
  height: 634px;
}
.HeroArea__banner__shape{
  background-image: url('../assets/img/bgimg.png');
  width: 100%;
  height: 100%;
  background-repeat: no-repeat;
  background-size: contain;
}
.header__wrapper{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: 1145px;
  height: 100px;
}
.HeroArea__footer__item{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.HeroArea__footer{
  margin: 89px auto 99px auto;
  width: 1146px;
  height: 59px;
}
.button__img__play{
  height: 27px;
  width: 24px;
  margin-right: 10px;
}
.HeroArea__wrapper__text{
  width: 604px;
  height: 415px;
}
.HeroArea__img{
  width: 632px;
  height: 634px;
}
.HeroArea__title__one{
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 160%;
  color: #3A68B8;
  margin-bottom: 10px;
}
.HeroArea__title{
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 700;
  font-size: 55px;
  line-height: 130%;
  color: #FFFFFF;
  margin-bottom: 40px;
}
.HeroArea__text{
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 160%;
  color: #FFFFFF;
  opacity: 0.7;
  margin-bottom: 50px;
}
.HeroArea{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.HeroArea__wrapper{
  width: 1145px;
  margin: 0 auto;
}
.HeroArea__wrapper__buttons{
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  text-align: center;
}
.HeroArea__button__getstarted{
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 27px;
  padding: 15px 30px;
  background: #3A68B8;
  color: white;
  width: 171px;
  height: 57px;
  text-align: center;
  border: none;
  border-radius: 5px;
  margin-right: 20px;
}
.HeroArea__button__watch{
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 27px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 15px 30px;
  background: #3A68B8;
  color: white;
  width: 217px;
  height: 57px;
  border: none;
  border-radius: 5px;
  margin-right: 20px;
}
.header{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    height: 100px;
    width: 100%;
    background-color: #020A18;
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
}
.header__item{
    display: flex;
    flex-direction: row;
    justify-content: center;
}
.header__logo{
    margin-right: auto;
}
.header__button{
    margin-left: auto;
    padding: 15px 30px;
    background: #3A68B8;
    border: none;
    border-radius: 5px;
}
.header__list{
    margin-right: 43px;
}
.header__link{
  text-decoration: none;
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 22px;
  color: white;
}
.header__list:last-child{
    margin-right: 0px;
}
</style>
