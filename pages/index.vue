<template>
<div class="body-container"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1479888230021-c24f136d849f?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
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
  <div class="button-container">
    <div class="button">
      <span class="desc">OUR WORK</span>
    </div>
  </div>
  </div>
  <div class="slide-three">
    <img class="bg-content" src="https://images.unsplash.com/photo-1515768678138-4ba95ba6ec96?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1958&q=80">
  <div class="desc-container">
    <span class="desc">OUR SERVICES</span>
    <div class="menu-list">
      <div class="menu-item">
        <span>CUSTOM DESIGN</span>
      </div>
      <div class="menu-item">
        <span>SCREEN PRINTING</span>
      </div>
      <div class="menu-item">
        <span>HEADWEAR</span>
      </div>
      <div class="menu-item">
        <span>CUT & SAW</span>
      </div>
      <div class="menu-item">
        <span>ACCESSORIES</span>
      </div>
    </div>
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
  height: 100vh;
  display: flex;
   img.bg-content{
      position: absolute;
      width: 100vw;
      height: 100vh;
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
     font-family: Antonio;
     color: white;
     font-size: 0.8rem;
     font-weight: 900;
    .menu-list{
      position: relative;
      display: flex;
      width: 100%;
      height: 100%;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
      .menu-item{
        position: relative;
        display: flex;
        border-top: 1px solid black;
        width: 4rem;
        height: 4rem;
      }
    }
   }
  }
}
}
</style>