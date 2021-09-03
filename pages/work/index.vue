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
          <div class="center-img">
          <img src="https://images.unsplash.com/photo-1503341733017-1901578f9f1e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80" alt="" />
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
      <div class="center-img">
          <img class="product" src="https://img.freepik.com/free-vector/vintage-design-with-ornamental-decorations_52683-57748.jpg?size=626&ext=jpg&ga=GA1.2.2107986711.1630540800" alt="" />
          <img class="product" src="https://images.unsplash.com/photo-1503341338985-c0477be52513?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80" alt="" />
          <img class="product" src="https://images.unsplash.com/photo-1502389614483-e475fc34407e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=334&q=80" alt="" />
          <img class="product" src="https://images.unsplash.com/photo-1564859228273-274232fdb516?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=334&q=80" alt="" />
      </div>
    </div>
      <div class="slide-four">
        <img
        class="bg-content"
        src="https://images.unsplash.com/photo-1496293455970-f8581aae0e3b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=701&q=80"
        />
        <div class="desc-container">
        <span>TESTIMONIALS</span>
        </div>
        <div class="item-container">
        <span>"I love working with ABDS. I really value their design process and the friendship we've developed over the years. It's more than a business transaction. It's a way to mutually propel our business and i've enjoyed the journey so far!"</span> 
        </div> 
      </div>
      <div class="slide-five">
        <img
        class="bg-content"
        src="https://images.unsplash.com/photo-1520529890308-f503006340b4?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=747&q=80"
        />
          <div class="content-container">
           <img src="https://images.unsplash.com/photo-1564859227552-81fde4a1df0b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=751&q=80" alt="">
            <div class="desc-container">
              <span class="desc"> OUR PROCESS </span>
              <span class="desc-1"> We've been at it for a long time and proven process makes sure that you get awesomeness fast! </span> 
              <div class="button">
                <span class="desc-2">LEARN MORE</span>
            </div>
            </div>
          </div>
        </div>
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
      flex-direction: row;
      justify-content: center;
      align-items: flex-start;
      .desc {
        position: relative;
        width: 100%;
        height: 100%;
        display: flex;
        margin-left: 5.5rem;
        justify-content: flex-start;
        align-items: center;
        span {
          position: relative;
          display: flex;
          width: 10%;
          color: white;
          font-family: Antonio;
          font-size: 5rem;
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
      .center-img {
        position: absolute;
        width: 70vw;
        height: 60vh;
        display: flex;
        justify-content: center;
        align-items: center;
      }
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
    .center-img{
      position: relative;
      display: flex;
      flex-direction: row;
      justify-content: flex-start;
      align-items: center;
      width: 120%;
      height: 100%;
      img.product{
        position: relative;
        display: flex;
        height: 6rem;
        width: 4rem;
      }
    }
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
  .desc-container {
      position: relative;
      display: flex;
      font-family: 'Antonio';
      font-size: 25px;
      color: white;
      width: 100%;
      height: 100%;
      padding: 5rem 4rem;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
}
  .item-container{
      position: relative;
      display: flex;
      font-family: 'Antonio';
      font-size: 25px;
      color: white;
      width: 100%;
      height: 100%;
      padding: 5rem 4rem;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
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
    .content-container{
     position: relative;
     display: flex;
     width: 100%;
     height: 100%;
     justify-content: flex-start;
     align-items: center;
     img{
       position: relative;
       display: flex;
       width: 60%;
       height: 50%;
     }
      .desc-container{
        position: relative;
        display: flex;
        font-family: 'Antonio';
        width: 100%;
        height: 100%;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
      }
      .item-container{
        position: relative;
        display: flex;
        font-family: 'Quicksand';
        font-size: 25px;
        color: black;
        width: 100%;
        height: 100%;
        padding: 5rem 4rem;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
      }
      .button {
          position: relative;
          display: flex;
          width: 20rem;
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
</style>