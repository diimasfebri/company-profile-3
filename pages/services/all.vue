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
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/72cb339b-18b3-48a1-b45b-18ef592dfabb_167230745_312607226951849_6425918934258754467_n.jpeg?auto=compress,format&w=640&h=785&fit=crop&q=85&f=center">
     </div>
    <div class="desc-container">
        <span class="desc">NEED SOMETHING ELSE?</span>
        <span class="desc-1">Still can’t find what you’re looking for? We can source or custom make anything available on the market. Bottle openers, coasters, bandanas, glass wear…whatever you need, that’s what we do. We can further personalize your accessories with customizable colors and logo placements. From seasonal items to promotional materials, we will work with you to bring your vision to life. </span>
      </div>  
    <div class="img-list">
      <img src="https://images.prismic.io/andersonbrothers/8e8d3487-0f19-44dd-a9d7-a1290cfec742_206124884_335342188168759_904531908827994356_n.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
      <img src="https://images.prismic.io/andersonbrothers/762894c0-5f78-48e5-8ac3-042ddb30d102_118996014_2435750616724248_7041903916703683333_n.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center">
    </div>  
  </div>
  <div class="slide-three">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/b9d66888-90d6-4ddf-8cf8-f8bcd793ca53_150698621_114917153910782_8970756713766715774_n.jpeg?auto=compress,format&w=804&h=864&fit=crop&q=85">
     </div>
  <div class="desc-container">
    <span class="desc-1">“Working with Anderson Brothers Design & Supply has been an amazing experience! They have helped us elevate our assortment with high-quality, uniquely-designed apparel that fans around the world love! Mike provides the exceptional designs, John provides the garment and trend expertise, making them the perfect combination. Plus, they have a great support team that is always available to help.”</span>
  </div>
  </div>
  <div class="slide-four">
    <div class="img-container">
     <img src="https://images.prismic.io/andersonbrothers/ad149b2f-b5ac-4b53-9ccc-cde93158b009_download+%282%29.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center"> 
     <img src="https://images.prismic.io/andersonbrothers/4bcefe5a-6628-423e-ad18-d079cf403d6f_download.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
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
        &:hover{
            background: #b48645;
            span.role-3{
              color: #f4f4f4
            }
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
      margin-top: 2rem;
      margin-bottom: 5rem;
      margin-left: 2rem;
      width: 40vw;
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
          margin-bottom: 5rem;
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
      margin-left: 28rem;
      padding: 5rem 2rem;
      transform: translateY(-0.5rem);
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
    span.desc-1{
        font-family: Antonio;
        color: black;
        font-size: 1.5rem;
        font-weight: bold;
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