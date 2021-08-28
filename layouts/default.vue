<template>
<div class="container">
 <div class="top">
    <div class="left">
<<<<<<< HEAD
=======
      <div class="dragdown" @click="opacity=1">
        <div class="list">ALL</div>
        <div class="list">CUSTOM DESIGN</div>
        <div class="list">SCREEN PRINTING</div>
        <div class="list">HEADWEAR</div>
        <div class="list">CUT & SAW</div>
        <div class="list">ACCESSORIES</div>
      </div>
>>>>>>> 7415f256b78d8fdb63a22b67060cbd2e985a5345
      <span class="button">SERVICES</span>
      <span class="button">OUR WORK</span>
      <span class="button">OUR PROCESS</span>
      <span class="button">ABOUT US</span>
    </div>
    <div class="center">
      <div class="image">
        <img src="https://cdn.shopify.com/s/files/1/0274/1389/files/suavecito-logo-full.png?height=628&pad_color=fff&v=1568385277&width=1200" alt="">
      </div>
    </div>
    <div class="right">
      <div class="button">
        <span class="button-hire"> HIRE US</span>
      </div>
    </div>
 </div>
 <nuxt />
 <div class="bottom">
   <div class="top-section">
     <div class="left">
       <span class="address">Jl. Ketintang Baru IV No.17, Surabaya, Jawa Timur</span>
       <span class="number">+62 857-3378-4892</span>
       <div class="email-container">
         <span class="email">Email : </span>
         <span class="name">redian@gmail.com</span>
       </div>

     </div>
     <div class="right">
       <div class="sign-up">
         <span>SIGN UP FOR OUR NEWSLETTER</span>
       </div>
       <div class="submit">
         <!-- <input type="email"> -->
       </div>
     </div>
   </div>
   <div class="center-section">
     <span> TEST</span>
   </div>
   <div class="bottom-section">
     <div class="left">
      <span class="button">ABOUT US</span>
      <span class="button">OUR WORK</span>
      <span class="button">OUR PROCESS</span>
     </div>
     <div class="right">
       <span class="button">CUSTOM DESIGN</span>
      <span class="button">SCREEN PRINTING</span>
      <span class="button">HEADWEAR</span>
      <span class="button">CUT AND SEW</span>
      <span class="button">ACCESSORIES</span>
     </div>
   </div>
   <div class="social-media"></div>
 </div>
</div> 
</template>



<style lang="scss" scoped>
.container{
  position: relative;
  width: 100vw;
  min-height: 100vh;
  min-height: calc((var(--vh, lvh) *100));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  .top{
    position: fixed;
    width: 100%;
    height: 3rem;
    display: flex;
    color:red; 
    margin-top: 2rem;
    z-index:3000;
    .left{
      position: relative;
      display: flex;
      flex-direction: row;
      width: 100%;
      justify-content: flex-start;
      align-items: center;
      margin-left: 2.5rem;
<<<<<<< HEAD
=======
      .dragdown{
          position: absolute;
          width: 6rem;
          height: 8rem;
          top: 2.5rem;
          left: 0.5rem;
          background: #f0EEE3;
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: flex-start;
          line-height: 1.75;
          padding-left: 1rem;
          opacity: 0;
          .list{
            font-family: 'Antonio';
            font-weight: 700;
            font-size: 15px;
          }
      }
>>>>>>> 7415f256b78d8fdb63a22b67060cbd2e985a5345
      span.button{
        font-family: 'Antonio';
        font-weight: 700;
        color: black;
        font-size: 18px;
        margin: 14px;
      }
    }
    .center{
      position: relative;
      width: 100%;
      display: flex;
      right: 9rem;
      justify-content: center;
      align-items: center;
      .image{
        position: absolute;
        img{
          width: 5.5rem;
          height: 2.5rem;
        }
      }
    }
    .right{
      position: relative;
      display: flex;
      width: 6rem;
      height: 100%;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      margin-right: 4rem;
      .button{
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 1.5rem;
        background-color: #b48645;
        span.button-hire{
          position: relative;
          width: 3rem;
          height: 1rem;
          color: white;
          font-family: Antonio;
          font-size: 18px;
          font-weight: 700;
          display: flex;
          justify-content: center;
          align-items: center;
        }
      }
    }
    
  }
  .bottom{
    position: relative;
    display: flex;
    background: #282829;
    width: 100%;
    height: 110vh; 
    justify-content: flex-start;
    align-items: center;
    flex-direction: column;
    .top-section{ 
      position: relative;
      top: 2rem;
      width: 40%;
      display: flex;
      flex-direction: row;
      justify-content: flex-start;
      align-items: center;
      .left{
        position: relative;
        display: flex;
        width: 100%;
        justify-content: flex-start;
        align-items: flex-start;
        span.address{
        font-family: "Quicksand";
        font-size: 1rem;

        }
      }
    }
    .center-section{

    }
    .bottom-section{
      .left{
        position: relative;
        display: flex;
        width: 100%;
        justify-content: flex-start;
        align-items: flex-start;
        span.button{
           font-family: "Quicksand";
           font-size: 1rem;
        }
      }
      .right{
        position: relative;
        display: flex;
        width: 100%;
        justify-content: flex-start;
        align-items: flex-start;
        span.button{
          font-family: "Quicksand";
          font-size: 1rem;
        }
      }
    }
  }
}

</style>




<style lang="scss">
::-webkit-scrollbar {
  display: none;
}
html, body {
  margin: 0;
  padding: 0;
  font-size: 24px;
  overflow-x: hidden;
}
</style>