<template>
  <div class="fourthBlock-container">
    <h1 class="fourthBlock-heading__h1">Схема работы</h1>
    <p class="fourthBlock-heading__p">Lorem ipsum dolor sit amet consectetur. Augue velit in enim sagittis imperdiet sit mauris. Vitae sit in fusce massa amet.</p>
    <div class="fourthBlock-card-comtainer">
        <div class="fourthBlock-card-pattern" id="fourthBlock-card-img-1">
            <div class="fourthBlock-card-pattern-title">
                <h1 class="fourthBlock-card-number__h1">01</h1>
                <h1 class="fourthBlock-card-title__h1">ВЫ ОСТАВЛЯЕТЕ ЗАЯВКУ</h1>
            </div>
            <p class="fourthBlock-card-one-txt__p">Отправить запрос вы можете любым удобным для вас способом: например, через форму на сайте. Также вы можете связаться с нами напрямую.</p>
        </div>
        <div class="fourthBlock-card-pattern" id="fourthBlock-card-img-2">
            <div class="fourthBlock-card-pattern-title">
                <h1 class="fourthBlock-card-number__h1">02</h1>
                <h1 class="fourthBlock-card-title__h1">МЫ ПРОВЕРЯЕМ <br> НАЛИЧИЕ ПОЗИЦИЙ</h1>
            </div>
            <p class="fourthBlock-card-two-txt__p">Проверяем наличие на складе, <br> а также актуальность производства <br> (возможна замена, если необходимо.) Если требуется замена - подбираем аналоги и привозим на заказ.</p>
        </div>
        <div class="fourthBlock-card-pattern" id="fourthBlock-card-img-3">
            <div class="fourthBlock-card-pattern-title">
                <h1 class="fourthBlock-card-number__h1">03</h1>
                <h1 class="fourthBlock-card-title__h1">ФОРМИРУЕМ КОММЕРЧЕСКОЕ ПРЕДЛОЖЕНИЕ</h1>
            </div>
            <p class="fourthBlock-card-three-txt__p">На данном этапе мы с вами согласуем ценовое предложение, обговариваем сроки поставки и условия оплаты.</p>
        </div>
        <div class="fourthBlock-card-pattern" id="fourthBlock-card-img-4">
            <div class="fourthBlock-card-pattern-title">
                <h1 class="fourthBlock-card-number__h1">06</h1>
                <h1 class="fourthBlock-card-title__h1">ПРОВОДИМ ОПЛАТУ</h1>
            </div>
            <p class="fourthBlock-card-six-txt__p">Поставляем вам товар в надлежащей упаковке в сопровождении оригиналов всех необходимых документов либо вы забираете его самовывозом.</p>
        </div>
        <div class="fourthBlock-card-pattern border-box" id="fourthBlock-card-img-5">
            <div class="fourthBlock-card-pattern-title">
                <h1 class="fourthBlock-card-number__h1">05</h1>
                <h1 class="fourthBlock-card-title__h1">МЫ ВЫПОЛНЯЕМ ЗАКАЗ</h1>
            </div>
            <p class="fourthBlock-card-five-txt__p">Товар поступает на склад в Москву или Санкт-Петербург, где мы сверяем правильность поставки и начинаем сборку.</p>
        </div>
        <div class="fourthBlock-card-pattern border-box" id="fourthBlock-card-img-6">
            <div class="fourthBlock-card-pattern-title">
                <h1 class="fourthBlock-card-number__h1">04</h1>
                <h1 class="fourthBlock-card-title__h1">ВЫ ПОЛУЧАЕТЕ ТОВАР</h1>
            </div>
            <p class="fourthBlock-card-four-txt__p">Далее, после получения авансового платежа, мы размещаем заказ.</p>
        </div>
    </div>
    <button class="fourthBlock-order__btn">ОСТАВИТЬ ЗАЯВКУ</button>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.fourthBlock-container{
    background: url('../assets/img/fourthblockbackground.png');
    height: 1098px;
    background-size: cover;
}
.fourthBlock-heading__h1{
    font-style: normal;
    font-weight: 700;
    font-size: 37px;
    /* color: #111111; */
    line-height: 45px;
    padding-top: 103px;
    margin-bottom: 24px;
    color: #111111;
}
.fourthBlock-heading__p {
    font-style: normal;
font-weight: 400;
font-size: 22px;
line-height: 22px;
/* identical to box height, or 100% */

text-align: center;
margin-bottom: 46px;
color: #333333;
}
.fourthBlock-card-pattern {
    width: 439.5px;
    height: 268.5px;
}
.fourthBlock-card-comtainer{
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    align-content: center;
    padding: 0px 269px;
}
.fourthBlock-card-pattern-title {
    display: flex;
    align-content: center;
    justify-content: left;
    align-items: center;
    text-align: left;
}
.fourthBlock-card-number__h1 {
    font-style: normal;
font-weight: 700;
font-size: 36px;
line-height: 42px;
/* identical to box height */

text-align: center;
margin: 30px 21px 30px 35px;
color: #969AF7;

}
.fourthBlock-card-title__h1 {
    font-style: normal;
font-weight: 700;
font-size: 18px;
line-height: 25px;
/* or 139% */
margin: 0;


color: #FFFFFF;

}
.fourthBlock-card-one-txt__p {
    text-align: left;
    font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 25px;
/* or 139% */
box-sizing: border-box;
    padding: 0px 28px 44px 100px;

color: #E3E3E3;
}
.fourthBlock-card-two-txt__p {
    text-align: left;
    font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 25px;
/* or 139% */
box-sizing: border-box;
    padding: 0px 50.5px 0px 98px;

color: #E3E3E3;
}
.fourthBlock-card-three-txt__p {
    text-align: left;
    font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 25px;
/* or 139% */
box-sizing: border-box;
   padding: 0px 0px 0px 102px;

color: #E3E3E3;
}
.fourthBlock-card-six-txt__p {
     text-align: left;
    font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 25px;
/* or 139% */
box-sizing: border-box;
   padding: 0px 44px 0px 102px;

color: #E3E3E3;
}
.fourthBlock-card-five-txt__p {
    text-align: left;
    font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 25px;
/* or 139% */
box-sizing: border-box;
   padding: 0px 44px 0px 102px;

color: #E3E3E3;
}
.fourthBlock-card-four-txt__p {
    text-align: left;
    font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 25px;
/* or 139% */
box-sizing: border-box;
   padding: 0px 44px 0px 102px;

color: #E3E3E3;
}
#fourthBlock-card-img-1 {
    background: url('../assets/img/fourthblockimg/frthblckcardone.svg');
    background-repeat: no-repeat;
    height: 298.5px;
}
#fourthBlock-card-img-2 {
    background: url('../assets/img/fourthblockimg/frthblckcardtwo.png');
     background-repeat: no-repeat;
     width: 442px;
    /* margin-bottom: 30px; */
    height: 298.5px;
}
#fourthBlock-card-img-3 {
    background: url('../assets/img/fourthblockimg/frthblckcardthree.png');
     background-repeat: no-repeat;
     width: 414px;
    /* margin-bottom: 30px; */
    height: 298.5px;
}
#fourthBlock-card-img-4 {
    background: url('../assets/img/fourthblockimg/frthblckcardsix.png');
     background-repeat: no-repeat;
     width: 413px;
}
#fourthBlock-card-img-5 {
    background: url('../assets/img/fourthblockimg/frthblckcardfive.png');
     background-repeat: no-repeat;
     width: 442px;
}
#fourthBlock-card-img-6 {
    background: url('../assets/img/fourthblockimg/frthblckcardfour.png');
     background-repeat: no-repeat;
     width: 441px;
}
.border-box {
    box-sizing: border-box;
   padding-left: 27px;
}
.fourthBlock-order__btn {
    width: 300px;
    height: 56px;
    background: #FFA500;
    border-radius: 10px;
    font-family: FuturaBookC;
font-style: normal;
font-weight: 400;
font-size: 22px;
    line-height: 57px;
/* identical to box height, or 106% */

text-align: center;
border: none;
color: #FFFFFF;
margin-top: 48px;
}

@media (max-width: 1440px) {
.fourthBlock-card-comtainer{
    padding: 0px
}
}
</style>