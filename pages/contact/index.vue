<template>
  <div class="container"  @scroll="scrollHandler">
    <div class="slide-one">
      <img
        class="bg-content"
        src="https://images.unsplash.com/uploads/1412273646059cc129bb5/eae0a1da?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80"
      />
      <div class="desc-container">
        <span class="desc">LET'S BE BROS</span>
        <span class="desc-1">TELL US MORE</span>
      </div>
    </div>
    <div class="slide-two">
      <span class="desc">WHAT SERVICES DO YOU NEED?</span>
      <div class="button-list">
        <div class="button"         
          :class="buttonSelected === 1 ? 'active' : ''"
          @click="buttonSelected = 1">
          <div class="circle">
            <div class="circle-mini"></div>
          </div>
          <span class="txt">I NEED A FREASH LOOK (Our design team is ready!)</span>
       </div>
        <div class="button" 
          :class="buttonSelected === 2 ? 'active' : ''"
          @click="buttonSelected = 2">
          <div class="circle">
            <div class="circle-mini"></div>
          </div>
          <span class="txt"
            >MY DESIGN ARE READY TO GO (Upload assets below)</span
          >
        </div>
      </div>
      <div class="button-list-sec">
        <span class="desc">DESIGN SERVICES</span>
        <div class="desc-container">
          <div class="button"
          :class="SecondSelected === true ? 'active' : ''"
          @click="SecondSelected = !SecondSelected">
          
            <div class="circle">
              <div class="bg"></div>
              <img src="flash.png" alt="">

            </div>
            <span class="txt">ILLUSTRATION</span>
          </div>
          <div class="button"  :class="ThirdSelected === true ? 'active' : ''"
          @click="ThirdSelected = !ThirdSelected">
            <div class="circle">
              <div class="bg"></div>
              <img src="flash.png" alt="">
            </div>
            <span class="txt">PACKAGE AND LABEL DESIGN</span>
          </div>
          <div class="button" :class="FourthSelected === true ? 'active' : ''"
          @click="FourthSelected = !FourthSelected">
            <div class="circle">
              <div class="bg"></div>
              <img src="flash.png" alt="">
            </div>
            <span class="txt">LOGO/BRANDING</span>
          </div>
        </div>
      </div>
      <div class="product">
        <span class="desc">CATEGORIES</span>
        <div class="card-list">
          <div class="card">
            <img src="https://images.prismic.io/andersonbrothers/89d584b8-3691-4255-80d4-b8ebcd5b1350_John-Anderson-President.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center"
              alt=""
            />
            <span class="name"> TEES </span>
            <div class="button" 
            :class="oneSelected === true ? 'active' : ''"
            @click="oneSelected = !oneSelected "> 
             <div class="kotak">
              <img src="flash.png" alt="">  
              </div>     
            </div>
          </div>
          <div class="card">
            <img
              src="https://images.prismic.io/andersonbrothers/83eae39b-48fb-4e72-a27e-edf48fbd5425_Mike-Anderson-Creative-Director.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center"
              alt=""
            />
            <span class="name"> FLEECE </span>
            <div class="button"
            :class="twoSelected === true ? 'active' : ''"
            @click="twoSelected = !twoSelected ">
              <div class="kotak">
              <img src="flash.png" alt="">  
              </div>  
             </div>
          </div>
          <div class="card">
            <img
              src="https://images.prismic.io/andersonbrothers/29830ffb-eb83-48d0-9830-d53bf63574d5_Aaron-Ashton-Sales-%26-Marketing.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center"
              alt=""
            />
            <span class="name"> FLANNELS </span>
            <div class="button"
            :class="threeSelected === true ? 'active' : ''"
            @click="threeSelected = !threeSelected ">
            <div class="kotak">
              <img src="flash.png" alt="">  
              </div>  
            </div>
          </div>
        </div>
        <div class="card-list two">
          <div class="card">
            <img
              src="https://images.prismic.io/andersonbrothers/6eb97008-65a2-427b-ab41-a835617f3abb_AfterlightImage+22.JPG?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center"
              alt=""
            />
            <span class="name"> OUTERWEAR/JACKET </span>
            <div class="button"
            :class="fourSelected === true ? 'active' : ''"
            @click="fourSelected = !fourSelected ">
            <div class="kotak">
              <img src="flash.png" alt="">  
              </div> 
             </div>
          </div>
          <div class="card">
            <img
              src="https://images.prismic.io/andersonbrothers/bd632467-16f3-429a-abdc-a342cf41c708_Debbi-Wong-Accounting-Manager.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center"
              alt=""
            />
            <span class="name"> HEADWEAR </span>
            <div class="button"
            :class="fiveSelected === true ? 'active' : ''"
            @click="fiveSelected = !fiveSelected "> 
            <div class="kotak">
              <img src="flash.png" alt="">  
              </div> 
            </div>
          </div>
          <div class="card">
            <img
              src="https://images.prismic.io/andersonbrothers/2117d343-7156-4e6f-9002-090ea6342e42_Kenny-Novak-Graphic-Design.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center"
              alt=""
            />
            <span class="name"> GLASSWEAR/GROWLERS </span>
            <div class="button"
            :class="sixSelected === true ? 'active' : ''"
            @click="sixSelected = !sixSelected ">
            <div class="kotak">
              <img src="flash.png" alt="">  
              </div>  
            </div>
          </div>
        </div>
        <div class="card-list test">
          <div class="card">
            <img
              src="https://images.prismic.io/andersonbrothers/4ecfbc98-ced8-40ae-8082-ea5c65e06ba8_Madison-Bailey-Production-Manager.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center"
              alt=""
            />
            <span class="name"> ACCESSORIES </span>
            <div class="button"
            :class="sevenSelected === true ? 'active' : ''"
            @click="sevenSelected = !sevenSelected "> 
            <div class="kotak">
              <img src="flash.png" alt="">  
              </div> 
            </div>
          </div>
          <div class="card">
            <img
              src="https://images.prismic.io/andersonbrothers/e600c588-2fed-4de6-933a-68406fc2d409_Tempest-Orman-Accounting-Asst.jpg?auto=compress,format&w=330&h=370&fit=crop&q=85&f=center"
              alt=""
            />
            <span class="name"> PROMOTIONAL </span>
            <div class="button"
            :class="eightSelected === true ? 'active' : ''"
            @click="eightSelected = !eightSelected "> 
            <div class="kotak">
              <img src="flash.png" alt="">  
              </div> 
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="slide-three">
      <span class="desc">LETS WORK TOGETHER</span>
      <div class="form">
        <input type="text" name="" required placeholder="First Name" />
        <input type="text" name="" required placeholder="Last Name" />
        <input type="text" name="" required placeholder="Company" />
        <input type="email" name="" required placeholder="Email" />
        <input type="text" name="" required placeholder="Phone" />
        <div class="upload-container">
          <span class="upload">Upload Brand Assets And Logo</span>
          <div class="button">
            <span class="unggah">UPLOAD</span>
          </div>
        </div>
        <div class="buttongede" @click="$router.push('/confirmed')">
          <span class="kumpul">SUBMIT!</span>
        </div>
        <span class="desc-2">PULL THE TRIGGER</span>
      </div>
    </div>
    <div class="slide-four">
      <div class="bg">
        <div class="line" aria-hidden="true">
          <img
            src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/18c63e8b-da67-4e14-a575-73a6a68ceef5_logos-row-1.png?auto=compress,format"
          />
        </div>
        <div class="line x" aria-hidden="true">
          <img
            src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/c75ffffc-ec43-4da8-9b3a-f6f31a16c508_logos-row-2.png?auto=compress,format"
          />
        </div>
        <div class="line" aria-hidden="true">
          <img
            src="https://images.prismic.io/andersonbrothers/30940b70-234d-4557-8554-5bc4355e6742_abds_logos_row3b.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/30940b70-234d-4557-8554-5bc4355e6742_abds_logos_row3b.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/30940b70-234d-4557-8554-5bc4355e6742_abds_logos_row3b.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/30940b70-234d-4557-8554-5bc4355e6742_abds_logos_row3b.png?auto=compress,format"
          />
        </div>
        <div class="line x" aria-hidden="true">
          <img
            src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format"
          />
          <img
            src="https://images.prismic.io/andersonbrothers/3fc617ce-03d0-4221-bca4-7fc328d3f9cc_logos-row-4.png?auto=compress,format"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import gsap from 'gsap'
export default {
  data() {
    return {
      scrollTargets: [],
      buttonSelected: 0,
      SecondSelected: false,
      ThirdSelected: false,
      FourthSelected: false,
      oneSelected: false,
      twoSelected: false,
      threeSelected: false,
      fourSelected: false,
      fiveSelected: false,
      sixSelected: false,
      sevenSelected: false,
      eightSelected: false,
    }
  },
   mounted() {
    const targets = document.querySelectorAll('.target')
    this.scrollTargets = [...targets].map((a) => ({
      distance: a.getBoundingClientRect().top - window.innerHeight,
      el: a,
    }))
    this.scrollTargets.sort((a, b) => a.distance - b.distance)
  },
    methods: {
    scrollHandler(e) {
      console.log(e)
      const top = e.target.scrollTop
      if (top > this.scrollTop) {
        this.$root.$emit('scroll-top')
      } else {
        this.$root.$emit('scroll-down')
      }
      if (this.scrollTargets.length && top >= this.scrollTargets[0].distance) {
        // play anim
        gsap.to(this.scrollTargets[0].el.children, {
          opacity: 1,
          duration: 2,
          stagger: 0.5,
          y: 0,
        })
        this.scrollTargets.splice(0, 1)
      }
      this.scrollTop = top
    },
    },
}
</script>

<style lang="scss" scoped>
.container {
  position: relative;
  width: 100vw;
  min-height: 100vh;
  min-height: calc((var(--vh, 1vh) * 100));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  overflow: hidden;
  overflow-y: auto;
  > * {
    flex-shrink: 0;
  }
  .slide-one {
    position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    img.bg-content {
      position: absolute;
      width: 100vw;
      height: 80vh;
      object-fit: cover;
    }
    .desc-container {
      position: relative;
      display: flex;
      width: 100%;
      height: 100%;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      span.desc {
        font-family: Antonio;
        color: white;
        font-size: 3rem;
        font-weight: 900;
      }
      span.desc-1 {
        font-family: Antonio;
        color: white;
        font-size: 0.7rem;
        font-weight: 900;
        margin-top: 1rem;
      }
    }
  }
  .slide-two {
    position: relative;
    width: 100vw;
    display: flex;
    color: white;
    align-items: center;
    justify-content: flex-start;
    flex-direction: column;
    span.desc {
      text-align: center;
      font-family: Antonio;
      color: black;
      font-size: 1.7rem;
      font-weight: 900;
    }
    .button-list {
      position: relative;
      display: flex;
      margin-top: 2rem;
      width: 60%;
      flex-direction: row;
      justify-content: space-between;
      align-items: space-between;
      .button {
        position: relative;
        display: flex;
        width: 22rem;
        height: 2.5rem;
        border: 5px solid black;
        flex-direction: row;
        justify-content: flex-start;
        align-items: center;
        .circle {
          position: relative;
          display: flex;
          width: 1.5rem;
          height: 1.5rem;
          border: 5px solid black;
          border-radius: 100%;
          margin: 0 0.5rem;
          justify-content: center;
          align-items: center;
          .circle-mini{
            width: 1.25rem;
            height: 1.25rem;
            border-radius: 100%;
            background: #b48645;
            opacity: 0;
          }
        }
        span.txt {
          justify-content: flex-start;
          align-items: flex-start;
          font-family: Quicksand;
          color: black;
          font-size: 0.7rem;
          border: black;
        }
        &.active {
          border: 5px solid #b48645;
          .circle{
            border: 5px solid #b48645;
            .circle-mini{
              opacity: 1;
            }
          }

        }
      }
    }
    .button-list-sec {
      position: relative;
      display: flex;
      margin-top: 2rem;
      width: 80%;
      flex-direction: column;
      justify-content: flex-start;
      align-items: center;
      span.desc {
        text-align: center;
        font-family: Antonio;
        color: black;
        font-size: 1rem;
        font-weight: bold;
      }
      .desc-container {
        position: relative;
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        align-items: center;
        .button {
          position: relative;
          display: flex;
          width: 13rem;
          height: 2.5rem;
          border: 5px solid black;
          flex-direction: row;
          justify-content: center;
          align-items: center;
          margin: 0 0.5rem;
          margin-top: 1rem;
          .circle{
            position: relative;
            display: flex;
            width: 2.5rem;
            height: 2.8rem;
            border-right: 4px solid black;
            margin-right: 1rem;
            justify-content: center;
            align-items: center;
            img{
              position: relative;
              display: flex;
              z-index: 200;
              width: 1rem;
              height: 1rem;
              align-items: center;
              justify-content: center;
              opacity: 0; 
            }
            .bg {
              position: absolute;
              width: 100%;
              height: 90%;
            }
         }
          span.txt {
            justify-content: flex-start;
            align-items: flex-start;
            font-family: Quicksand;
            color: black;
            font-size: 0.7rem;
            border: black;
          }
          &.active{
              border: 5px solid #b48645;
              .circle{
                border-right: 5px solid #b48645;

                img{
                  opacity: 1;
                }
                .bg{
                  background: #b48645 ;
                }
              }
          }
        }
        
      
        }   
    } 
    .product {
  position: relative;
  display: flex;
  margin-top: 2rem;
  margin-bottom: 3rem;
  width: 80%;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  span.desc {
    text-align: center;
    font-family: Antonio;
    color: black;
    font-size: 1rem;
    margin: 1.5rem 0;
    font-weight: 900;
  }
  .card-list {
    position: relative;
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    .card {
      position: relative;
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
      span.name {
        position: relative;
        font-family: 'Quicksand';
        font-size: 0.7rem;
        font-weight: 600;
        margin-left: 4rem;
        justify-content: flex-start;
        align-items: flex-start;
        display: flex;
        transform: translateY(-3rem);
      }
      .button {
        position: relative;
        display: flex;
        transform: translateY(-4.8rem);
        height: 2rem;
        margin-left: 1.5rem;
        width: 2rem;
        border: 4px solid black;
        background: white;
        .kotak{
          width: 100%;
          height: 100%;
          position: absolute;
          display: flex;
          align-items: center;
          background:#b48645;
          opacity: 0;
          justify-content: center;
          img {
            position: absolute;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
            width: 1rem;
            height: 1rem;
          }
         
        }
      &.active{
          border: 4px solid #b48645;
          .kotak{
              opacity: 1;
            }
            
          
      }
      }
    }
  }
    }
  }
  .slide-three {
    position: relative;
    display: flex;
    width: 100vw;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    span.desc {
      text-align: center;
      font-family: 'Antonio';
      color: black;
      margin: 1rem 0;
      font-size: 1.7rem;
      font-weight: 900;
    }
    .form {
      position: relative;
      display: flex;
      width: 100%;
      flex-direction: column;
      justify-content: flex-start;
      align-items: center;
      input {
        height: 2rem;
        width: 24rem;
        margin-bottom: 0.5rem;
        border-bottom: 1px solid #b48645;
        outline: none;
      }
    }
    .upload-container {
      position: relative;
      display: flex;
      width: 24rem;
      height: 2.8rem;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #b48645;
      span.upload {
        text-align: center;
        font-family: 'Quicksand';
        color: black;
        font-size: 0.7rem;
        font-weight: 900;
      }
      .button {
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #282829;
        height: 1.5rem;
        width: 3rem;
        span.unggah {
          text-align: center;
          font-family: Antonio;
          color: white;
          font-size: 0.7rem;
          font-weight: 900;
        }
        &:hover {
          background: #b48645;
        }
      }
    }
    .buttongede {
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #b48645;
      height: 5rem;
      width: 24rem;
      margin: 2rem 0;
      span.kumpul {
        text-align: center;
        font-family: 'Antonio';
        color: white;
        margin: 1rem 0;
        font-size: 1.7rem;
        font-weight: 900;
      }
      &:hover {
        background: #282829;
      }
    }
    span.desc-2 {
      text-align: center;
      font-family: 'Antonio';
      color: black;
      font-size: 6rem;
      font-weight: 900;
      font-weight: bold;
      margin-bottom: 2rem;
    }
  }
  .slide-four {
    position: relative;
    display: flex;
    padding: 2rem 0;
    width: 100vw;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    background: #282829;
    .bg {
      position: relative;
      overflow: hidden;
      --offset: 20vw;
      --move-initial: calc(-25% + var(--offset));
      --move-final: calc(-50% + var(--offset));
      .line {
        width: fit-content;
        display: flex;
        position: relative;
        transform: translate3d(var(--move-initial), 0, 0);
        animation: marquee 20s linear infinite;
        animation-play-state: running;
        img {
          height: 6rem;
          padding: 1rem 2px;
        }
        @keyframes marquee {
          0% {
            transform: translate3d(var(--move-initial), 0, 0);
          }
          100% {
            transform: translate3d(var(--move-final), 0, 0);
          }
        }
        &.x {
          animation-direction: reverse;
        }
      }
    }
  }
 @media screen and (max-width: 1024px) {
   .slide-one{
     position: relative;
     width: 100%;
     img.bg.content{
      width: 100%;
      height: 30vh;
      object-fit: cover;
     }
     .desc-container{
       width: 100%;
       transform: translateY(-8rem);
       span.desc{
         font-size: 2rem;
       }
       span.desc-1{
         font-size: 1rem;
       }
     }
   }
   .slide-two{
     width: 100%;
     flex-direction: column;
     span.desc{

     }
     .button-list{
       position: relative;
       flex-direction: column;
       align-items: center;
       .button{
         width:335px;
         height: 100px;
         margin-bottom: 1rem;
       .circle{
         position: relative;
         align-items: center;
         .circle-mini{

         }
       }
       }
       span.txt{

       }
     }
     .button-list-sec{
       width: 100%;
       position: relative;
       flex-direction: column;
       align-items: center;
       span.desc{
         text-align: center;
         font-size: 1rem;
       }
       .desc-container{
         flex-direction: column;
         .button {
           justify-content: flex-start;
           align-items: center;
           position: relative;
           .circle{
             position: relative;
             flex-direction: column;
             img{
               flex-direction: column;
             }
             .bg{
               flex-direction: column;
             }
           }
           span.txt {
             
           }
         }
       }
     }
     .product{
       span.desc{

       }
       .card-list{
         flex-direction: column;
         .card{
           flex-direction: column;
         }
       }
     }
   }
   .slide-three{
     span.desc{

     }
     .form{
       flex-direction: column;
       input {
         width: 90%;
         height: 45px;
       }
     }
     .upload-container{
       width: 90%;
       height: 45px;
       justify-content: center;
       span.upload{
         text-align: center;
       }
       .button{
         margin-left: 0.5rem;
         span.unggah{
         }
       }
     }
     .buttongede{
       width: 90%;
       height: 80px;
       span.kumpul{

       }
     }
     span.desc-2{
       width: 100%;
       font-size: 2rem;
     }
   }
   .slide-four{
     position: relative;
     width: 100%;
     .bg{
       .line{
         img {
           height: 4rem;
           padding: 0;
         }
       }
     }
   }
 }
}

</style>