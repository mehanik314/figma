<template>
   <div class="deeplearning__wrapper">
       <div class="deeplearning__img">
           <img src="../assets/img/about.png" alt="">
       </div>
       <div class="wrapper__deeplearning__text">
           <h2 class="deeplearning__title">Apply AI, Deep Learning and Data Sciece to solve</h2>
           <p class="deeplearning__text">Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.</p>
           <button class="button__more">Learn More</button>
       </div>
   </div>
</template>

<script>
export default {

}
</script>

<style>
.button__more{
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 22px;
    color: #FFFFFF;
    padding: 15px 30px;
    background: #3A68B8;
    border: none;
    border-radius: 5px;
    margin-top: 50px;
}
.deeplearning__title{
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 40px;
    line-height: 130%;
    color: #FFFFFF;
}
.deeplearning__text{
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 160%;
    color: #FFFFFF;
    opacity: 0.7;
    margin-top: 30px;
}
.wrapper__deeplearning__text{
    width: 484px;
    height: 314px;
}
.deeplearning__img{
    width: 725px;
    height: 669px;
}
.deeplearning__wrapper{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
    width: 1277px;
    height: 669px;
}
</style>