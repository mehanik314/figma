<template>
    <div class="reviews">
        <div class="reviews__wrapper__text">
            <h2 class="reviews__title">What our clients say about our awesome solutions</h2>
            <p class="reviews__text">To take a trivial example, which of us ever undertakes laborious physical exercise, except to obtain some advantage from it who do not know.</p>
            <p class="reviews__text">Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing .</p>
            <p class="reviews__text">Lorem ipsum is placeholder previewing layouts and visual mockups.</p>
            <p class="reviews__text">Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.</p>
        </div>
        <div class="reviews__wrapper__img">
            <img src="../assets/img/about3.png" alt="">
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.reviews{
    display: flex;
    flex-direction: row;
    margin: 170px auto 0px auto;
    width: 1146px;
    height: 551px;
}
.reviews__wrapper__text{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    width: 548px;
    height: 464px;
}
.reviews__title{
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 700px;
    font-size: 40px;
    line-height: 52px;
    color: #FFFFFF;
    margin-bottom: 40px;
}
.reviews__text{
    font-family: 'Open Sans';
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 160%;
    width: 460px;
    margin-bottom: 20px;
    color: white;
    opacity: 0.7;
}
</style>