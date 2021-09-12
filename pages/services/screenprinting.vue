<template>
<div class="body-container"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80">
  <div class="desc-container">
    <span class="desc-1"> KICK-A** SCREEN PRINTING </span>
    </div>  
  </div>
  <div class="slide-two">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/71d80649-f78b-4cdc-b3c6-678afe98802d_download+%2814%29.jpeg?auto=compress,format&w=1080&h=1080&fit=crop&q=85&f=center">
        <div class="desc-container">
            <span class="desc">DAMN GOOD DESIGNS</span>
            <span class="desc-1">At Anderson Brothers, we use only the top-quality inks and print processes to create and design your collection. Our custom screen printing designs are built to withstand the test of time. Not sure how to place or size your logo? Leave it to us! We’re experts in print placement and size, taking extra care to ensure your logos and brand assets come out looking damn good each and every time. \
              And if you have custom pantone colors, we can easily match them. Whether you need tee shirts, tank tops, hoodies or sweaters, our screen printing services can help bring your brand to life.</span>
          </div>  
     </div>
    <div class="img-list">
      <img class="satu" src="https://images.prismic.io/andersonbrothers/6347a499-571f-4afe-a4f5-4f055cb85aa0_download+%2815%29.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
      <img class="dua" src="https://images.prismic.io/andersonbrothers/0f0f10ba-e275-495d-a7c6-3bf4beb8a17e_download+%2812%29.jpeg?auto=compress,format&rect=320,0,760,1080&w=760&h=1080&w=397&h=544&fit=crop&q=85&f=center">
    </div>  
  </div>
  <div class="slide-three">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/cc73c7e2-d922-4926-847b-71d6c248d964_download+%2818%29.jpeg?auto=compress,format&w=804&h=864&fit=crop&q=85">
     </div>
  <div class="desc-container">
        <span class="desc">"</span>
    <span class="desc-1">The Anderson Brothers are the best at what they do. I trust them with all of my businesses for amazing design and custom apparel.</span>
    <div class="auth">
      <span class="desc-2">MARCUS LEMONIS - THE PROFIT, CNBC</span>
      <span class="desc-3">"</span>
  </div>
  </div>
</div>
  <div class="slide-four">
    <div class="img-container">
     <img class= "satu" src="https://images.prismic.io/andersonbrothers/39f69a3b-04b4-4f96-b632-ed48cca543f2_download+%287%29.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center"> 
     <img class="dua" src="https://images.prismic.io/andersonbrothers/a91bff8b-97b4-4942-9c23-5b3477965812_download+%285%29.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
    </div>
  </div>
    <div class="marquee">
    <div class="track">
      <div class="content">&nbsp;ANDERSON BROTHER WE HAVE A PHD IN CUSTOM APPAREAL
         QUALITY GOODS</div>
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
  justify-content: center;
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
        margin-top: 2rem;
        line-height: 1.5;
        span.desc{
            font-family: 'Antonio';
            color: #b48645;
            font-size: 1rem;
            font-weight: 900;
        }
        span.desc-1{
          color: white;
          font-family: 'Antonio';
          font-size: 4rem;
          font-weight: 900;
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

   justify-content: flex-start;
   display: flex;
   flex-direction: column;
   align-items: center;
   background-color: #f4f4f4;
   .img-container{
      position: relative;
      width: 90%;
      height: 100%;
      margin: 3rem 0;
      display: flex;
      flex-direction: row;
      align-items: space-between;
      justify-content: space-between;
      
    img.bg-content{
      position: relative;
      width: 30rem;
      height: 32rem;
      object-fit: cover;

    }
    .desc-container{
        position: relative;
        display: flex;
        width: 50%;
        height: 32rem;
        margin-left: 4rem;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        span.desc{
            font-family: Antonio;
            color: black;
            font-size: 2rem;
            font-weight: 900;
            
          }
        span.desc-1{
          margin-top: 2rem;
                font-family: Quicksand;
                color: black;
                font-size: 1rem;
                line-height: 1.5rem;
            }
          }
   }
    .img-list{
      position: relative;
      display: flex;
      flex-direction: row;
      width: 90%;
      justify-content: center;
      align-items: center;
      margin: 2rem 0;
      img.satu{
      position: relative;
      display: flex;
      width: 75%;
      margin-right: 1rem;
      height: 24rem  ;
      object-fit: cover;
      }
      img.dua{
      position: relative;
      display: flex;
      height: 24rem ;
      width: 25%;
      object-fit: cover;
      
      }
    }
 }
.slide-three{
  position: relative;
  width: 100vw;
  height: 120vh;
  display: flex;
  flex-direction: row;
  background: #f4f4f4;
  .img-container{
      position: relative;
      width: 50%;
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: flex-start;
      img.bg-content{
         position: relative;
         width: 32.5rem;
         height: 35rem;
         margin-left: 2rem;
         object-fit: cover;
      }
  }
        .desc-container{
    position: relative;
    display: flex;
    width: 50%;
    height: 100%;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
      span.desc{
          color: #b48645;
          font-family: 'Antonio';
          font-size: 3rem;
          font-weight: 900;
      }
      span.desc-1{
          font-family: Antonio;
          color: black;
          font-size: 3rem;
          font-weight: 900;
          transform: translateY(-1rem);
      }
      .auth{
        position: relative;
        display: flex;
        width: 100%;
        justify-content: center;
        align-items: center;
        span.desc-2{
            font-family: Antonio;
            color: #b48645;
            font-size: 0.7rem;
            font-weight: 900;
          }
      }
      span.desc-3{
          color: #b48645;
          font-family: Antonio;
          font-size: 3rem;
          font-weight: 900;
          transform: translateX(4rem);
      }
    }
 }
.slide-four{
   position: relative;
   width: 100vw;
   justify-content: flex-start;
   display: flex;
   flex-direction: column;
   align-items: center;
   background-color: #f4f4f4;
 .img-container{
      position: relative;
      display: flex;
      flex-direction: row;
      width: 90%;
      justify-content: center;
      align-items: center;
      margin: 2rem 0;

      img.satu{
      position: relative;
      display: flex;
      width: 25%;
      margin-right: 1rem;
      height: 24rem  ;
      object-fit: cover;
      }
      img.dua{
      position: relative;
      display: flex;
      height: 24rem ;
      width: 75%;
      object-fit: cover;
      
      }
    }
 } 
 .marquee{
  position: relative;
  width: 100vw;
  max-width: 100%;
  height: 200px;
  overflow-x: hidden;
  background: #F0EEE3;
  .track{
    position: absolute;
    white-space: nowrap;
    will-change: transform;
    animation: marquee 10s linear infinite;
    .content{
      font-family: 'Antonio';
      font-size: 144px;
      font-weight: bolder;
      color: #282829;
     
     }
    @keyframes marquee {
    from { transform: translateX(0); }
    to { transform: translateX(-100%); }
    }
    @keyframes marquee {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
    }
    } 
 }
}
</style>