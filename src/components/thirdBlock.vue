<template>
    <div class="third-block-container"> 
       <h1 class="third-block-heading__h1">Наши производители</h1> 
       <div class="third-block-card-main-container">
         <div class="third-block__cards">
            <div id="manuf-card-1"></div>
         </div>
         <div class="third-block__cards">
            <div id="manuf-card-2"></div>
         </div>
         <div class="third-block__cards">
            <div id="manuf-card-3"></div>
         </div>
         <div class="third-block__cards">
            <div id="manuf-card-4"></div>
         </div>
         <div class="third-block__cards">
            <div id="manuf-card-5"></div>
         </div>
       </div>
       <p class="third-block__p">Lorem ipsum dolor sit amet consectetur. Non eget blandit in euismod felis id quisque nunc. Non orci lacus elit mauris velit gravida imperdiet id. Ipsum pulvinar ac ut <br> sociis. Sed magna gravida consequat et euismod aenean quis mauris. Ut etiam egestas ultrices faucibus ultrices nisl enim consequat faucibus. Nibh id leo ullamcorper <br> eleifend. Id at commodo interdum et leo. </p>
    </div>
  
</template>

<script>
export default {

}
</script>

<style>
.third-block-container {
    background: url('../assets/img/thirdblck.png');
    height: 750px;
    background-size: cover;
    background-repeat: no-repeat;
    
}
.third-block-heading__h1 {
    font-style: normal;
    font-weight: 700;
    font-size: 37px;
    /* color: #111111; */
    line-height: 45px;
    padding-top: 125px;
    margin-bottom: 57px;
}
.third-block__p {
text-align: left;
    width: 1280px;
    margin: 0 auto;
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    /* margin-left: 78px; */
    line-height: 31px;
}
.third-block__cards {
    width: 242px;
height: 174px;
background: #FFFFFF;
border-radius: 10px;
align-items: center;
    justify-content: center;
    display: flex;
}
.third-block-card-main-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 18px;
    margin-bottom: 42px;
}
#manuf-card-1 {
    background: url('../assets/img/thirdblckcard1.png');
    width: 150px;
height: 94px;
}    
#manuf-card-2 {
    background: url('../assets/img/thirdblckcard2.png');
    width: 186px;
height: 47px;
}    
#manuf-card-3 {
    background: url('../assets/img/thirdblckcard3.png');
    width: 106px;
height: 106px;
}    
#manuf-card-4 {
    background: url('../assets/img/thirdblckcard4.png');
    width: 171px;
height: 116px;
}    
#manuf-card-5 {
    background: url('../assets/img/thirdblckcard5.png');
    width: 183px;
height: 40px;
}
</style>