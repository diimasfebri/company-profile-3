<template>
<div class="body-container"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1523199455310-87b16c0eed11?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
  <div class="desc-container">
    <span class="desc-1"> CUT & SEW </span>
    </div>  
  </div>
  <div class="slide-two">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/70160250-aeb8-4491-bc95-2b43caadbfe9_download+%283%29.jpeg?auto=compress,format&w=1080&h=1080&fit=crop&q=85&f=center">
     </div>
    <div class="desc-container">
        <span class="desc">CLOTHES FOR WORK AND PLAY</span>
        <span class="desc-1">Whether you need work flannels for the crew or custom-designed jackets for your store, our cut and sew service offers custom fits, fabrics and styles in a variety of colors, styles and patterns. Whether you need buttons, zippers, plaid print or solid print, we’re here to help you bring your vision to life. Customize your collection with an embroidered design or shop our ready-to-buy styles for a quicker, more affordable option. </span>
      </div>  
    <div class="img-list">
      <img src="https://images.prismic.io/andersonbrothers/6d9dad71-d348-4753-9abb-6328c226fa75_download+%289%29.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
      <img src="https://images.prismic.io/andersonbrothers/06f2c57e-a268-4f80-a605-eb1b3918fe02_download+%286%29.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center">
    </div>  
  </div>
  <div class="slide-three">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/336ea54d-cc42-4882-8de2-b6e1668e90cb_download+%284%29.jpeg?auto=compress,format&w=804&h=864&fit=crop&q=85">
     </div>
  <div class="desc-container">
    <span class="desc-1">“The Anderson Brothers are the best at what they do. I trust them with all of my businesses for amazing design and custom apparel."</span>
  </div>
  </div>
  <div class="slide-four">
    <div class="img-container">
     <img src="https://images.prismic.io/andersonbrothers/164a3ef5-854d-45d2-b9c4-53149ee14845_download+%287%29.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center"> 
     <img src="https://images.prismic.io/andersonbrothers/962e7b98-6158-4c44-8823-aaed59612a71_download+%282%29.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
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
        margin-left:  25rem;
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
      width: 50%;
      height: 50%;
      display: flex;
      align-items: flex-start;
      justify-content: flex-start;
    img.bg-content{
      position: absolute;
      margin-top: 2rem;
      margin-bottom: 2rem;
      margin-left: 2rem;
      width: 50vw;
    }
   }
    .desc-container{
        position: relative;
        display: flex;
        width: 40%;
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
            transform: translateY(2rem);
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
          width: 80%;
          margin-top: 10rem;
          justify-content: flex-start;
          align-items: flex-start;
          margin-left: 1rem;
          margin-bottom: 2rem;
          img{
          position: relative;
          display: flex;
          width: 80%;
          margin-top: 10rem;
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
    transform: translateY(-10rem);
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