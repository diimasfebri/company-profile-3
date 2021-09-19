<template>
<div class="body-container" @scroll="scrollHandler"> 
  <div class="slide-one">
    <div class="layer-container">
      <div :style="`transform: translateX(-${layerIndex * 100}%)`" class="layer">
        <img class="bg-content" src="https://images.unsplash.com/photo-1479888230021-c24f136d849f?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
        <div class="filter-black"></div>
        <div class="desc-container">
          <div class="desc">
          <span>D*MN GOOD APPAREL</span>
        </div>  
        <div class="button">
          <span class="desc" @click="$router.push('/work')">VIEW OR WORK</span>
        </div>
      </div>

        </div>
      <div :style="`transform: translateX(-${layerIndex * 100}%)`" class="layer">
        <img class="bg-content" src="https://images.unsplash.com/photo-1496293455970-f8581aae0e3b?ixid=MnwxMjA3fDB8MHxzZWFyY2h8M3x8dmludGFnZXxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=60">
        <div class="filter-black"></div>
        <div class="desc-container">
          <div class="desc">
          <span>FALL FLANNEL ARE HERE</span>
        </div>  
        <div class="button">
          <span class="desc" @click="$router.push('/work')">VIEW OUR PROCESS</span>
        </div>
      </div>

        </div>
    </div>
    <div class="button-switch">
      <div class="circle-1" @click="layerHandler('prev')"></div>
      <div class="circle-2" @click="layerHandler('next')"></div>
    </div>
  </div>
  <div class="slide-two">
    <img class="bg-content" src="https://images.prismic.io/andersonbrothers/c48c2615-02be-44f4-8aae-2f5ba88b7061_work-logos.jpg?auto=compress,format&w=1652&h=678&fit=crop&q=85&f=center" >
    <div class="button-container">
      <div class="button" @click="$router.push('/work')">
        <span class="desc" >OUR WORK</span>
      </div>
    </div>
  </div>
  <div class="slide-three">
    <img class="bg-content" src="https://images.unsplash.com/photo-1515768678138-4ba95ba6ec96?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1958&q=80">
    <div class="filter-black"></div>
    <div class="desc-container">
      <span class="desc">OUR SERVICES</span>
      <div class="menu-list">
        <div class="menu-item one" @click="$router.push('/services/customdesign')">
          <span class="txt">
            CUSTOM DESIGN
          </span>
        </div>
        <div class="menu-item two" @click="$router.push('/services/screenprinting')">
          <span class="txt">
            SCREEN PRINTING
            <!-- <img class= "produk" src="https://images.unsplash.com/photo-1576248533223-e3fa93eecbcc?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8bW9ub2tyb218ZW58MHx8MHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=60" alt=""> -->
            </span>
        </div>
        <div class="menu-item three" @click="$router.push('/services/headwer')">
          <span class="txt">
            HEADWEAR
            <!-- <img class= "produk" src="https://media.istockphoto.com/photos/beauty-of-ballet-picture-id1253731461?b=1&k=20&m=1253731461&s=170667a&w=0&h=P71yNb2OJEZdc0AO8HAolrlA6fDfFm1sDJEmOMoUqIM=" alt=""> -->
            </span>
        </div>
        <div class="menu-item four" @click="$router.push('/services/cutsew')">
          <span class="txt">
            CUT & SAW
            <!-- <img class= "produk" src="https://images.unsplash.com/photo-1422207258071-70754198c4a2?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTh8fGJsYWNrJTIwYW5kJTIwd2hpdGV8ZW58MHx8MHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=60" alt=""> -->
            </span>
        </div>
        <div class="menu-item five" @click="$router.push('/services/accessories')">
          <span class="txt">
            ACCESSORIES
            <!-- <img class= "produk" src="https://images.unsplash.com/photo-1549281899-f75600a24107?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjB8fGJsYWNrJTIwYW5kJTIwd2hpdGV8ZW58MHx8MHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=60" alt=""> -->
            </span>
        </div>
      </div>
   
      </div>
 
    </div>
  <div class="slide-four">
    <div class="content-container">
        <span class="desc"> WE KEEP IT SIMPLE </span>
        <div class="step-list target">
          <div class="step one">
            <div class="img">
              <img
                src="https://images.unsplash.com/photo-1621607505833-616916c46a25?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8cG9tYWRlfGVufDB8fDB8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60"
                alt=""
              />
              <span>1</span>
            </div>
            <div class="txt-container">
              <span class="title">SHARE YOUR LOGO AND BRAND ASSETS</span>
              <span class="subtitle">
                Our design team will elevate your brand by using your company
                logos, brand assets and color palletes</span
              >
            </div>
          </div>
          <div ref="stepDua" class="step two">
            <div class="img">
              <img
                src="https://images.unsplash.com/photo-1540221652346-e5dd6b50f3e7?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1049&q=80"
                alt=""
              />
              <span>2</span>
            </div>
            <div class="txt-container">
              <span class="title">WE'LL DESIGN YOU A CUSTOM CATALOG</span>
              <span class="subtitle">
                Collaborate with our world-class design, production and
                merchandising teams to create lifestyle driven apparel with
                timeless design.</span
              >
            </div>
          </div>
          <div ref="stepTiga" class="step three">
            <div class="img">
              <img
                src="https://images.unsplash.com/photo-1562157873-818bc0726f68?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=564&q=80"
                alt=""
              />
              <span>3</span>
            </div>
            <div class="txt-container">
              <span class="title">ORDER AND RECIEVE DAMN GOOD APPAREL</span>
              <span class="subtitle">
                We'll produce and ship your brand new collection as quickly as
                21 days with the highest quality printing, garments and
                material.</span
              >
            </div>
          </div>
        </div>
        <div class="button-start" @click="$router.push('/contact')">
          <span class="txt">GET STARTED</span>
        </div>
        <div class="testimonial">
          <div :style="`transform: translateX(-${activeIndex * 100}%)`" class="testi-container">
            <span class="txt">TESTIMONIALS</span>
            <div class="subtxt-container">
              <span class="desc-2">"</span>
              <span class="desc-1"
                >For over 10+ years I have been trusting the team at Anderson
                Brothers to deliver great quality shirts with awesome creativity
                and thought. I keep coming back for the cuatomer service and
                experience.
              </span>
              <div class="auth">
                <span class="desc-2"
                  >BRANDON RICHARDS - CEO ALESMITH BREWING</span
                >
                <span class="desc-3">"</span>
              </div>
            </div>
          </div>
          <div :style="`transform: translateX(-${activeIndex * 100}%)`" class="testi-container">
            <span class="txt">TESTIMONIALS</span>
            <div class="subtxt-container">
              <span class="desc-2">"</span>
              <span class="desc-1"
                >I love working with ADBS. I really value their design process
                and the friendship we've developed over the years. It's more
                than a business transaction. It's a way to mutually propel our
                business and i've enjoyed the journey so far!
              </span>
              <div class="auth">
                <span class="desc-2"
                  >GREG LONGO - SIERRA NEVADA BREWING CO.</span
                >
                <span class="desc-3">"</span>
              </div>
            </div>
          </div>
        </div>
        <div class="button-switch">
          <div class="circle-1" @click="slideHandler('prev')"></div>
          <div class="circle-2" @click="slideHandler('next')"></div>
        </div>
    </div>
    </div>
  <div class="slide-five">
      <svg>
        <defs>
          <clipPath
            id="clip-00"
            clipPathUnits="objectBoundingBox"
            transform="scale(0.0005208333333333333, 0.000925925925925926)"
          >
            <path
              d="m 341.4087,58.040727 0,951.927273 -112.60986,0 -66.8335,-432.74767 0,432.74767 -107.42188,0 0,-951.927273 107.42188,0 72.02149,428.631863 0,-428.631863 107.42187,0 z"
            />
            <path
              d="m 614.54102,58.040727 73.54737,951.927273 -131.53077,0 -6.40869,-171.09997 -46.08154,0 -7.6294,171.09997 -133.05664,0 65.30762,-951.927273 185.85205,0 z M 546.48682,670.11996 Q 536.72119,508.42756 526.95557,270.88672 507.42432,543.7059 502.54151,670.11996 l 43.94531,0 z"
            />
            <path
              d="m 934.6704,58.040727 0,190.503053 -76.29394,0 0,761.42422 -128.47902,0 0,-761.42422 -75.98874,0 0,-190.503053 280.7617,0 z"
            />
            <path
              d="m 1256.0205,58.040727 0,636.186103 q 0,108.18692 -3.6621,152.28484 -3.6621,43.50995 -21.6675,89.95977 -18.0054,45.86185 -47.6074,69.96876 -29.2969,23.5188 -69.2749,23.5188 -44.2505,0 -78.125,-28.2226 -33.8745,-28.2227 -50.65919,-73.49656 -16.78469,-45.27388 -19.83647,-95.25154 -3.0517,-50.56562 -3.0517,-211.67004 l 0,-563.277533 128.47906,0 0,713.798453 q 0,62.32507 3.3568,79.96425 3.6622,17.05119 14.3433,17.05119 12.207,0 15.564,-18.81512 3.6621,-19.40309 3.6621,-90.54774 l 0,-701.451033 128.479,0 z"
            />
            <path
              d="m 1305.7642,58.040727 90.9424,0 q 90.9423,0 122.9858,13.523364 32.3486,13.523365 52.4902,69.380729 20.4468,55.26941 20.4468,176.97969 0,111.12678 -14.3433,149.34498 -14.3432,38.21821 -56.4575,45.86185 38.147,18.22714 51.2696,48.80171 13.1225,30.57455 16.1743,56.44534 3.3569,25.28282 3.3569,140.5254 l 0,251.06421 -119.3237,0 0,-316.32915 q 0,-76.43641 -6.4087,-94.66354 -6.1035,-18.22715 -32.6538,-18.22715 l 0,429.21984 -128.479,0 0,-951.927273 z m 128.479,162.868343 0,211.67006 q 21.6674,0 30.2123,-11.17148 8.8502,-11.75945 8.8502,-74.67248 l 0,-52.32955 q 0,-45.27388 -8.545,-59.38521 -8.2397,-14.11134 -30.5175,-14.11134 z"
            />
            <path
              d="m 1642.6782,58.040727 214.2334,0 0,190.503053 -85.7544,0 0,180.50751 80.2613,0 0,181.09549 -80.2613,0 0,209.31816 94.2994,0 0,190.50306 -222.7784,0 0,-951.927273 z"
            />
          </clipPath>
        </defs>
      </svg>
      <video loop autoplay muted playsinline>
        <source src="/suave.mp4" type="video/mp4" />
      </video>
      <div class="desc">
        <span class="title"> OUR VISION</span>
        <span class="subtitle"
          >From conception to production, our promise is to help grow your brand
          through custom design and premium apparel.</span
        >
      </div>
    </div>
  <div class="slide-six">
      <div class="content-container">
        <img
          src="https://images.prismic.io/andersonbrothers/28d63aa2-103e-42c6-ba0f-d9fd6a5fe367_teamwork.jpg?auto=compress,format?w=897&h=585&fit=fill&q=85&f=center"
          alt=""
        />
        <div class="desc-container">
          <span class="desc"> TEAMWORK </span>
          <span class="desc-1">
            We believe company culture and teamwork thrive in a fun and creative
            environment. Work with us and get to know our team!</span
          >
          <div class="button" @click="$router.push('/about')">
            <span class="desc-2">ABOUT US</span>
          </div>
        </div>
      </div>
    </div>
  <div class="marquee">
      <div class="track" aria-hidden="true" >
        <div class="content">&nbsp;
          <span>ANDERSON BROTHER </span> 
            <div class="button-hire"  @click="$router.push('/contact')">
              <div class="img-container">
                <img class="flash" src="/flash.png" >
              </div>
              <span>LETS GO</span>
            </div>   
          <span>WE HAVE A PHD IN CUSTOM APPAREAL </span> 
          <span> QUALITY GOODS </span> 
        </div>
        <div class="content">&nbsp;
          <span>ANDERSON BROTHER </span> 
            <div class="button-hire"  @click="$router.push('/contact')">
              <div class="img-container">
                <img class="flash" src="/flash.png" >
              </div>
              <span>LETS GO</span>
            </div>   
          <span>WE HAVE A PHD IN CUSTOM APPAREAL </span> 
          <span> QUALITY GOODS </span> 
        </div>
        <div class="content">&nbsp;
          <span>ANDERSON BROTHER </span> 
            <div class="button-hire"  @click="$router.push('/contact')">
              <div class="img-container">
                <img class="flash" src="/flash.png" >
              </div>
              <span>LETS GO</span>
            </div>   
          <span>WE HAVE A PHD IN CUSTOM APPAREAL </span> 
          <span> QUALITY GOODS </span> 
        </div>
        <div class="content">&nbsp;
          <span>ANDERSON BROTHER </span> 
            <div class="button-hire"  @click="$router.push('/contact')">
              <div class="img-container">
                <img class="flash" src="/flash.png" >
              </div>
              <span>LETS GO</span>
            </div>   
          <span>WE HAVE A PHD IN CUSTOM APPAREAL </span> 
          <span> QUALITY GOODS </span> 
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
      activeIndex: 0,
      menuIndex: 0,
      layerIndex: 0,
      scrollTop: 0
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
      // if (top > this.scrollTop) {
      //   // this.$emit('scrollTop', )
      // } else {

      // }
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
      console.log('test')
    },
    slideHandler(direction) {
      if (direction === 'prev'){
        this.activeIndex = this.activeIndex === 0 ? 0 : this.activeIndex - 1 
      }
      else{
        this.activeIndex = this.activeIndex === 1 ? 1 : this.activeIndex + 1
        
      }
    },
    layerHandler(direction) {
    if (direction === 'prev'){
      this.layerIndex = this.layerIndex === 0 ? 0 : this.layerIndex - 1 
    }
    else{
      this.layerIndex = this.layerIndex === 1 ? 1 : this.layerIndex + 1
      
    }
    },
   
  },
}
</script>


<style lang="scss" scoped>
.body-container {
  position: relative;
  width: 100vw;
  height: 100vh;
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
    justify-content: flex-start;
    align-items: flex-start;
    .layer-container{
      position: relative;
      display: flex;
      width: 100%;
      height: 100vh;
      flex-direction: row;
      justify-content: flex-start;
      align-items: center;
      overflow: hidden;
      .layer{
          position: relative;
          display: flex;
          width: 100%;
          height: 100vh;
          flex-direction: row;
          justify-content: flex-start;
          align-items: center;
           transition: 0.5s transform cubic-bezier(0.645, 0.045, 0.355, 1);
          flex-shrink: 0;
        img.bg-content {
          position: absolute;
          width: 100vw;
          height: 100vh;
          object-fit: cover;
        }
        .filter-black {
          position: absolute;
          width: 100%;
          height: 100%;
          background: rgba(#000, 0.6);
        }
        .desc-container {
          position: relative;
          display: flex;
          width: 100%;
          height: 100%;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          .desc {
            position: relative;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            span {
              color: white;
              font-family: Antonio;
              font-size: 3rem;
              font-weight: 900;
            }
          }
          .button {
            position: relative;
            cursor: pointer;
            display: flex;
            width: 11rem;
            cursor: pointer;
            height: 1.5rem;
            background: white;
            justify-content: center;
            align-items: center;
            margin-top: 0.5rem;
            span.desc {
              color: black;
              font-family: Antonio;
              font-size: 0.8rem;
              font-weight: 900;
            }
            &:hover {
                background: #b48645;
                span.desc{
                  color: white;
                }
            }
        }
      }
      }       
    }
    .button-switch {
      position: absolute;
      display: flex;
      height: 100%;
      margin-left: 8rem;
      align-items: flex-end;
      justify-content: flex-start;
      z-index: 24;
      .circle-1 {
        width: 0.5rem;
        height: 0.5rem;
        border-radius: 100%;
        background: white;
        margin-right: 1rem;
        margin-bottom: 2rem;
        &.active {
          background: #b48645;
        }
      }
      .circle-2 {
        width: 0.5rem;
        height: 0.5rem;
        border-radius: 100%;
        margin-bottom: 2rem;
        background: white;
        &.active {
          background: #b48645;
        }
      }
    }
  }
  .slide-two {
    position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    img.bg-content {
      position: absolute;
      height: 100vh;
      text-align: center;
      animation: cssmarquee 4s linear infinite alternate;
    }
    @keyframes cssmarquee {
      0% {
        transform: translateX(-5%);
      }
      100% {
        transform: translateX(5%);
      }
    }
    .button-container {
      position: relative;
      display: flex;
      width: 100%;
      height: 100%;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      .button {
        position: relative;
        display: flex;
        width: 9.5rem;
        height: 1.5rem;
        background: #282829;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        span.desc {
          position: relative;
          display: flex;
          font-family: Antonio;
          font-size: 0.8rem;
          font-weight: 900;
          color: white;
        }
        &:hover {
          background: #b48645;
        }
      }
    }
  }
  .slide-three {
    position: relative;
    width: 100vw;
    height: 120vh;
    display: flex;
    img.bg-content {
      position: absolute;
      width: 100vw;
      height: 120vh;
    }
    .filter-black {
      position: absolute;
      width: 100%;
      height: 100%;
      background: rgba(#000, 0.6);
    }
    .desc-container {
      position: relative;
      display: flex;
      width: 100%;
      height: 100%;
      padding: 5rem 4rem 5rem 0;
      margin-left: 4rem;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
      span.desc {
        font-family: 'Antonio';
        color: white;
        font-size: 1.2rem;
        font-weight: 900;
        transform: translateY(-2rem);
      }
      .menu-list {
        position: relative;
        display: flex;
        width: 100%;
        height: 100vw;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        .menu-item {
          position: relative;
          display: flex;
          cursor: pointer;
          flex-direction: row;
          width: 60vw;
          border-top: 1px solid rgba(128, 128, 122, 1);
          margin-bottom: 0.5rem;
          span.txt {
            position: relative;
            display: flex;
            width: 100%;
            margin-top: 1.5rem;
            margin-bottom: 1.5rem;
            font-family: 'Antonio';
            font-size: 4rem;
            font-weight: 900;
            color: white;
            line-height: 1;
            justify-content: flex-start;
            align-items: center;
          }
          &.one{
            &:hover{
                span.txt{
                 color:#b48645;

                }
              
            }
          }
          &.two{
            &:hover{
                span.txt{
                 color:#b48645;
                 img.produk{
                  opacity: 1;
                  transform: translateY(-5rem);
                  transition: 2s opacity;
                 }
                }
              
            }
          }
          &.three{
            &:hover{
                span.txt{
                 color:#b48645;
                 img.produk{
                  opacity: 1;
                  transition: 2s opacity;
                 }
                }
              
            }
          }
          &.four{
            &:hover{
                span.txt{
                 color:#b48645;
                 img.produk{
                  opacity: 1;
                  transition: 2s opacity;
                 }
                }
              
            }
          }
          &.five {
            border-bottom: 1px solid rgba(128, 128, 122, 1);
               &:hover{
                span.txt{
                 color:#b48645;
                 img.produk{
                  opacity: 1;
                  transition: 2s opacity;
                 }
                }
              
            }
          }
        
        }
      }
    }
  }
  .slide-four {
    position: relative;
    width: 100vw;
    display: flex;
    justify-content: center;
    align-items: center;
    .content-container {
      position: relative;
      display: flex;
      width: 85%;
      height: 100%;
      flex-direction: column;
      justify-content: flex-start;
      align-items: center;
      span.desc {
        font-family: 'Antonio';
        color: #282829;
        font-size: 1.2rem;
        font-weight: 900;
        margin: 8rem 0 2.5rem 0;
      }
      .step-list {
        position: relative;
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        .step {
          position: relative;
          display: flex;
          width: 33%;
          transform: translateY(5rem);
          opacity: 0;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          .img {
            position: relative;
            width: 18.75rem;
            height: 12.5rem;
            display: flex;
            img {
              border-radius: 100%;
              object-fit: cover;
              width: 100%;
              height: 100%;
            }
            span {
              position: absolute;
              width: 100%;
              height: 100%;
              display: flex;
              justify-content: center;
              align-items: center;
              color: white;
              font-family: 'Antonio';
              font-size: 7rem;
              font-weight: 900;
            }
          }
          .txt-container {
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
            span.title {
              font-family: 'Antonio';
              font-size: 30px;
              color: #282829;
              font-weight: 700;
              margin-top: 2rem;
            }
            span.subtitle {
              font-family: 'Antonio';
              font-size: 20px;
              color: #282829;
              font-weight: 400;
              margin-top: 0.5rem;
            }
          }
        }
      }
      .button-start {
        position: relative;
        display: flex;
        margin-top: 5rem;
        width: 10rem;
        height: 1.6rem;
        background: #282829;
        justify-content: center;
        align-items: center;
        span.txt {
          font-family: 'Antonio';
          color: white;
          font-size: 0.8rem;
          font-weight: 900;
        }
        &:hover {
          background: #b48645;
        }
      }
      .testimonial {
        position: relative;
        display: flex;
        width: 100%;
        flex-direction: row;
        justify-content: flex-start;
        align-items: center;
        overflow: hidden;
        .testi-container {
          position: relative;
          display: flex;
          width: 100%;
          margin-top: 9rem;
          flex-direction: column;
          justify-content: flex-start;
          align-items: flex-start;
          transition: 0.5s transform cubic-bezier(0.645, 0.045, 0.355, 1);
          flex-shrink: 0;
          span.txt {
            color: #282829;
            font-size: 1.2rem;
            font-family: 'Antonio';
            font-weight: 900;
          }
          .subtxt-container {
            position: relative;
            display: flex;
            width: 100%;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
            span.desc-2 {
              color: #b48645;
              font-family: 'Antonio';
              font-size: 3rem;
              font-weight: 900;
            }
            span.desc-1 {
              font-family: 'Antonio';
              color: #282829;
              font-size: 1.9rem;
              font-weight: 900;
              transform: translateY(-1rem);
            }
            .auth {
              position: relative;
              display: flex;
              width: 100%;
              justify-content: flex-end;
              align-items: center;
              span.desc-2 {
                font-family: Antonio;
                color: #b48645;
                font-size: 1rem;
                font-weight: 900;
                transform: translateX(-3rem);
              }
            }
            span.desc-3 {
              color: #b48645;
              font-family: Antonio;
              font-size: 3rem;
              font-weight: 900;
            }
          }
        }
      }
      .button-switch {
        position: relative;
        display: flex;
        margin-bottom: 9rem;
        width: 100%;
        align-items: flex-start;
        justify-content: flex-start;
        .circle-1 {
          width: 0.5rem;
          height: 0.5rem;
          border-radius: 100%;
          background: #282829;
          margin-right: 1rem;
          &.active {
            background: #b48645;
          }
        }
        .circle-2 {
          width: 0.5rem;
          height: 0.5rem;
          border-radius: 100%;
          background: #282829;
          &.active {
            background: #b48645;
          }
        }
      }
    }
  }
  .slide-five {
    position: relative;
    display: flex;
    width: 100vw;
    height: 130vh;
    box-sizing: border-box;
    justify-content: center;
    align-items: flex-end;
    svg {
      width: 100vw;
      height: 0;
      position: absolute;
    }
    video {
      position: absolute;
      left: 0px;
      top: 0px;
      width: 100vw;
      height: 100vh;
      object-fit: cover;
      clip-path: url(#clip-00);
      overflow: hidden;
    }
    .desc {
      position: relative;
      width: 100%;
      display: flex;
      margin: 4rem 0;
      flex-direction: column;
      justify-content: flex-start;
      align-items: center;
      span.title {
        font-family: 'Antonio';
        font-size: 1rem;
        color: #282829;
        font-weight: bolder;
      }
      span.subtitle {
        font-family: 'Quicksand';
        margin-top: 2rem;
        width: 30%;
        text-align: center;
        font-size: 0.8rem;
        color: #282829;
        font-weight: 400;
      }
    }
  }
  .slide-six {
    position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    .content-container {
      position: relative;
      display: flex;
      width: 80%;
      height: 100%;
      flex-direction: row;
      justify-content: flex-start;
      align-items: center;
      img {
        position: relative;
        display: flex;
        width: 35rem;
        height: 22rem;
      }
      .desc-container {
        position: relative;
        display: flex;
        width: 100%;
        height: 100%;
        margin-left: 7rem;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        span.desc {
          font-family: 'Antonio';
          color: black;
          font-size: 25px;
          margin-bottom: 1.5rem;
        }
        span.desc-1 {
          font-family: 'Quicksand';
          color: black;
          font-size: 18px;
        }
        .button {
          cursor: pointer;
          position: relative;
          display: flex;
          width: 19rem;
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
          &:hover {
            background: #282829;
          }
        }
      }
    }
  }
  .marquee{
    position: relative;
    overflow: hidden;
    height: 8rem;
    --offset: 20vw;
    --move-initial: calc(-25% + var(--offset));
    --move-final: calc(-50% + var(--offset));
  .track{
      width: fit-content;
      display: flex;
      position: relative;
      transform: translate3d(var(--move-initial), 0, 0);
      animation: marquee 20s linear infinite;
      animation-play-state: running;
    .content{
      position: relative;
      display: flex;
      flex-direction: row;
      justify-content: flex-start;
      height: 100%;
       box-sizing: border-box;
      span{
        font-family: 'Antonio';
        font-size: 144px;
        font-weight: bolder;
        color: #282829;
      }
      .button-hire{
        position: relative;
        display: flex;
        height: 8rem;
        width: 8rem;
        padding: 0 2rem;
        justify-content: center;
        align-content: center;
        flex-direction: column;
        background: white;
        .img-container{
          position: relative;
          display: flex;
          justify-content: center;
          align-items: center;
          height: 2rem;
          width: 5rem;

          img.flash{
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            width: 1rem;
            height: 1rem;
          }
        }
        span{
          position: relative;
          display: flex;
          width: 100%;
          justify-content: center;
          align-content: center;
          font-family: quicksand;
          font-size: 20px;
          color: #b48645;
        }
          &:hover{
            background: #b48645;
            span{
              color: white;
            }
          }
      }
     }
      @keyframes marquee {
              0% {
                  transform: translate3d(var(--move-initial), 0, 0);
              }
              100% {
                  transform: translate3d(var(--move-final), 0, 0);
                }
      } 
 
    } 
    &:hover{
      .track{
      animation-play-state: paused;
      }
    }
 }
  @media screen and (max-width: 1024px) {
    .slide-one{
      height: 65vh;
      width: 100vw;
      .layer-container{
        width: 100%;
        height: 100%;
        .layer{
          height: 100%;
          width: 100%;
          .desc-container{
            height: 100%;
            width: 100%;
            .desc{
              span{
                text-align: center;
                font-size: 40px;
              }
            }
          }
         
        }
      }
      .button-switch{
        margin: 0;
        margin-left: 1rem;
      }
    }
    .slide-two{
      height: 20%;
    }
  }
}
</style>