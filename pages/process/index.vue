<template>
<div class="body-container" @scroll="scrollHand"> 
  <div class="slide-one">
    <img class="bg-content" src="https://images.unsplash.com/photo-1502239608882-93b729c6af43?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
  <div class="desc-container">
    <span class="desc">OUR PROCESS</span>
    <span class="desc-1"> WE KEEP IT SIMPLE </span>
    <span class="desc-2"> You've done the hard work, now it's our turn. You send us your logos, we send you a customized catalog, designed to showcase your brand. Let us know what you love (and what you don't), then have a seat and pour yourself a beer...we've got it from here.</span>
    </div>  
  </div>
  <div class="slide-two">
    <img class="bg-content" src="https://images.unsplash.com/photo-1517816743773-6e0fd518b4a6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80" >
  <div class="button-container">
      <span class="desc">WHAT TO EXPECT</span>
      <span class="desc-1">Our design team will take a deep dive into your company logo, brand assets and color palette to begin elevating your brand. You'll work collaboratively with our world-class design, production and merchandising teams to create a customized catalog, then we'll produce and ship your brand new collection in as quickly as 21 days.</span>
    </div>
  </div>
  <div class="slide-three">
    <div class="img-container">
        <img class="bg-content" src="https://images.unsplash.com/photo-1542435503-956c469947f6?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=667&q=80">
     </div>
  <div class="desc-container ">
    <span class="desc target">01</span>
    <span class="desc-1">SHARE YOUR LOGO AND BRAND ASSETS</span>
    <span class="desc-2">Our design team will elevate your brand by using your company logos, brand assets and color palette.</span>
    </div>
  </div>
  <div class="slide-four">
      <div class="img-container">
          <img class= "bg-content" src="https://images.unsplash.com/photo-1504309092620-4d0ec726efa4?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
    </div>
    <div class="desc-container ">
        <span class="desc target">02</span>
        <span class="desc-1">WE'LL DESIGN YOU A CUSTOM CATALOG</span>
        <span class="desc-2">Collaborate with our world-class design, production and merchandising teams to create lifestyle driven apparel with timeless design.</span>
    </div>
  </div>
  <div class="slide-five">
    <div class="img-container">
    <img class="bg-content" src="https://images.unsplash.com/photo-1530543787849-128d94430c6b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
    </div>
  <div class="desc-container">
    <span class="desc target">03</span>
    <span class="desc-1">ORDER AND RECEIVE DAMN GOOD APPAREL</span>
    <span class="desc-2">We’ll produce and ship your brand new collection in as quickly as 21 days with the highest quality printing, garments and material.</span>
   </div> 
  </div>
  <div class="slide-six">
   <div class="desc-container">
      <span class="desc">WE'RE HERE FOR YOU</span>
      <span class="desc-1">From providing imagery to use on your social channels to giving advice on how to merchandise your apparel, we’re here to support you.</span>
      <img src="/CP.png" alt="">
      <div class="button-hire">
          <div class="img-container">
            <img class="flash" src="/flash.png" >
          </div>
        <span>HIRE US</span>
      </div>
    </div> 
  </div>
  <div class="slide-seven">
    <img src="https://images.prismic.io/andersonbrothers/9f71cd88-4950-4a20-875a-f909777cfeaa_226077030_340112087762285_3510021914681768504_n.jpeg?auto=compress,format&w=804&h=864&fit=crop&q=85" alt="">
      <div class="desc-container">
    <span class="desc">"</span>
    <span class="desc-1">The Anderson Brothers are the best at what they do. I trust them with all of my businesses for amazing design and custom apparel.</span>
    <div class="auth">
      <span class="desc-2">MARCUS LEMONIS - THE PROFIT, CNBC</span>
      <span class="desc-3">"</span>
    </div>
      </div>
  </div>
  <div class="slide-eight">
    <div class="left">
      <img class="bg-content" src="https://images.unsplash.com/photo-1426543881949-cbd9a76740a4?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mzd8fGJhY2tncm91bmQlMjBwZW9wbGV8ZW58MHx8MHx8&auto=format&fit=crop&w=600&q=60">
      <div class="filter-black"></div> 
      <span class="desc">LET'S BE BROS</span>
      <div class="button" @click="$router.push('/contact')">
        <span>HIRE US</span>
      </div>   
    </div>
    <div class="right">
      <img class="bg-content" src="https://images.unsplash.com/photo-1496602910407-bacda74a0fe4?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=80" alt="">
      <div class="filter"></div>
      <span class="desc">WE'VE GOT YOUR SIX</span>
      <div class="button" @click="$router.push('/work')">
        <span>SEE OUR WORK</span>
      </div>
    </div>
  </div>
</div>
</template>

<script>
import gsap from 'gsap'
export default {
  data(){
    return{
      scrollTargett: [],
    }
  },
  mounted() {
    const targets = document.querySelectorAll('.target')
    this.scrollTargett = [...targets].map((a) => ({
      distance: a.getBoundingClientRect().top - window.innerHeight,
      el: a,
    }))
    this.scrollTargett.sort((a, b) => a.distance - b.distance)
  },
  methods: {
    scrollHand(e) {
      const top = e.target.scrollTop
      if (this.scrollTargett.length && top >= this.scrollTargett[0].distance) {
        // play anim
        gsap.to(this.scrollTargett[0].el, {
          opacity: 1,
          duration: 1,
          y:0,
        })
        this.scrollTargett.splice(0, 1)
      }
      console.log('test')
    },

   
  },


}
</script>


<style lang="scss" scoped>
.body-container{
  position: relative;
  width: 100vw;
  height: 100vh;
  height: calc((var(--vh, 1vh) * 100));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
   overflow-y: auto;
  > * {
    flex-shrink: 0;
  }
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
        width: 40%;
        height: 100%;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        margin-left:  4rem;
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
        span.desc-2{
            color: white;
            font-family: 'Quicksand';
            font-size: 0.8rem;
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
   height: 60vh;
   display: flex;
    img.bg-content{
      position: absolute;
      width: 100vw;
      height: 60vh;
 }
 .button-container{
    position: relative;
    display: flex;
    width: 55%;
    height: 60vh;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    line-height: 1.5;
    margin-left: 3rem;;
    span.desc{
        font-family: 'Antonio';
        color: black;
        font-size: 1rem;
        font-weight: 900;
        margin-bottom: 1rem;
      }
    span.desc-1{
        font-family: 'Quicksand';
        font-size: 0.7rem;
        color: black;
        width: 70%;
    }
 }
 }
.slide-three{
  position: relative;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  .img-container{
      position: absolute;
      width: 100%;
      height: 100%;
      align-items: flex-end;
      display: flex;
      justify-content: flex-end  ;
      img.bg-content{
         position: relative;
         width: 50vw;
         height: 100vh;
         object-fit: cover;
      }
  }
  .desc-container{
  position: relative;
  display: flex;
  width: 40%;
  height: 100%;
  padding: 5rem 2rem;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
   span.desc{
        font-family: Antonio;
        color:#b48645;
        font-size: 6rem;
        font-weight: 900;
        opacity: 0;
        transform: translateY(2rem);
        }
    span.desc-1{
        font-family: Antonio;
        color: black;
        font-size: 1rem;
        font-weight: 900;
        transform: translateY(-2.5rem);
    }
    span.desc-2{
        font-family: Quicksand;
        color: black;
        font-size: 0.7rem;
        transform: translateY(-1rem);
    }
   }
 }
.slide-four{
  position: relative;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  .img-container{
      position: relative;
      width: 50%;
      height: 100%;
      align-items: flex-start;
      display: flex;
      justify-content: flex-start ;
      img.bg-content{
         position: relative;
         width: 100%;
         height: 100vh;
         object-fit: cover;
      } 
  }
.desc-container{
  position: relative;
  display: flex;
  width: 40%;
  height: 100%;
  transform: translateX(2rem);
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
   span.desc{
        font-family: Antonio;
        color:#b48645;
        font-size: 6rem;
        font-weight: 900;
         opacity: 0;
        transform: translateY(2rem);
        }
    span.desc-1{
        font-family: Antonio;
        color: black;
        font-size: 1rem;
        font-weight: 900;
        transform: translateY(-2.5rem);
    }
    span.desc-2{
        font-family: Quicksand;
        color: black;
        font-size: 0.7rem;
        transform: translateY(-1rem);
    }
}
 }
.slide-five{
  position: relative;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  .img-container{
      position: absolute;
      width: 100%;
      height: 100%;
      align-items: flex-end;
      display: flex;
      justify-content: flex-end  ;
      img.bg-content{
         position: relative;
         width: 50vw;
         height: 100vh;
         object-fit: cover;
      }
  }
  .desc-container{
  position: relative;
  display: flex;
  width: 40%;
  height: 100%;
  padding: 5rem 2rem;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
   span.desc{
        font-family: Antonio;
        color:#b48645;
        font-size: 6rem;
        font-weight: 900;
         opacity: 0;
        transform: translateY(2rem);
        }
    span.desc-1{
        font-family: Antonio;
        color: black;
        font-size: 1rem;
        font-weight: 900;
        transform: translateY(-2.5rem);
    }
    span.desc-2{
        font-family: Quicksand;
        color: black;
        font-size: 0.7rem;
        transform: translateY(-1rem);
    }
}
 }
.slide-six{
  position: relative;
  width: 100vw;
  height: 110vh;
  display: flex;
  justify-content: center;
  align-items: center;
  .desc-container{
    position: relative;
    display: flex;
    width: 100%;
    height: 100%;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    span.desc{
      color: black;
      font-family: 'Antonio';
      font-size: 3rem;
      font-weight: 900;
      margin-bottom: 1.5rem;
    }
    span.desc-1{
    text-align: center;
    font-family: 'Quicksand';
    font-size: 0.7rem;
    color: black;
    width: 60%;   
    margin-bottom: 2rem;
    }
    img{
      position: relative;
      display: flex;
      width: 45rem;
      height: 18rem;
      object-fit: cover;
    }
    .button-hire{
      position: absolute;
      display: flex;
      width: 9.27rem;
      height: 8.95rem;
      background: #282829;
      margin-top: 17.3rem;
      margin-left: 17.2rem;
      justify-content: center;
      align-content: center;
      flex-direction: column;
      .img-container{
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 2rem;
          img.flash{
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            width: 2rem;
            height: 2rem;
          }
        }
         span{
              position: relative;
              display: flex;
              width: 100%;
              justify-content: center;
              font-family: quicksand;
              font-size: 1rem;
              color: #b48645;
              margin-top: 0.7rem;
            }
             &:hover{
                background: #b48645;
                span{
                  color: #f0eee3;
                }
              }
    }
  }
 
 }
.slide-seven{
  position: relative;
  width: 100vw;
  height: 120vh;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  background: #f0eee3;
  img{
    width: 23rem;
    height: 24rem;
    margin-left:4.2rem;
    margin-top: 3rem;
  }
    .desc-container{
    position: relative;
    display: flex;
    width: 40%;
    height: 100%;
    padding: 5rem 2rem;
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
          font-size: 1.8rem;
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
.slide-eight{
  position: relative;
  width: 100vw;
  height: 85vh;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: flex-start;
  .left{
    position: relative;
    display: flex;
    width: 50%;
    height: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    img{
      width: 100%;
      height: 100%;
      position: absolute;
      object-fit: cover;
    }
    .filter-black{
      position: absolute;
      width: 100%;
      height: 100%;
      background: rgba(#b48645, 0.6);
    }
    span.desc{
      font-family: Antonio;
      font-size: 3rem;
      color: white;
      font-weight: 900;
      z-index: 5;
    }
    .button{
      position: relative;
      display: flex;
      width: 9.5rem;
      height: 1.7rem;
      background: #282829;
      justify-content: center;
      margin-top: 1rem;
    span{
      position: relative;
      display: flex;
      color: white;
      font-family: Antonio;
      font-size: 0.7rem;
      font-weight: 900;
      align-items: center;
      justify-content: center;
    }
    &:hover{
      background: #b48645;
    }
    }
  }
  .right{
    position: relative;
    display: flex;
    width: 50%;
    height: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    
     img{
      width: 100%;
      height: 100%;
      position: absolute;
      object-fit: cover;
    }
      .filter{
      position: absolute;
      width: 100%;
      height: 100%;
      background: rgba(black, 0.6);
    }
    span.desc{
      font-family: Antonio;
      font-size: 3rem;
      color: white;
      font-weight: 900;
      z-index: 5;
    }
    .button{
      position: relative;
      display: flex;
      width: 12rem;
      height: 1.7rem;
      background: #b48645;
      justify-content: center;
      margin-top: 1rem;
    span{
      position: relative;
      display: flex;
      color: white;
      font-family: Antonio;
      font-size: 0.7rem;
      font-weight: 900;
      align-items: center;
      justify-content: center;
    }
    &:hover{
      background: #282829;
    }
      }
  }
  }
  @media screen and (max-width: 1024px) {
    .slide-one{
      width: 100%;
      height: 100vh;
      img.bg-content{
        width: 100%;
      }
      .desc-container{
        width: 100%;
        margin-left: 1rem;
        height: 90vh;
        span.desc{
          
        }
        span.desc-1{
          
        }
        span.desc-2{

        }
      }
    }
    .slide-two{
      height: 120vh;
      width: 100%;
      img.bg-content{
        width: 100%;
        height: 100vh;
      }
      .button-container{
        margin-top: 3rem;
        margin-left: 1rem;
        span.desc{

        }
        span.desc-1{
          width: 100%;
        }
      }
    }
    .slide-three{
      width: 100%;
      height: 100vh;
      flex-direction: row;
        .desc-container{
          justify-content: flex-start;
          width: 100%;
          height: 100vh;
          transform: translateY(-10rem);
          span.desc-target{
  
          }
          span.desc-1{
            width: 100%;
          }
          span.desc-2{
            width: 100%;
          }
        }
      .img-container{
        width: 100%;
        height: 100%;
        align-items: flex-start;
        flex-direction: row;
        img.bg-content{
          margin-top: 10rem;
          height: 562px;
          width: 100%;
          
          
        }
      }
    }
    .slide-four{
      width: 100%;
      height: 120vh;
      flex-direction: row;
     .desc-container{
        justify-content: flex-start;
        width: 100%;
        margin-top: 0.5rem;
        transform: translateX(-5rem);
          span.desc-target{
          width: 100%;
          margin-top: 0.5rem;
          }
          span.desc-1{
            width: 100%;
          }
          span.desc-2{
            width: 100%;
          }
        }
      .img-container{
        align-items: flex-start;
        flex-direction: row;
        img.bg-content{
          margin-top: 18rem;
          height: 562px;
          width: 380px; 
          
        }
      }
    }
    .slide-five{
      width: 100%;
      height: 120vh;
      flex-direction: row;
     .desc-container{
        justify-content: flex-start;
        width: 100%;
          span.desc-target{
          width: 100%;
          margin-top: 0.5rem;
          }
          span.desc-1{
            width: 100%;
          }
          span.desc-2{
            width: 100%;
          }
        }
      .img-container{
        align-items: flex-start;
        flex-direction: row;
        img.bg-content{
          margin-top: 20rem;
          height: 562px;
          width: 380px; 
          
        }
      }
    }
    .slide-six{
      position: relative;
      align-items: center;
      width: 100%;
      .desc-container{
        margin-top: 6rem;
        span.desc{
          text-align: center;
        }
        span.desc-1{

        }
        img{
          position: absolute;
          justify-content: center;
        }
        .button-hire{
          .img-container{
            img.flash{

            }
          }
        }
      }
    }
    .slide-seven{
      .desc-container{
        span.desc{
          
        }
        span.desc-1{

        }
        .auth{
          span.desc-2{

          }
        }
        span.desc-3{

        }

      }
      img{
        width: 100%;
        height: 335px;
      }
    }
  }
}
</style>