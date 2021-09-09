<template>
<div class="body-container"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1479888230021-c24f136d849f?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
    <div class="filter-black"></div>
  <div class="desc-container">
    <div class="desc">
      <span>D*MN GOOD APPAREL</span>
    </div>  
    <div class="button">
      <span class="desc">VIEW OR WORK</span>
    </div>
  </div>
  </div>
  <div class="slide-two">
    <img class="bg-content" src="https://images.unsplash.com/32/9FybtVFNSEOxogGzIvHJ_IMG_2226.jpg?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=889&q=80" >
    <div class="filter-black"></div>
  <div class="button-container">
    <div class="button">
      <span class="desc">OUR WORK</span>
    </div>
  </div>
  </div>
  <div class="slide-three">
    <img class="bg-content" src="https://images.unsplash.com/photo-1515768678138-4ba95ba6ec96?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1958&q=80">
    <div class="filter-black"></div>
    <div class="desc-container">
      <span class="desc">OUR SERVICES</span>
      <div class="menu-list">
        <div class="menu-item">
          <span class="txt">CUSTOM DESIGN</span>
        </div>
        <div class="menu-item">
          <span class="txt">SCREEN PRINTING</span>
        </div>
        <div class="menu-item">
          <span class="txt">HEADWEAR</span>
        </div>
        <div class="menu-item">
          <span class="txt">CUT & SAW</span>
        </div>
        <div class="menu-item btm">
          <span class="txt">ACCESSORIES</span>
        </div>
      </div>
    </div>
  </div>
  <div class="slide-four">
    <div class="content-container">
      <span class="desc"> WE KEEP IT SIMPLE </span>
      <div class="step-list">
        <div class="step one">
          <div class="img">
            <img src="https://images.unsplash.com/photo-1621607505833-616916c46a25?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8cG9tYWRlfGVufDB8fDB8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
            <span>1</span>
          </div>
          <div class="txt-container">
            <span class="title">SHARE YOUR LOGO AND BRAND ASSETS</span>
            <span class="subtitle"> Our design team will elevate your brand by using your company logos, brand assets and color palletes</span>
          </div>
        </div>
        <div class="step two">
          <div class="img">
            <img src="https://images.unsplash.com/photo-1540221652346-e5dd6b50f3e7?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1049&q=80" alt="">
            <span>2</span>
          </div>
          <div class="txt-container">
            <span class="title">WE'LL DESIGN YOU A CUSTOM CATALOG</span>
            <span class="subtitle"> Collaborate with our world-class design, production and merchandising teams to create lifestyle driven apparel with timeless design.</span>
          </div>
        </div>
        <div class="step three">
          <div class="img">
            <img src="https://images.unsplash.com/photo-1562157873-818bc0726f68?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=564&q=80" alt="">
            <span>3</span>
          </div>
          <div class="txt-container">
            <span class="title">ORDER AND RECIEVE DAMN GOOD APPAREL</span>
            <span class="subtitle"> We'll produce and ship your brand new collection as quickly as 21 days with the highest quality printing, garments and material.</span>
          </div>
        </div>
      </div>
      <div class="button-start">
        <span class="txt">GET STARTED</span>
      </div>
    </div>
  </div>
  <div class="slide-five">
    <div class="desc-container">

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
  align-items: flex-start;
.slide-one{
   position: relative;
   width: 100vw;
   height: 100vh;
   display: flex;
    img.bg-content{
      position: absolute;
      width: 100vw;
      height: 100vh;
      object-fit: cover ;
    }
    .filter-black{
      position: absolute;
      width: 100%;
      height: 100%;
      background: rgba(#000, 0.6);
    }
     
    .desc-container{
      position: relative;
      display: flex;
      width: 100%;
      height: 100%;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      .desc{
        position: relative;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        span{
          color: white;
          font-family: Antonio;
          font-size: 3rem;
          font-weight: 900;
        }
      }
      .button{
        position: relative;
        display: flex;
        width: 11rem;
        height: 1.5rem;
        background: white;
        justify-content: center;
        align-items: center;
        margin-top: 0.5rem;
        span{
          color: black;
          font-family: Antonio;
          font-size: 0.8rem;
          font-weight: 900;
        }
      }
    }
 }
 .slide-two{
   position: relative;
   width: 100vw;
   height: 100vh;
   display: flex;
    img.bg-content{
      position: absolute;
      width: 100vw;
      height: 100vh;
    }
    .filter-black{
      position: absolute;
      width: 100%;
      height: 100%;
      background: rgba(#000, 0.6);;
    }
 .button-container{
  position: relative;
  display: flex;
  width: 100%;
  height: 100%;
  flex-direction: column;
  justify-content: center;
  align-items: center;
   .button{
     position: relative;
     display: flex;
     width: 9.5rem;
     height: 1.5rem;
     background: #282829;
     flex-direction: column;
     justify-content: center;
     align-items: center;
    span.desc{
      position: relative;
      display: flex;
      font-family: Antonio;
      font-size: 0.8rem;
      font-weight: 900;
      color: white;
      }
   }
 }
 }
.slide-three{
  position: relative;
  width: 100vw;
  height: 120vh;
  display: flex;
   img.bg-content{
      position: absolute;
      width: 100vw;
      height: 120vh;
   }
   .filter-black{
      position: absolute;
      width: 100%;
      height: 100%;
      background: rgba(#000, 0.6);;
    }
  .desc-container{
    position: relative;
    display: flex;
    width: 100%;
    height: 100%;
    padding: 5rem 4rem;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    span.desc{
     font-family: 'Antonio';
     color: white;
     font-size: 1.2rem;
     font-weight: 900;
     transform: translateY(-2rem);
    }
    .menu-list{
      position: relative;
      display: flex;
      width: 100%;
      height: 100vw;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
      .menu-item{
        position: relative;
        display: flex;
        flex-direction: row;
        width: 60vw;
        border-top: 1px solid rgba(128, 128, 122, 1);
        margin-bottom: 0.5rem;
        span.txt{
          position: relative;
          display: flex;
          width: 100%;
          margin-bottom: 1.5rem;
          font-family: 'Antonio';
          font-size: 4rem;
          color: white;
        }

        &.btm{
          border-bottom: 1px solid rgba(128, 128, 122, 1);
        }
      }
    }
  }
 
 }
 .slide-four{
  position: relative;
  width: 100vw;
  height: 120vh;
  display: flex;
  justify-content: center;
  align-items: center;
  .content-container{
    position: relative;
    display: flex;
    width: 85%;
    height: 100%;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    span.desc{
      font-family: 'Antonio';
      color: #282829;
      font-size: 1.2rem;
      font-weight: 900;
      margin: 8rem 0 2.5rem 0;
    }
    .step-list{
      position: relative;
      width: 100%;
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
      .step{
        position: relative;
        display: flex;
        width: 33%;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        .img{
          position: relative;
          width: 18.75rem;
          height: 12.5rem;
          display: flex;
          img{
            border-radius: 100%;
            object-fit: cover;
            width: 100%;
            height: 100%;
          }
          span{
            position: absolute;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-family: 'Antonio';
            font-size: 7rem;
            font-weight: 900;
          }
        }
        .txt-container{
         position: relative;
         display: flex;
         flex-direction: column;
         justify-content: flex-start;
         align-items: flex-start;
          span.title{
            font-family: 'Quicksand';
            font-size: 22px;
            color: #282829;
            font-weight: 700;
            margin-top: 2rem;
          }
          span.subtitle{
            font-family: 'Quicksand';
            font-size: 16px;
            color: #282829;
            font-weight: 400;
            margin-top: 0.5rem;
          }
        }
     
      }
    }
    .button-start{
      position: relative;
      display: flex;
      margin-top: 5rem;
      width: 10rem;
      height: 1.6rem;
      background: #282829;
      justify-content: center;
      align-items: center;
      span.txt{
        font-family: 'Antonio';
        color: white;
        font-size: 0.8rem;
        font-weight: 900;
      }
    }
  }
 }
 .slide-five{
  position: relative;
  width: 100vw;
  height: 85h;
  display: flex;
  justify-content: center;
  align-items: center;
  .desc-container{
    position: relative;
  }
 }
}
</style>