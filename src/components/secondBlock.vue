<template>
  <div class="second-block__container">
    <h1 class="second-block-heading__h1">Почему с нами выгодно</h1>
    <p class="second-block-heading-desc__p">С 1996 года мы занимаемся оптовыми поставками электронных компонентов от ведущих производителей из Европы<br>и Азии для Российских потребителей. </p>
    <div class="second-block-desc-cards-main__container">
        <div class="second-block-desc__card">
            <div class="desc-card__img" id="desc-card-1"></div>
            <h1 class="desc-card__h1">Качественная продукция</h1>
            <p class="desc-card__p">Все наши товары сертифицированы <br> и имеют сопроводительную <br> документацию.</p>
            <div class="desc-rectangle__img"></div>
        </div>
        <div class="second-block-desc__card">
            <div class="desc-card__img" id="desc-card-2"></div>
            <h1 class="desc-card__h1">Индивидуальный подход</h1>
            <p class="desc-card__p">Возможность изготовления <br> компонентов специально для вас <br> на заводах-изготовителя.</p>
            <div class="desc-rectangle__img"></div>
        </div>
        <div class="second-block-desc__card">
            <div class="desc-card__img" id="desc-card-3"></div>
            <h1 class="desc-card__h1">Бесплатная доставка</h1>
            <p class="desc-card__p">При наличии товара на складе и <br> заказе от 10 000 рублей, <br> доставим бесплатно по Москве и <br> СПБ в течение 2х часов.</p>
            <div class="desc-rectangle__img"></div>
        </div>
        <div class="second-block-desc__card">
            <div class="desc-card__img" id="desc-card-4"></div>
            <h1 class="desc-card__h1">Подбираем аналоги</h1>
            <p class="desc-card__p">Поможем подобрать аналоги <br> популярных европейских брендов в <br> условиях санкций.</p>
            <div class="desc-rectangle__img"></div>
        </div>
        <div class="second-block-desc__card">
            <div class="desc-card__img" id="desc-card-5"></div>
            <h1 class="desc-card__h1">Резервный запас компонентов</h1>
            <p class="desc-card__p">Хранение товара на наших <br> складах для постоянных <br> клиентов.</p>
            <div class="desc-rectangle__img"></div>
        </div>
        <div class="second-block-desc__card">
            <div class="desc-card__img" id="desc-card-6"></div>
            <h1 class="desc-card__h1">Гибкая система оплаты</h1>
            <p class="desc-card__p">Отсрочка платежей для <br> постоянных клиентов.</p>
            <div class="desc-rectangle__img"></div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.second-block__container {
 margin-top: 85px;
 margin-bottom: 130px;
}
.second-block-heading__h1 {
 font-weight: 700;
    font-size: 37px;
    line-height: 45px;
    color: #111111;
    font-family: FuturaFuturisC, Regular;
}
.second-block-heading-desc__p {
font-style: normal;
    font-weight: 400;
    font-size: 22px;
    line-height: 24px;
    margin-top: 25px;
    color: #030303;
    margin-bottom: 42px;
}
.second-block-desc-cards-main__container {
   display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 43px;
    justify-content: center;
    padding: 0px 360px;
    box-sizing: border-box;
    align-content: center;
    max-width: 1970px;
    margin: 0 auto;
}
.second-block-desc__card {
    width: 369px;
    height: 406px;
    background: #FFFFFF;
    border-radius: 10px;
    box-sizing: border-box;
    padding: 40px 32px;
    position: relative;
}
.desc-card__h1 {
    font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 23px;
text-align: center;
color: #2A336C;
margin-bottom: 15px;
}
.desc-card__p {
    font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 22px;
text-align: center;
color: #555555;
}
#desc-card-1 {
    background: url('../assets/img/firstcard.svg');
    margin: 0 auto;
    height: 163px;
    width: 157px;
    margin-bottom: 39px;
}
#desc-card-2 {
    background: url('../assets/img/secondcard.svg');
    margin: 0 auto;
    height: 163px;
    width: 157px;
    margin-bottom: 39px;
}
#desc-card-3 {
    background: url('../assets/img/thirdcard.svg');
    margin: 0 auto;
    height: 163px;
    width: 157px;
    margin-bottom: 39px;
}
#desc-card-4 {
    background: url('../assets/img/fourthcard.svg');
    margin: 0 auto;
    height: 163px;
    width: 157px;
    margin-bottom: 39px;
}
#desc-card-5 {
    background: url('../assets/img/fifthcard.svg');
    margin: 0 auto;
    height: 163px;
    width: 157px;
    margin-bottom: 39px;
}
#desc-card-6 {
    background: url('../assets/img/sixthcard.svg');
    margin: 0 auto;
    height: 163px;
    width: 157px;
    margin-bottom: 39px;
}
.desc-rectangle__img {
    background: url('../assets/img/rectangle.svg');
    position: absolute;
    width: 100%;
    height: 170px;
    right: 0;
    bottom: 0;
    margin-right: -33px;
}
@media (max-width: 1440px) {
.second-block-desc-cards-main__container {
    padding: 0px
}
}
</style>