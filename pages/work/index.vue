
<template>
  <div class="body-container">
    <div class="slide-one">
      <img
        class="bg-content"
        src="https://images.unsplash.com/photo-1514483127413-f72f273478c3?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80"
      />
      <div class="desc-container">
        <div class="desc">
          <span>OUR WORK</span>
        </div>
      </div>
    </div>
    <div class="slide-two">
      <img
        class="bg-content"
        src="https://images.unsplash.com/photo-1517816743773-6e0fd518b4a6?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80"
      />
      <div class="button-container">
        <div class="desc">
          <span>RECENT WORK</span>
        </div>
        <div class="item">
          <span>For the last 6 years, we have been supplying Hangar 24 with world class and designs and top quality 
            apparel that has catapulted their retail sales
          </span>
        </div>
        <div class="button">
          <span class="desc">HIRE US</span>
        </div>
      </div>
    </div>
    <div class="slide-three">
      <img
        class="bg-content"
        src="https://images.unsplash.com/photo-1517816743773-6e0fd518b4a6?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80"
      />
      <div class="desc-container">
        <span>SCROLL TO SEE MORE COOL SH*T -- ></span>
        </div>
      </div>
      <div class="slide-four">
        <img
        class="bg-content"
        src="https://images.unsplash.com/photo-1496293455970-f8581aae0e3b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=701&q=80"
        />
      </div>
      <div class="slide-five">
        <img
        class="bg-content"
        src="https://images.unsplash.com/photo-1520529890308-f503006340b4?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=747&q=80"
        />
      </div>
  </div>
  </div>
    
</template>

<style lang="scss" scoped>
.body-container {
  position: relative;
  width: 100vw;
  min-height: 100vh;
  min-height: calc((var(--vh, 1vh) * 100));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  .slide-one {
    position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    img.bg-content {
      position: absolute;
      width: 100vw;
      height: 100vh;
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
        display: flex;
        width: 11rem;
        height: 1.5rem;
        background: white;
        justify-content: center;
        align-items: center;
        margin-top: 0.5rem;
        span {
          color: black;
          font-family: Antonio;
          font-size: 0.8rem;
          font-weight: 900;
        }
      }
    }
  }
  .slide-two {
    position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    img.bg-content {
      position: absolute;
      width: 100vw;
      height: 100vh;
    }
    .button-container {
      position: relative;
      display: flex;
      width: 100%;
      height: 100%;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      .desc{
        font-family: 'Antonio';
        font-size: 100px;
      }
      .item{
        font-family: 'Antonio';
        position: relative;
        font-size: 18px;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
      }
      .button {
        position: relative;
        display: flex;
        width: 9.5rem;
        height: 1.5rem;
        background: #b48645;
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
      }
    }
  }
  .slide-three {
    position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    img.bg-content {
      position: absolute;
      width: 100vw;
      height: 100vh;
    }
    .desc-container {
      position: relative;
      display: flex;
      width: 100%;
      height: 100%;
      padding: 5rem 4rem;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
      span.desc {
        font-family: Antonio;
        color: white;
        font-size: 0.8rem;
        font-weight: 900;
        .menu-list {
          position: relative;
          display: flex;
          width: 100%;
          height: 100%;
          flex-direction: column;
          justify-content: flex-start;
          align-items: flex-start;
          .menu-item {
            position: relative;
            display: flex;
            border-top: 1px solid black;
            width: 4rem;
            height: 4rem;
          }
        }
      }
    }
  }
}
.slide-four{
  position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    img.bg-content {
      position: absolute;
      width: 100vw;
      height: 100vh;
    }
}
.slide-five{
  position: relative;
    width: 100vw;
    height: 100vh;
    display: flex;
    img.bg-content {
      position: absolute;
      width: 100vw;
      height: 100vh;
    }
}
</style>