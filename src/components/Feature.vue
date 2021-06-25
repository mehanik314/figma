<template>
  <div class="feature__wrapper">
        <div class="feature__items__wrapper">
            <div class="feature__items">
                <img src="../assets/img/feature1.png" alt="" class="feature__img">
                <h1 class="feature__title">Naxly as the Winners in Global Agency Awards</h1>
                <p class="feature__text">Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups.</p>
            </div>
            <div class="feature__items">
                <img src="../assets/img/feature2.png" alt="" class="feature__img">
                <h1 class="feature__title">Expert Prespective Agency Awards</h1>
                <p class="feature__text">Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups.</p>
            </div>
            <div class="feature__items">
                <img src="../assets/img/feature3.png" alt="" class="feature__img">
                <h1 class="feature__title">Business Prespective Global Agency Awards</h1>
                <p class="feature__text">Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups.</p>
            </div>
            <div class="feature__items">
                <img src="../assets/img/feature4.png" alt="" class="feature__img">
                <h1 class="feature__title">Value for Results in Global Agency Awards</h1>
                <p class="feature__text">Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups.</p>
            </div>
            <div class="feature__items">
                <img src="../assets/img/feature5.png" alt="" class="feature__img">
                <h1 class="feature__title">Global Experience in Agency Awards</h1>
                <p class="feature__text">Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups.</p>
            </div>
        </div>
        <div class="feature__slider__wrapper">
            <button class="slider__btn"></button>
            <button class="slider__btn"></button>
            <button class="slider__btn"></button>
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.feature__title{
    font-family: 'Open Sans';
    width: 300px;
    height: 62px;
    font-style: normal;
    text-align: center;
    font-weight: 700px;
    font-size: 25px;
    line-height: 125%;
    color: #FFFFFF;
    opacity: 0.7;
    margin-top: 30px;
}
.feature__text{
    font-family: 'Open Sans';
    width: 300px;
    height: 104px;
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 160%;
    color: #FFFFFF;
    opacity: 0.7;
    margin-top: 30px;
}
.slider__btn{
    width: 14px;
    height: 14px;
    border-radius: 10px;
    border-style: none;
    background: #2C3647;
    opacity: 0.5;
    

border-radius: 10px;
}
.feature__slider__wrapper{
    display: flex;
    justify-content: space-between;
    width: 66px;
    height: 15px;
}
.feature__items__wrapper{
    display: flex;
    column-gap: 29.84px;
    margin: 170px auto 0px auto;
    justify-content: center;
    align-content: center;
    width: 1800px;
    height: 389px;
}
.feature__wrapper{
    display: flex;
    flex-direction: column;
    align-items: center;
}
@media (max-width:1280px){
    .feature__wrapper{
    flex-wrap: wrap;
    width: 1145px;
    height: auto;
    }
}
.feature__items{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 360px;
    height: 389px;
    
}
.feature__img{
    width: 97px;
    height: 103px;
}
.feature__items:nth-child(1) .feature__img{
    width: 72px;
    height: 69px;
    margin-top: 64px;
}
</style>