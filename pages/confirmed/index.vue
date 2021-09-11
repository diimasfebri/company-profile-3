<template>
<div class="body-container"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1547907647-2061eca5a0bf?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=686&q=80">
  <div class="massage-button">
      <img src="icons8-ok.svg" alt="">
      <span class="desc">Submission Received</span>
  </div>
  <div class="desc-container">
    <span class="desc-1"> WELCOME TO THE BROSHIP </span>
    <span class="desc-2"> Got your submission, love your style. We'll follow up shortly with next steps, thanks for your interest in Anderson Brothers Design & Supply!</span>
    </div>  
    <div class="button-container" @click="$router.push('/')">
    <span class="desc-3">BACK TO HOME</span>
    </div>
  </div>
</div>
</template>

<style lang="scss" scoped>
.body-container{
  position: relative;
  width: 100vw;
  min-height: 100vh;
  min-height: calc((var(--vh, 1vh) * 100));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
.slide-one{
  position: relative;
  width: 100vw;
  height: 150vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
   img.bg-content{
      position: absolute;
      width: 100vw;
      height: 150vh;
    }
    .massage-button{
        cursor: pointer;
        position: relative;
        display: flex;
        width: 12rem;
        height: 5rem;
        background: transparent;
        border: 2px solid #b48645;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        img{
          width: 1.5rem;
          height: 1.5rem;
          border-radius: 100%;
          background: #b48645;
          color: #b48645;
        }
        span.desc{
        position: relative;
        display: flex;
        margin-top: 0.5rem;
        font-family: 'Quicksand';
        font-size: 0.8rem;
        font-weight: 500;
        color: white;
        }
    }
    .desc-container{
        position: relative;
        display: flex;
        width: 100%;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        line-height: 1.5;
        margin-top: 1.5rem;
        span.desc-1{
         color: white;
         font-family: 'Antonio';
         font-size: 5rem;
         width: 50%;
         font-weight: 900;
         text-align: center;
    }
        span.desc-2{
        color: white;
        font-family: 'Quicksand';
        font-size: 20px;
        width: 50%;
        margin-top: 1rem;
        font-weight: 400;
        text-align: center;
    }
    }
    .button-container{
        position: relative;
        display: flex;
        cursor: pointer;
        width: 9.5rem;
        margin-top: 2rem;
        height: 1.8rem;
        background: #b48645;
        span.desc-3{
         width: 100%;
         align-items: center;
         justify-content: center;
         height: 100%;
         text-align: center;
         font-family: Antonio;
         font-size: 0.8rem;
         margin-top: 0.4rem;
         font-weight: 900;
         color: white;
        }
         &:hover{
         background: #282829;
        }
    }
}
 } 
</style>