<template>
<div class="body-container"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1441984536979-3513fd89f0d0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80">
  <div class="desc-container">
    <span class="desc-1"> KICK-A** SCREEN PRINTING </span>
    </div>  
  </div>
  <div class="slide-two">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/71d80649-f78b-4cdc-b3c6-678afe98802d_download+%2814%29.jpeg?auto=compress,format&w=1080&h=1080&fit=crop&q=85&f=center">
     </div>
    <div class="desc-container">
        <span class="desc">DAMN GOOD DESIGNS</span>
        <span class="desc-1">At Anderson Brothers, we use only the top-quality inks and print processes to create and design your collection. Our custom screen printing designs are built to withstand the test of time. Not sure how to place or size your logo? Leave it to us! We’re experts in print placement and size, taking extra care to ensure your logos and brand assets come out looking damn good each and every time.
        And if you have custom pantone colors, we can easily match them. Whether you need tee shirts, tank tops, hoodies or sweaters, our screen printing services can help bring your brand to life.</span>
      </div>  
    <div class="img-list">
      <img src="https://images.prismic.io/andersonbrothers/6347a499-571f-4afe-a4f5-4f055cb85aa0_download+%2815%29.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
      <img src="https://images.prismic.io/andersonbrothers/0f0f10ba-e275-495d-a7c6-3bf4beb8a17e_download+%2812%29.jpeg?auto=compress,format&rect=320,0,760,1080&w=760&h=1080&w=397&h=544&fit=crop&q=85&f=center">
    </div>  
  </div>
  <div class="slide-three">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/cc73c7e2-d922-4926-847b-71d6c248d964_download+%2818%29.jpeg?auto=compress,format&w=804&h=864&fit=crop&q=85">
     </div>
  <div class="desc-container">
    <span class="desc-1">"The Anderson Brothers are the best at what they do. I trust them with all of my businesses for amazing design and custom apparel."</span>
  </div>
  </div>
  <div class="slide-four">
    <div class="img-container">
     <img src="https://images.prismic.io/andersonbrothers/39f69a3b-04b4-4f96-b632-ed48cca543f2_download+%287%29.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center"> 
     <img src="https://images.prismic.io/andersonbrothers/a91bff8b-97b4-4942-9c23-5b3477965812_download+%285%29.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
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
          font-size: 3rem;
          font-weight: 900;
        }
    }
 }
 .slide-two{
   position: relative;
   width: 100vw;
   justify-content: flex-start;
   display: flex;
   flex-direction: column;
   background-color: #f4f4f4;
   .img-container{
      position: absolute;
      width: 40%;
      height: 40%;
      display: flex;
      align-items: flex-start;
      justify-content: flex-start;
    img.bg-content{
      position: absolute;
      margin-top: 4rem;
      margin-bottom: 2rem;
      margin-left: 4rem;
      width: 40vw;
    }
   }
    .desc-container{
        position: relative;
        display: flex;
        width: 30%;
        margin-left: 30rem;
        padding: 5rem 2rem;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        span.desc{
            font-family: Antonio;
            color: black;
            font-size: 20px;
            font-weight: 900;
            transform: translateY(4rem);
          }
        span.desc-1{
                font-family: Quicksand;
                color: black;
                font-size: 15px;
                transform: translateY(5rem);
            }
          }
        .img-list{
          position: relative;
          display: flex;
          flex-direction: row;
          width: 68%;
          margin-top: 15rem;
          justify-content: flex-start;
          align-items: flex-start;
          margin-left: 1rem;
          margin-bottom: 2rem;
          img{
          position: relative;
          display: flex;
          width: 68%;
          flex-direction: row;
          justify-content: flex-start;
          align-items: flex-start;
          margin-left: 1rem;
          margin-bottom: 3rem;
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
      position: absolute;
      width: 100%;
      height: 100%;
      display: flex;
      align-items: flex-start;
      justify-content: flex-start;
      img.bg-content{
         position: relative;
         width: 23rem;
         height: 24rem;
         margin-left:4.2rem;
         margin-top: 3rem;
         object-fit: cover;
      }
  }
    .desc-container{
      position: relative;
      display: flex;
      width: 40%;
      height: 100%;
      margin-left: 30rem;
      padding: 5rem 2rem;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
    span.desc-1{
        font-family: Antonio;
        color: black;
        font-size: 1.5rem;
        font-weight: bold;
        transform: translateY(3rem);
    }
   }
  }
.slide-four{
   position: relative;
   width: 100vw;
   justify-content: flex-start;
   display: flex;
   flex-direction: column;
   background-color: #f4f4f4;
.img-container{
    position: relative;
    display: flex;
    flex-direction: row;
    width: 80%;
    margin-top: 15rem;
    justify-content: flex-start;
    align-items: flex-start;
    margin-left: 1rem;
    margin-bottom: 2rem;
    transform: translateY(-13rem);
         img{
          position: relative;
          display: flex;
          width: 80%;
          flex-direction: row;
          justify-content: flex-start;
          align-items: flex-start;
          margin-left: 1rem;
          margin-bottom: 3rem;
          }
          }
 } 
}
</style>