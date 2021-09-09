<template>
<div class="body-container"> 
  <div class="slide-one">
  <div class="desc-container">
    <span class="desc-1"> D*MN GOOD QUALITY </span>
    <span class="desc-2"> Our goal is to help grow your brand through custom design and premium apparel. We offer quick turnaround times and affordable pricing. We are a full package design agency and production house in Seal Beach, California.</span>
    </div>
  <div class="item-container">
    <span class="desc-3">CUSTOM DESIGN</span>
    <span class="desc-3">SCREEN PRINTING</span>
    <span class="desc-3">HEADWER</span>
    <span class="desc-3">CUT & SEW</span>
    <span class="desc-3">ACCESSORIES</span>
  </div>  
  </div>
  <div class="slide-two">
    <div class="desc-container">
        <span class="desc">YOU ARE IN GOOD HANDS</span>
      </div>  
  </div>
    <div class="slide-three">
          <div class="content-container">
           <img src="https://images.prismic.io/andersonbrothers/9d6609bf-e0f6-42e1-b363-8129d9f422a0_192141485_293521482489208_6621258632138134305_n.jpeg?auto=compress,format&w=750&h=741&fit=crop&q=85&f=center" alt="">
            <div class="desc-container">
              <span class="desc"> WE'LL BE YOUR WINGMAN </span>
              <span class="desc-1"> Have ideas, we can help, need ideas we have those too. If you want merch that will make someone say "daaaamn" we've got you! </span> 
              <div class="button">
                <span class="desc-2">HIRE US</span>
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
  height: 200vh;
  display: flex;
  background: black;
  justify-content: center;
  flex-direction: column;
  align-items: flex-start;
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
        align-items: flex-start;
        margin-left:  8rem;
        margin-top: 2rem;
        span.desc-1{
            font-family: 'Antonio';
            color: white;
            font-size: 25px;
            font-weight: 900;
            margin-bottom: 0.5rem;
            line-height: 1.5;
        }
        span.desc-2{
          color: white;
          font-family: 'Quicksand';
          font-size: 15px;
          width: 35%;
          flex-direction: column;
          font-weight: 500;
        }
        }
        .item-container{
        position: relative;
        display: flex;
        width: 100%;
        height: 100%;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        margin-left: 9rem;
        margin-top: 2rem;
        transform: translateY(-4cm);
        font-weight: bold;
        span.desc-3{
           font-family: 'Antonio';
           color: white;
           font-size: 100px;
           font-weight: 400;
           margin-bottom: 0.5rem;
           line-height: 1.5;
      }
    }
 }
 .slide-two{
   position: relative;
   width: 100vw;
   height: 100vh;
   justify-content: flex-start;
   display: flex;
   flex-direction: column;
   background-color: #fff;
    .desc-container{
        position: relative;
        display: flex;
        width: 30%;
        padding: 3.5rem 4rem;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        span.desc{
            font-family: Antonio;
            color: black;
            font-size: 1rem;
            font-weight: 900;
          }
          }
    }
 
.slide-three{
    position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #f0eee3;
    .content-container{
     position: relative;
     display: flex;
     width: 80%;
     height: 100%;
     flex-direction: row;
     justify-content: center;
     align-items: center;
     margin-top: 3rem;
     margin-left: -3rem;
     img{
       position: relative;
       display: flex;
       width: 31rem;
       height: 21rem;
      }
    .desc-container{
        position: relative;
        display: flex;
        width: 100%;
        height: 100%;
        margin-left: 3rem;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        span.desc{
          font-family: Antonio;
          color:black;
          font-size: 2.5rem;
          font-weight: 900;
          margin-bottom: 1.5rem;
          line-height: 2.5rem;
        }
        span.desc-1{
          font-family: 'Quicksand';
          color:black;
          font-size: 17px;
          line-height: 1rem;
        }
        .button {
          cursor: pointer;
          position: relative;
          display: flex;
          width: 9rem;
          height: 1.5rem;
          background: #b48645;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          margin-top: 2rem;
          span.desc-2 {
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
  }

}
</style>