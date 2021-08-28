<template>
<div class="container">
 <div class="top">
    <div class="left">
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
       <div class="address">
         <span>Jl. Ketintang Baru IV No.17, Surabaya, Jawa Timur</span>
       </div>
       <div class="number">
         <span>+62 857-3378-4892</span>
       </div>
       <div class="email">
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
  height: 100vh;
  display: flex;
  justify-content: flex-start;
  .top{
    position: relative;
    width: 100%;
    height: 3rem;
    display: flex;
    color:red; 
    margin-top: 2rem;
    .left{
      position: relative;
      display: flex;
      flex-direction: row;
      width: 100%;
      justify-content: flex-start;
      align-items: center;
      margin-left: 2.5rem;
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

    width: 100%;
    height: 120%;
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