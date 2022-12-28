<template>
  <div class="home">
    <div class="header-block">
      <div class="header-block-main-container">
        <div class="header-block-list__a">
          <div class="semitex__img"></div>
          <a>Каталог</a>
          <a>Производители</a>
          <a>Для кого работаем</a>
          <a>Серитификаты</a>
          <a>О нас</a>
          <a>FAQ</a>
          <a>Контакты</a>
          <a class="semitex-num__img">+7 (812) <span class="smitex-num__span">313-58-45</span></a>
          
        </div>
        <div class="header-block-container">
          <div class="header-block-container-flex">
            <div class="header-block-title">
              <h1 class="header-block-first-title__h1">Оптовые поставки </h1>
                <h2 class="header-block-title-span__h2">электронных компонентов</h2>
                <h1 class="header-block-title__h1"> ИЗ КИТАЯ день в день</h1>
            </div>
            <div class="header-block-desc">
              <a class="header-block-desc__a">Комплексные поставки электронных компонентов и оборудования. Подберем аналоги популярных брендов из Европы в условиях санкций.</a>
            </div>
            <div class="header-block-benefits-container">
              <p class="header-block-benefits__p">Отсрочка платежей для постоянных клиентов</p>
              <p class="header-block-benefits__p">Бесплатная доставка по Москве и СПБ в течение 2х часов</p>
              <p class="header-block-benefits__p">Квалифицированный персональный менеджер</p>
            </div>
          </div> 
          <div class="callback-card__div">
            <div class="callback-card-container">
              <h1 class="callback-txt__h">ЗАКАЖИТЕ<br>ОБРАТНЫЙ ЗВОНОК</h1> 
                <div class="callback-name-number__container">
                    <div class="callback-email__container">
                    <p class="callback-email-txt__p">Ваше имя*</p>
                    <input class="callback__input" type="text" placeholder="Петров Петр">
                  </div>
                  <div class="callback-number__container">
                    <p class="callback-number-txt__p">Ваш номер*</p> 
                    <masked-input v-model="phone" class="callback__input" mask="\+\7 (111) 1111-11" placeholder="+7 (_ _ _) _ _ _-_ _-_ _" />
                  </div>
                </div>
            <button class="callback-phonecall__btn">Заказать звонок</button>
            <div class="callback-conf__div">
              <a class="callback-conf__a">Мы гарантируем конфиденциальность данных</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <secondBlock/>
  <thirdBlock/>
  <fourthBlock/>
  <fifthBlock/>
  <footerBlock/>
</div>
</template>

<script>
import MaskedInput from 'vue-masked-input'
import secondBlock from '../components/secondBlock.vue'
import thirdBlock from '../components/thirdBlock.vue'
import fourthBlock from '../components/fourthBlock.vue'
import fifthBlock from '../components/fifthBlock.vue'
import footerBlock from '../components/footerBlock.vue'

export default {
  name: 'Home',
  components: {
    MaskedInput,
    secondBlock,
    thirdBlock,
    fourthBlock,
    fifthBlock,
    footerBlock,
  },
  data() {
    return {
     phone:"",
    }
  }
}
</script>

<style>
.header-block {
  background: url('../assets/img/header.png');
  width: 100%;
  height: 850px;
  background-repeat: no-repeat;
    background-size: cover;
    background-position: bottom;
  }
.header-block-list__a {
  width: 1281px;
  height: 33px;
  display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 0 auto;
}
.semitex__img {
  background: url('../assets/img/semitex.png');
  width: 155px;
  height: 28px;
  background-repeat: no-repeat;

}
.semitex-num__img {
 padding-left: 55px;
 font-weight: 400;
 font-family:FuturaFuturisC;
 
}
.semitex-num__img::before {
  content: "";
  background: url('../assets/img/phone.png');
  width: 33px;
  height: 33px;
   background-repeat: no-repeat;
   margin-left: -40px;
   position: absolute;
}
.header-block-main-container {
  padding-top: 50px;
  box-sizing: border-box;
}
.smitex-num__span {
  font-weight: 700;
  font-family: FuturaFuturisC;
  margin-left: 5px;
}
.header-block-desc__a {
  font-family: FuturaBookC;
font-style: normal;
font-weight: 400;
font-size: 23px;
line-height: 30px;
color: #969AF7;
}
.header-block-container {
  margin: 0 auto;
    display: flex;
    width: 1281px;
}
.header-block-container-flex {
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
  align-items: flex-start;
  width: 847px;
  height: 470px;
  margin-top: 112px;
  margin-right: 53px;
}
.header-block-title__h1{
font-size: 62.23px;
}
.header-block-first-title__h1 {
text-align: left;
font-size: 70.23px;
}
.header-block-desc__a {
  text-align: left;
  margin: 10px 0 37px 0;
}
.header-block-benefits-container {
  text-align: left;
  height: 150px;
    width: 830px;
    /* text-align: left; */
    box-sizing: border-box;
    padding: 18px;
    background: linear-gradient(90deg, rgb(150 154 247 / 30%) 1.34%, rgba(150, 154, 247, 0) 96.66%);
    /* opacity: 0.3; */
    border-radius: 10px;
}
.header-block-title-span__h2 {
  color: #969AF7;
  /* font-size: 95px; */
  font-weight: 700;
  font-size: 57.23px;
  font-family: FuturaFuturisC;
  line-height: 69px;
  margin: 0 0 5px 0;
    text-align: left;
}
.header-block-benefits__p {
  margin-top: 5px;
    margin-left: 60px;
}
.header-block-benefits__p::before {
  content: "";
    background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAALCAYAAABPhbxiAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAEdSURBVHgBlZAxTsNAEEVnNsGREEEcgGJbCiSHAqW0S8rUFJAjcILYN+AGhAsgqCjdgQRFXCAF0UBHiSES6yVef9aWMAZhkfxm5+/ozegP0xLyFKTTooiYxrww9AIpBCJmSGufFgK9Z0iIvIJopeX/C3qP2DBiPrGlhTgxLfhXm04s+lMl+1M9aoL0xzzKUpJGU5JqXUJFr52nbMPmcnei6abXCevge6KLQ7ilAQ9ve2vxV09kqTk1isi+wc61qjbb+sSkcI0CQWFoh57Xh5YZ3WgWAGJUOOQUsLB5QIdcdvko9lePf8eojrN9+TYG+OD7C0UZ3u11A/pDP666dTaLAPLYQhAc3A+6ITWoXTfqNRs4HRFZ7uJhf70RKvQJfBR6gH9uniIAAAAASUVORK5CYII=);
    height: 11px;
    width: 14px;
    position: absolute;
    margin-left: -40px;
    margin-top: 8px;
    background-repeat: no-repeat;
} 



.callback-card__div {
  margin-top: 112px;
  height: 473px;
  width: 380px;
  background: #FFFFFF;
  border-radius: 10px;
}

.callback-card-container {

}
.callback-txt__h {
  margin: 0;
    background: linear-gradient(180deg, #6A32B4 0%, #552693 100%);
    height: 110px;
    font-weight: 700;
    font-size: 23px;
    line-height: 27px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 10px 10px 0px 0px;
}
.callback-number-txt__p{
  font-weight: 400;
font-size: 18px;
color: #626366;
font-family: FuturaBookC;
text-align: left;
    margin-left: 60px;
}
.callback-email-txt__p{
  font-family: FuturaBookC;
  font-weight: 400;
  font-size: 18px;
  color: #626366;
  text-align: left;
  margin-left: 60px;
}
.callback__input {
  background: #F5F3FF;
    box-shadow: inset 1px 1px 3px rgb(0 0 0 / 10%);
    border-radius: 10px;
    width: 300px;
    height: 56px;
    font-family: FuturaBookC;
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 26px;
    border: 0;
    box-sizing: border-box;
    padding: 20px;
}
.callback__input::placeholder {
  color: #BCBFC4;
}
.callback-name-number__container {
  margin-top: 30px
}
.callback-number__container{
  margin-top: 5px;
}
.callback-crte-acc__a {
  font-family: FuturaBookC;
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 16px;
color: #C0C0C0;
display: flex;
    justify-content: center;
    align-items: center;
}
.header-block-title {
  margin: 0;
    text-align: left;
}
.callback-phonecall__btn {
  width: 300px;
    height: 56px;
    font-family: FuturaFuturisC;
    font-style: normal;
    font-weight: 100;
    font-size: 18px;
    line-height: 19px;
    background: #FFA500;
    border-radius: 10px;
    border: 0;
    margin-top: 34px;
    color: #FFFFFF;
}
.callback-conf__div{
  display: flex;
    justify-content: center;
    align-items: center;
}
.callback-conf__a {
  margin-top: 17px;
  color: #C0C0C0;
    font-family: FuturaBookC;
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 16px;
}
.callback-conf__a::before {
  content: "";
  background: url('../assets/img/lock.svg');
  width: 16px;
  height: 16px;
   background-repeat: no-repeat;
   margin-left: -22px;
   position: absolute;
}
@media (max-width: 414px) {
.header-block {
  width: 1280px;
  height: 1500px;
}
.header-block-container {
    margin: 0 auto;
    display: flex;
    width: 1281px;
    flex-direction: column;
}
.second-block__container {
  width: 1280px;
}
.second-block-desc-cards-main__container {
  padding: 0px 40px;
}
.third-block-container {
  height: 1000px;
  width: 1280px;
}
.fourthBlock-container {
  height: 1098px;
  width: 1280px;
}
}
</style>
