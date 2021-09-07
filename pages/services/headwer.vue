<template>
<div class="body-container"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1518481774046-f7384edaf3fa?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
  <div class="desc-container">
    <span class="desc-1"> HEADWEAR </span>
    </div>  
  </div>
  <div class="slide-two">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/f6cf6007-b0a0-4880-a18e-25a9483b74a9_download+%281%29.jpeg?auto=compress,format&w=1080&h=1080&fit=crop&q=85&f=center">
     </div>
    <div class="desc-container">
        <span class="desc">YOU’VE NEVER HAT IT SO GOOD</span>
        <span class="desc-1">Give customers and employees alike the chance to rep your brand with customized headwear. From baseball hats to beanies, we only use the top-quality headwear to create your designs. Customize your cap with woven and embroidered patches or take advantage of our clean embroidery techniques. When it comes to trendy styles and fits, we’re way ahead of the curve. With styles to suit everyone, and every climate, our customized headwear is just as easy to personalize is it is fun to wear. </span>
      </div>  
    <div class="img-list">
      <img src="https://images.prismic.io/andersonbrothers/f1199f5b-9b76-4c73-a433-a30312b91251_download+%283%29.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
      <img src="https://images.prismic.io/andersonbrothers/71f5e469-2595-45a8-8c33-8ac1c15b4e1b_download+%282%29.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center">
    </div>  
  </div>
  <div class="slide-three">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/190dc38a-90f6-4c10-97a2-2aa34acd71bd_download+%284%29.jpeg?auto=compress,format&w=804&h=864&fit=crop&q=85">
     </div>
  <div class="desc-container">
    <span class="desc-1">“Working with ABDS has been a game changer for us at Brouwerij West. From their years of experience in the industry, to the exceptional quality of their designs and products, Anderson Brothers Design and Supply have made it incredibly easy to have a world-class merchandise program here at the brewery.”</span>
  </div>
  </div>
  <div class="slide-four">
    <div class="img-container">
     <img src="https://images.prismic.io/andersonbrothers/73147fd3-83ad-48c0-8304-0ee83906a44f_download+%285%29.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center"> 
     <img src="https://images.prismic.io/andersonbrothers/5fd85de0-ff5d-45e0-862f-d0114984715c_download+%289%29.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
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
      margin-top: 4rem;
      margin-bottom: 2rem;
      margin-left: 2rem;
      width: 50vw;
    }
   }
    .desc-container{
        position: relative;
        display: flex;
        width: 35%;
        margin-left: 33rem;
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
                transform: translateY(3rem);
            }
          }
        .img-list{
          position: relative;
          display: flex;
          flex-direction: row;
          width: 80%;
          margin-top: 20rem;
          justify-content: flex-start;
          align-items: flex-start;
          margin-left: 1rem;
          margin-bottom: 2rem;
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
      transform: translateY(-4rem);
    span.desc-1{
        font-family: Antonio;
        color: black;
        font-size: 1.5rem;
        font-weight: bold;
        transform: translateY(4rem);
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