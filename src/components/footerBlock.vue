<template>
  <div class="footer-container">
        <div class="footer-list__a">
          <div class="semitex__img"></div>
          <a>Каталог</a>
          <a>Производители</a>
          <a>Для кого работаем</a>
          <a>Серитификаты</a>
          <a>О нас</a>
          <a>FAQ</a>
          <a>Контакты</a>
        </div>
        <button class="footer-btn">ОСТАВИТЬ ЗАЯВКУ</button>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.footer-container {
  height: 177px;
    background: #333333;
    display: flex;
    justify-content: center;
    align-items: center;
}
.footer-list__a {
  display: flex;
  gap: 36px;
  margin-right: 44px;
}
.footer-btn {
  height: 56px;
    width: 261px;
    background: #969AF7;
    border-radius: 10px;
    color: white;
    font-family: 'FuturaLightC';
    font-style: normal;
    font-weight: 400;
    font-size: 22px;
}
</style>