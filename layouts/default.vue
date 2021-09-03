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
          <img src="/suavecito.png" alt="" />
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
          <span class="address"
            >Jl. Ketintang Baru IV No.17, Surabaya, Jawa Timur</span
          >
          <span class="number">+62 857-3378-4892</span>
          <div class="email-container">
            <span class="email">Email : </span>
            <span class="name"> redian@gmail.com</span>
          </div>
        </div>
        <div class="right">
          <span class="desc">SIGN UP FOR OUR NEWSLETTER</span>
        <div class="signup-container">
         <input id="" type="email" name="" required placeholder="Your Email" >
         <div class="button">
          <span class="submit"> SUBMIT</span>
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
          <span class="button">About Us</span>
          <span class="button">Our Work</span>
          <span class="button">Our Process</span>
        </div>
        <div class="right">
          <span class="desc">SERVICES</span>
          <span class="button">Custom Design</span>
          <span class="button">Screen Printing</span>
          <span class="button">Headwear</span>
          <span class="button">Cut & Sew</span>
          <span class="button">Accessories</span>
        </div>
      </div>
      <div class="social-media"></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  position: relative;
  width: 100vw;
  min-height: 100vh;
  min-height: calc((var(--vh, lvh) * 100));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  .top {
    position: fixed;
    width: 100%;
    height: 3rem;
    display: flex;
    align-items: center;
    margin-top: 2rem;
    z-index: 3000;
    .left {
      position: absolute;
      display: flex;
      flex-direction: row;
      width: 100%;
      left: 0;
      justify-content: flex-start;
      align-items: center;
      margin-left: 2.5rem;
      .dragdown {
        position: absolute;
        width: 6rem;
        height: 8rem;
        top: 2.5rem;
        left: 0.5rem;
        background: #f0eee3;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        line-height: 1.75;
        opacity: 0;
        padding-left: 1rem;
        .list {
          font-family: 'Antonio';
          font-weight: 700;
          font-size: 15px;
          cursor: pointer;
        }
      }
      span.button {
        font-family: 'Antonio';
        font-weight: 700;
        color: white;
        font-size: 18px;
        margin: 14px;
      }
    }
    .center {
      position: relative;
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      .image {
        position: absolute;
        img {
          width: 6.5rem;
          height: 5.5rem;
        }
      }
    }
    .right {
      position: absolute;
      display: flex;
      width: 6rem;
      height: 100%;
      right: 0;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      margin-right: 4rem;
      .button {
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 1.5rem;
        background-color: #b48645;
        span.button-hire {
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
  .bottom {
    position: relative;
    display: flex;
    background: #282829;
    width: 100%;
    height: 160vh;
    justify-content: flex-start;
    align-items: center;
    flex-direction: column;
    .top-section {
      position: relative;
      width: 40%;
      display: flex;
      margin-top: 8rem;
      flex-direction: row;
      justify-content: flex-start;
      align-items: flex-start;
      .left {
        position: relative;
        display: flex;
        width: 40%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        span.address {
          font-family: 'Quicksand';
          font-size: 18px;
          color: #f0eee3;
        }
        span.number {
          font-family: 'Quicksand';
          font-size: 18px;
          color: #b48645;
        }
        .email-container {
          position: relative;
          display: flex;
          justify-content: flex-start;
          padding-top: 1rem;
          align-items: flex-start;
          font-family: 'Quicksand';
          font-size: 18px;
          span.email {
            color: #f0eee3;
          }
          span.name {
            position: relative;
            display: flex;
            left: 0.4rem;
            color: #b48645;
          }
        }
      }
      .right {
        position: relative;
        display: flex;
        width: 60%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        span.desc {
          position: relative;
          font-family: 'Antonio';
          font-size: 18px;
          font-weight: 400;
          color: #f0eee3;
          display: flex;
          justify-content: flex-start;
          align-items: center;
        }
        .signup-container {
          position: relative;
          display: flex;
          width: 100%;
          height: 1.5rem;
          flex-direction: row;
          justify-content: flex-start;
          align-items: flex-start;
          input{
            position: relative;
            display: flex;
            margin-top: 0.5rem;
            height: 100%;
            width: 60%;
            background: #282829;
            border: 1px solid #b48645;
          }
          .button{
            position: relative;
            display: flex;
            width: 30%; 
            height: 100%; 
            margin-top: 0.5rem;
            margin-left: 0.5rem;
            background: #f0EEE3;
            justify-content: center;
            align-items: center;
            span.submit{
              font-family: "Antonio";
              font-size: 18px;
              color: #282829;
              font-weight: 900;
            }
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
      margin-top: 2rem;
      justify-content: flex-start;
      align-items: flex-start;
      span.desc{
        position: relative;
        color: white;
        font-family: 'Antonio';
        font-size: 5.5rem;
        font-weight: 900;
        display: flex;
      }
    }
    .bottom-section {
      position: relative;
      width: 40%;
      height: 100%;
      margin-top: 4rem;
      display: flex;
      flex-direction: row;
      justify-content: flex-start;
      align-items: flex-start;
      .left {
        position: relative;
        display: flex;
        width: 40%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        font-family: 'Quicksand';
        span.desc {
          width: 100%;
          color: white;
          font-weight: 400;
          padding-bottom: 1rem;
          font-size: 19px;
          justify-content: flex-start;
          align-items: flex-start;
        }
        span.button {
          font-weight: 400;
          font-size: 19px;
          line-height: 2;
          color: #b48645;
        }
      }
      .right {
        position: relative;
        display: flex;
        width: 40%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        font-family: 'quicksand';
        span.desc {
          width: 100%;
          color: white;
          font-weight: 400;
          padding-bottom: 1rem;
          font-size: 19px;
          justify-content: flex-start;
          align-items: flex-start;
        }
        span.button {
          font-weight: 400;
          font-size: 19px;
          line-height: 2;
          color: #b48645;
        }
      }
    }
    .social-media {
    }
  }
}
</style>

<style lang="scss">
::-webkit-scrollbar {
  display: none;
}
html,
body {
  margin: 0;
  padding: 0;
  font-size: 24px;
  overflow-x: hidden;
}
</style>