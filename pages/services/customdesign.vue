<template>
<div class="body-container"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1441984261150-55796ff52afc?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=839&q=80">
  <div class="desc-container">
    <span class="desc-1"> CUSTOM DESIGN </span>
    </div>  
  </div>
  <div class="slide-two">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/635650b4-df28-4171-9d5d-6534d5d81a1a_73475344_101021104658431_7650227357011818624_n.jpeg?auto=compress,format&w=750&h=676&fit=crop&q=85&f=center">
     </div>
    <div class="desc-container">
        <span class="desc">WHEN YOU WORK WITH US, YOU WORK WITH THE BEST</span>
        <span class="desc-1">The folks we help aren’t just customers to us – these are brands we believe in, brands we wear and support. That’s why we’ve built a world-class design team to help bring your vision to life. Our designers and in-house illustrators dive deep into your logo design, color palette and messaging in order to get to the heart of your brand.  When it comes to the design work, we keep it simple. After our design team dives into your brand, you’ll work collaboratively with us to create your collection. We’ll talk about your story, maybe share a laugh or two, and really get to know who you, and your brand, are.</span>
      </div>  
    <div class="img-list">
      <img src="https://images.prismic.io/andersonbrothers/360ec377-867c-4e9a-b71c-c6d6beefbb35_107941959_145001300536455_2962723900008999164_n.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
      <img src="https://images.prismic.io/andersonbrothers/332e50f3-2b70-4a3e-8353-ccc28c04cdd4_118614890_167168778236020_7885514944768749926_n.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center">
    </div>  
  </div>
  <div class="slide-three">
    <div class="img-container">
        <img class="bg-content" src="https://images.prismic.io/andersonbrothers/dcfbd144-86c3-4647-b105-43578b51fb33_102430783_654207478466623_1722211818841452464_n.jpeg?auto=compress,format&w=804&h=864&fit=crop&q=85">
     </div>
  <div class="desc-container">
    <span class="desc-1">"The Anderson Brothers are the best at what they do. I trust them with all of my businesses for amazing design and custom apparel."</span>
  </div>
  </div>
  <div class="slide-four">
    <div class="img-container">
     <img src="https://images.prismic.io/andersonbrothers/fd403d4c-0d78-40b0-80fc-0e6a832b0504_95345101_247856789928069_326199525772961341_n.jpeg?auto=compress,format&w=397&h=544&fit=crop&q=85&f=center"> 
     <img src="https://images.prismic.io/andersonbrothers/de141eaa-34b2-4fa7-acdf-dbecfc832620_87594854_220057132472320_3590531815329565696_n.jpeg?auto=compress,format&w=968&h=544&fit=crop&q=85&f=center">
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
        align-items: flex-start;
        margin-left:  16rem;
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
          margin-top: 15rem;
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