<template>
    <div>
        <div class="fifth-block-trans-div">
                <div class="one-click-block__div" v-on:click="show = !show" :class="{ 'two-click-block__div': show }">
                    <h2 class="first-txt__h2" :class="{ 'txt-color': show }">{{data.title}}</h2>
                    <div class="one-click-block__img" :class="{ 'img-change': show }"></div>
                </div>
                <transition name="fifth-block-fade">
                    <div class="trans-text-container" v-if="show">    
                        <p class="trans-txt__p" v-if="show" v-html="data.text"></p>
                    </div>
                </transition>
        </div>
    </div>
</template>

<script>
export default {
    props: [
        'data'
    ],
    data() {
    return {
        show: false,
    }
  },
  computed: {
      className() {
         if(this.show == false) {
            return 'one-click-block__div'
         } else {
            return 'two-click-block__div'
         }
      },
    }
}
</script>

<style>
.fifth-block-trans-div{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.one-click-block__div{
    border-radius: 10px;
    width: 1280px;
    height: 87px;
    margin: 0;
    display: flex;
    align-items: center;
    z-index: 1;
    transition: all 3s ease;
}
.one-click-block__div {
    background: linear-gradient(180deg, #FFFFFF 50.57%, #BDC0FF 100%);
    box-shadow: 0px 0px 50px -10px rgb(22 126 194 / 20%);
}
.two-click-block__div {
    background: linear-gradient(180deg, #969AF7 0%, #686EEC 100%);
}
.one-click-block__img,.one-click-block__img{
    width: 40px;
    height: 40px;
    background-repeat: no-repeat !important;
    margin-left: 564px;
}
.one-click-block__img {
    background: url('../assets/img/fifthblockimg/elipse.svg');
}
.first-txt__h2 {
    margin: 0 0 0 53px;
    
}
.trans-text-container {
    text-align: left;
    background: #FFFFFF;
    border: 1px solid #167EC2;
    border-radius: 10px; 
    width: 1280px;
    height: 522px;
    z-index: 0;
    margin-top: -87px;
    box-sizing: border-box;
    padding: 124px 53px 45px;
}
.trans-txt__p {
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 27px;
    color: #333333;
}
.txt-color {
    color: white;
}
.img-change {
    background: url('../assets/img/fifthblockimg/elipsetwo.svg');
}
</style>