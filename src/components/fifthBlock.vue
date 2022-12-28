<template>
  <div class="fifth-block-container">
    <h1 class="fifth-block-heading__h1">Ответы на самые популярные вопросы в сфере</h1>
    <div class="fifth-block-flex-div">
        <div class="fifth-block-trans-btn-main-container" v-for="item,index in stockList" :key="index">
             <fifthBlockChild :data="item"/> 
        </div>
    </div>
  </div>
</template>

<script>

import fifthBlockChild from '../components/fifthBlockChild.vue'

export default {

    components: {
        fifthBlockChild,
    },
    data() {
    return {
     stockList: [
        { title: "Lorem ipsum dolor sit amet consectetur. Ultrices aliquam.", 
          text: "Like the phrase “stem cell” itself, “stem cell therapy” is often used to describe a variety of different medical therapies that utilize stem cells in some form to treat a patient. Sometimes the term is used incorrectly to refer to platelet rich plasma (PRP) injections. The term is also used to refer to stem cell transplants, also known as bone marrow transplants. <br><br/> Most commonly “stem cell therapy” is used to describe a procedure where the patient’s adult stem cells and other potentially regenerative cells are harvested from a tissue sample of either fat or bone marrow taken from the patient. These concentrated regenerative cells are then used to treat specific injuries typically by injecting them into the afflicted area. It should be said that this type of stem cell therapy is currently not FDA approved and clinics performing it illegally in the US or in other countries perform various versions of the procedure to treat illnesses and injuries with little to no clinical evidence.<br><br/>At InGeneron we use the term “regenerative cell therapy” since there are many different cell types and regenerative properties collected and used by our therapy along with adult stem cells. Importantly we do not treat patients outside of our approved clinical trials and we are dedicated to securing FDA approval through rigorous clinical testing.",  
        },
        { title: "Lorem ipsum dolor sit amet consectetur. Ultrices aliquam.", 
          text: "Like the phrase “stem cell” itself, “stem cell therapy” is often used to describe a variety of different medical therapies that utilize stem cells in some form to treat a patient. Sometimes the term is used incorrectly to refer to platelet rich plasma (PRP) injections. The term is also used to refer to stem cell transplants, also known as bone marrow transplants. <br><br/> Most commonly “stem cell therapy” is used to describe a procedure where the patient’s adult stem cells and other potentially regenerative cells are harvested from a tissue sample of either fat or bone marrow taken from the patient. These concentrated regenerative cells are then used to treat specific injuries typically by injecting them into the afflicted area. It should be said that this type of stem cell therapy is currently not FDA approved and clinics performing it illegally in the US or in other countries perform various versions of the procedure to treat illnesses and injuries with little to no clinical evidence.<br><br/>At InGeneron we use the term “regenerative cell therapy” since there are many different cell types and regenerative properties collected and used by our therapy along with adult stem cells. Importantly we do not treat patients outside of our approved clinical trials and we are dedicated to securing FDA approval through rigorous clinical testing.",  
        },
        { title: "Lorem ipsum dolor sit amet consectetur. Ultrices aliquam.", 
          text: "Like the phrase “stem cell” itself, “stem cell therapy” is often used to describe a variety of different medical therapies that utilize stem cells in some form to treat a patient. Sometimes the term is used incorrectly to refer to platelet rich plasma (PRP) injections. The term is also used to refer to stem cell transplants, also known as bone marrow transplants. <br><br/> Most commonly “stem cell therapy” is used to describe a procedure where the patient’s adult stem cells and other potentially regenerative cells are harvested from a tissue sample of either fat or bone marrow taken from the patient. These concentrated regenerative cells are then used to treat specific injuries typically by injecting them into the afflicted area. It should be said that this type of stem cell therapy is currently not FDA approved and clinics performing it illegally in the US or in other countries perform various versions of the procedure to treat illnesses and injuries with little to no clinical evidence.<br><br/>At InGeneron we use the term “regenerative cell therapy” since there are many different cell types and regenerative properties collected and used by our therapy along with adult stem cells. Importantly we do not treat patients outside of our approved clinical trials and we are dedicated to securing FDA approval through rigorous clinical testing.",  
        },
        { title: "Lorem ipsum dolor sit amet consectetur. Ultrices aliquam.", 
          text: "Like the phrase “stem cell” itself, “stem cell therapy” is often used to describe a variety of different medical therapies that utilize stem cells in some form to treat a patient. Sometimes the term is used incorrectly to refer to platelet rich plasma (PRP) injections. The term is also used to refer to stem cell transplants, also known as bone marrow transplants. <br><br/> Most commonly “stem cell therapy” is used to describe a procedure where the patient’s adult stem cells and other potentially regenerative cells are harvested from a tissue sample of either fat or bone marrow taken from the patient. These concentrated regenerative cells are then used to treat specific injuries typically by injecting them into the afflicted area. It should be said that this type of stem cell therapy is currently not FDA approved and clinics performing it illegally in the US or in other countries perform various versions of the procedure to treat illnesses and injuries with little to no clinical evidence.<br><br/>At InGeneron we use the term “regenerative cell therapy” since there are many different cell types and regenerative properties collected and used by our therapy along with adult stem cells. Importantly we do not treat patients outside of our approved clinical trials and we are dedicated to securing FDA approval through rigorous clinical testing.",  
        },
        { title: "Lorem ipsum dolor sit amet consectetur. Ultrices aliquam.", 
          text: "Like the phrase “stem cell” itself, “stem cell therapy” is often used to describe a variety of different medical therapies that utilize stem cells in some form to treat a patient. Sometimes the term is used incorrectly to refer to platelet rich plasma (PRP) injections. The term is also used to refer to stem cell transplants, also known as bone marrow transplants. <br><br/> Most commonly “stem cell therapy” is used to describe a procedure where the patient’s adult stem cells and other potentially regenerative cells are harvested from a tissue sample of either fat or bone marrow taken from the patient. These concentrated regenerative cells are then used to treat specific injuries typically by injecting them into the afflicted area. It should be said that this type of stem cell therapy is currently not FDA approved and clinics performing it illegally in the US or in other countries perform various versions of the procedure to treat illnesses and injuries with little to no clinical evidence.<br><br/>At InGeneron we use the term “regenerative cell therapy” since there are many different cell types and regenerative properties collected and used by our therapy along with adult stem cells. Importantly we do not treat patients outside of our approved clinical trials and we are dedicated to securing FDA approval through rigorous clinical testing.",  
        }
      ]
    }
  }
}
</script>

<style>
.fifth-block-container {
    background: url(/img/fifthblckback.ec3ef24f.png);
    background-size: cover;
    background-repeat: no-repeat;
    height: 1271px;
    margin-top: -55px;
}
.fifth-block-heading__h1 {
    padding-top: 150px;
    font-style: normal;
    font-weight: 700;
    font-size: 39px;
    line-height: 45px;
    padding-bottom: 40px;
    color: black;
}
.fifth-block-flex-div {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    gap: 25px;
}
</style>