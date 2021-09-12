<template>
<div class="body-container"> 
  <div class="slide-one">
  <div class="desc-container">
    <span class="desc-1"> D*MN GOOD QUALITY </span>
    <span class="desc-2"> Our goal is to help grow your brand through custom design and premium apparel. We offer quick turnaround times and affordable pricing. We are a full package design agency and production house in Seal Beach, California.</span>
    </div>
  <div class="bg-container">
    <img src="https://images.unsplash.com/photo-1629299342291-98995bcca891?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=333&q=80"> 
  </div>
  <div class="item-container">
    <span class="desc-3" @click="$router.push('/services/customdesign')">CUSTOM DESIGN</span>
    <span class="desc-3" @click="$router.push('/services/screenprinting')">SCREEN PRINTING </span>
    <span class="desc-3" @click="$router.push('/services/headwer')">HEADWER</span>
    <span class="desc-3" @click="$router.push('/services/cut&sew')">CUT & SEW</span>
    <span class="desc-3" @click="$router.push('/services/accessories')">ACCESSORIES</span>
  </div> 
  </div>
  <div class="slide-two">
    <div class="desc-container">
        <span class="desc">YOU ARE IN GOOD HANDS</span>
        <img src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format">
        <img src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format">
        <img src="https://images.prismic.io/andersonbrothers/3f50020a-7a98-4a7b-8b23-7c635ed406f8_logos-row-3.png?auto=compress,format">
        <img src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format">
      </div>  
  </div>
    <div class="slide-three">
          <div class="content-container">
           <img src="https://images.prismic.io/andersonbrothers/9d6609bf-e0f6-42e1-b363-8129d9f422a0_192141485_293521482489208_6621258632138134305_n.jpeg?auto=compress,format&w=750&h=741&fit=crop&q=85&f=center" alt="">
            <div class="desc-container">
              <span class="desc"> WE'LL BE YOUR WINGMAN </span>
              <span class="desc-1"> Have ideas, we can help, need ideas we have those too. If you want merch that will make someone say "daaaamn" we've got you! </span> 
              <div class="button" @click="$router.push('/contact')">
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
  height: 250vh;
  display: flex;
  background: black;
  justify-content: flex-start;
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
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        margin-left:  9rem;
        margin-top: 10rem;
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
          width: 25%;
          flex-direction: column;
          font-weight: 500;
        }
        }
        .item-container{
        position: relative;
        display: flex;
        width: 100%;
        height: 100%;
        transform: translateY(-3rem);
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        margin-left: 9rem;
        margin-top: 6rem;
        font-weight: bold;
        span.desc-3{
           font-family: 'Antonio';
           color: white;
           font-size: 130px;
           font-weight: 900;
           margin-top: 2rem;
           margin-bottom: 0.5rem;
           line-height: 1;
        &:hover{
            color: #b48645;
            span.role-3{
              color: #f4f4f4
            }
      }
    }
 }
 .bg-container{
      position: absolute;
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-end;
      transform: translateY(-44rem);
      margin-left: 7rem;
      img{
        position: absolute;
        width: 32rem;
        height: 38rem;
        object-fit: cover;
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
   background-color: #282829;
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
            color: white;
            font-size: 1rem;
            font-weight: 900;
          }
        img{           
        position: relative;           
        display: flex;           
        height: 6rem;   
        color: black;        
        animation: marquee 10s linear infinite;     
        @keyframes marquee {     
            from { transform: translateX(0); }     
            to { transform: translateX(-100%); }     
            }     
            
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