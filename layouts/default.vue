<template>
  <div class="container" >
    <div class="top">
      <div class="left">
        <div ref="drop" class="dropdown">
          <div class="list" @click="$router.push('/services/all')" >ALL</div>
          <div class="list" @click="$router.push('/services/customdesign')" >CUSTOM DESIGN</div>
          <div class="list" @click="$router.push('/services/screenprinting')">SCREEN PRINTING</div>
          <div class="list" @click="$router.push('/services/headwer')">HEADWEAR</div>
          <div class="list" @click="$router.push('/services/cutsew')">CUT & SAW</div>
          <div class="list" @click="$router.push('/services/accessories')">ACCESSORIES</div>
        </div>
        <span class="button"  @click="openDropdown" >SERVICES</span>
        <span class="button"  @click="$router.push('/work')">OUR WORK</span>
        <span class="button"  @click="$router.push('/process')">OUR PROCESS</span>
        <span class="button"  @click="$router.push('/about')">ABOUT US</span>
      </div>
      <div class="center">
        <div class="image" @click="$router.push('/')">
          <img src="/suavecito.png" alt="" />
        </div>
      </div>
      <div class="right">
        <div class="button" @click="$router.push('/contact')">
          <span class="button-hire"> HIRE US</span>
        </div>
      </div>
    </div>
    <nuxt  />
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
         <input type="email" name="" required placeholder="Your Email" >
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
          <span class="button" @click="$router.push('/about')">About Us</span>
          <span class="button" @click="$router.push('/work')">Our Work</span>
          <span class="button" @click="$router.push('/process')">Our Process</span>
        </div>
        <div class="right">
          <span class="desc">SERVICES</span>
          <span class="button" @click="$router.push('/services/customdesign')">Custom Design</span>
          <span class="button" @click="$router.push('/services/screenprinting')">Screen Printing</span>
          <span class="button" @click="$router.push('/services/headwer')">Headwear</span>
          <span class="button" @click="$router.push('/services/cutsew')">Cut & Sew</span>
          <span class="button" @click="$router.push('/services/accessories')">Accessories</span>
        </div>
      </div>
      <div class="social-media">
        <div class="img-container">
          <img src="/suavecito.png" alt="" />
        </div>
        <div class="item-container">
            <div class="circle">
                <img class="test" src="data:image/png;base64,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">
            </div>
            <div class="circle-2">
            <img src="https://www.citypng.com/public/uploads/preview/-11595327237ulqckjabpb.png">
            </div>
            <div class="circle-3">
              <img src="https://img.flaticon.com/icons/png/512/1384/1384031.png?size=1200x630f&pad=10,10,10,10&ext=png&bg=FFFFFFFF">
            </div>
    </div>
  </div>
  </div>
</div>
</template>

<script>
import gsap from 'gsap'


export default {
  methods: {
    openDropdown(){
      const {
        $refs: {
         drop,
        }
      } = this
       const tl = gsap.timeline({
        onComplete() {
          tl.to(drop, {
            display: 'flex',
            duration: 0
          })
        }
      })

    }
  }
}
</script>

<style lang="scss" scoped>
.container {
  position: relative;
  width: 100vw;
  min-height: 100vh;
  min-height: calc((var(--vh, 1vh) * 100));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  overflow-y: auto;
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
      .dropdown {
        position: absolute;
        width: 6rem;
        height: 8rem;
        top: 2.5rem;
        left: 0.5rem;
        background: #f0eee3;
        display: none;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        line-height: 1.75;
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
        cursor: pointer;
        color: white;
        font-size: 18px;
        margin: 14px;
        width: auto;
        
        &:hover{
          border-bottom: 2px solid #b48645;
        }
      }
    }
    .center {
      position: relative;
      width: 100%;
      cursor: pointer;
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
        cursor: pointer;
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
        &:hover{
          background: #16191a;
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
      flex-direction: row;
      align-items: flex-start;
      display: flex;
      width: 80%;
      height: 100%;
      justify-content:space-between;
      position: relative;
      .img-container{
      flex-direction: column;
      align-items: flex-start;
      display: flex-start;
      justify-content: flex-start;
      position: relative;
      img{
        width: 6.5rem;
        height: 5.5rem;
      }
      }
      .item-container{
        display: flex;
        position: relative;
        flex-direction: row;
        width: 15rem;
        justify-content: space-between;
        align-items: space-between;
        .circle{
        width: 3rem;
        height: 3rem;
        border-radius: 100%;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        background:#f0eee3;
        img.test{
          justify-content: center;
          align-items: center;
          margin-top: 0.5rem;
          margin-left: 0.5rem;
          width: 2rem;
          height: 2rem;
        }
        
        &.active{
          background: #b48645
        }
      }
        .circle-2{
        width: 3rem;
        height: 3rem;
        border-radius: 100%;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        background:#f0eee3;
        img{
         justify-content: center;
          align-items: center;
          margin-top: 0.5rem;
          margin-left: 0.5rem;
          width: 2rem;
          height: 2rem;
        }
         &.active{
          background: #b48645
        }
        }
        .circle-3{
        width: 3rem;
        height: 3rem;
        border-radius: 100%;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        background:#f0eee3;
        img{
          justify-content: center;
          align-items: center;
          margin-top: 0.5rem;
          margin-left: 0.5rem;
          width: 2rem;
          height: 2rem;
          object-fit: cover;
        }
         &.active{
          background: #b48645
        }
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
html,
body {
  margin: 0;
  padding: 0;
  font-size: 24px;
  overflow-x: hidden;
}
</style> 