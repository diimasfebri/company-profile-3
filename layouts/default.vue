<template>
<div class="container">
  <div class="top">
    <div class="left">
      <div class="dragdown">
        <div class="list">CUSTOM DESIGN</div>
        <div class="list">SCREEN PRINTING</div>
        <div class="list">HEADWEAR</div>
        <div class="list">CUT & SAW</div>
        <div class="list">ACCESSORIES</div>
      </div>
        <span class="button">SERVICES</span>
        <span class="button">OUR WORK</span>
        <span class="button">OUR PROGRESS</span>
        <span class="button">ABOUT US</span>
    </div>
    <div class="center">
        <div class="image">
          <img src="/suavecito.png" alt="">
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
         <span class="name"> redian@gmail.com</span>
       </div>
     </div>
     <div class="right">
       <span class="desc">SIGN UP FOR OUR NEWSLETTER</span>
       <div class="signup-container">
          <input  value="your email" class="sign-up">
            <span>Your-email</span>
          <input>
          <div class="submit">
            <span>SUBMIT</span>
          </div>
       </div>
     </div>
    </div>
   <div class="center-section">
     <span class="desc">SOME MORE INFO, AKA THE FOOTER</span>
   </div>
   <div class="bottom-section">
     <div class="left">
      <span class="desc">SITE</span>
      <span class="button">ABOUT US</span>
      <span class="button">OUR WORK</span>
      <span class="button">OUR PROCESS</span>
     </div>
     <div class="right">
       <span class="desc">SERVICES</span>
       <span class="button">CUSTOM DESIGN</span>
      <span class="button">SCREEN PRINTING</span>
      <span class="button">HEADWEAR</span>
      <span class="button">CUT AND SEW</span>
      <span class="button">ACCESSORIES</span>
     </div>
    </div> 
   <div class="social-media">
    </div>
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
    align-items: center;
    margin-top: 2rem;
    z-index:3000;
    .left{
      position: absolute;
      display: flex;
      flex-direction: row;
      width: 100%;
      left: 0;
      justify-content: flex-start;
      align-items: center;
      margin-left: 2.5rem;
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
          .list{
            font-family: 'Antonio';
            font-weight: 700;
            font-size: 15px;
          }
      }
      span.button{
        font-family: 'Antonio';
        font-weight: 700;
        color: white;
        font-size: 18px;
        margin: 14px;
      }
    }
    .center{
      position: relative;
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      .image{
        position: absolute;
        img{
          width: 6.5rem;
          height: 5.5rem;
        }
      }
    }
    .right{
      position: absolute;
      display: flex;
      width: 6rem;
      height: 100%;
      right: 0;
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
          width: 4rem;
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
    height: 140vh;
    justify-content: flex-start;
    align-items: center;
    flex-direction: column;
    .top-section{ 
      position: relative;
      width: 40%;
      height: 100%;
      display: flex;
      top: 5rem;
      flex-direction: row;
      justify-content: flex-start;
      align-items: flex-start;
      .left{
        position: relative;
        display: flex;
        width: 40%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
          span.address{
          font-family: "Quicksand";
          font-size: 18px;
          color: #f0EEE3;
          }
          span.number{
          font-family: "Quicksand";
          font-size: 18px;
          color: #B48645;
          }
          .email-container{
            position: relative;
            display: flex;
            justify-content: flex-start;
            padding-top: 1rem;
            align-items: flex-start;
            font-family: 'Quicksand';
            font-size: 18px;
            span.email{
            color: #f0EEE3;
            }
            span.name {
            position: relative;
            display: flex;
            left: 0.4rem;
            color: #b48645;
            }
          }
      }
      .right{
        position: relative;
        display: flex;
        width: 60%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        span.desc{
          position: relative;
          font-family: "Antonio";
          font-size: 18px;
          font-weight: 400;
          color: #f0EEE3;
          display: flex;
          justify-content: flex-start;
          align-items: center;
        }
        .signup-container{
          position: relative;
          display: flex;
          width: 100%;
          flex-direction: row;
          justify-content: flex-start;
          align-items: flex-start;
          input.sign-up{
            position: relative;
            display: flex;
            width: 100%;
            height: 100%;
            border: 1px solid black;
            background: #282829;
          }
        }
      }
    }
    .center-section{
      position: relative;
      display: flex;
      background: #282829;
      width: 40%;
      height: 100%;
      justify-content: flex-start;
      align-items: flex-start; 
      span.desc{
        position: relative;
        color: white;
        font-family: "Antonio";
        font-size: 5.5rem;
        font-weight: 600;
        display: flex;
      }     
    }
    .bottom-section{
      position: relative;
      display: flex;
      width: 100%;
      justify-content: flex-start;
      align-items: center;
      flex-direction: column;
      .left{
        position: relative;
        display: flex;
        width: 40%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        span.desc{
         position: relative;
         display: flex;
         width: 100%;
         color: #B48645;
         justify-content: flex-start;
         align-items: flex-start;
        }
        span.button{
          font-family: "Quicksand";
          font-size: 1.5rem;
          color: white;
        }
      }
      .right{
        position: relative;
        display: flex;
        width: 40%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        span.desc{
          position: relative;
          display: flex;
          width: 100%;
          color: #B48645;
          justify-content: flex-start;
          align-items: flex-start;
        }
        span.button{
          font-family: "Quicksand";
          font-size: 1rem;
          color: white;
        }
      }
    }
    .social-media{
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
