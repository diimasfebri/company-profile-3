<template>
<div class="container">
 <div class="top">
    <div class="left">
      <span class="button">SERVICES</span>
      <span class="button">OUR WORK</span>
      <span class="button">OUR PROCESS</span>
      <span class="button">ABOUT US</span>
    </div>
    <div class="center">
      <div class="image"></div>
    </div>
    <div class="right">

      <span class="button-hire"> HIRE US</span>
    </div>
 </div>
</div> 


</template>



<style lang="scss" scoped>
.container{
  position: relative;
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: flex-start;
  .top{
    position: relative;
    width: 100%;
    height: 3rem;
    display: flex;
    color:red; 
    margin-top: 2rem;
    .left{
      position: relative;
      display: flex;
      flex-direction: row;
      width: 40rem;
      justify-content: flex-start;
      align-items: flex-start;
      margin-left: 2.5rem;
      span.button{
        font-family: 'Antonio';
        color: black;
        font-size: 16px;
        font-weight: 600;
        margin: 14px;
      }
    }
    .center{
      position: relative;
      width: 30rem;
      background: red;
      left: 3.5rem;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .right{
      position: relative;
      display: flex;
      width: 100%;
      flex-direction: row;
      justify-content: flex-end;
      align-items: center;
      margin-right: 2.5rem;
      span.button-hire{
        width: 3rem;
        height: 1rem;
      }
    }
    
  }
}

</style>




<style lang="scss">
::-webkit-scrollbar {
  display: none;
}
html, body {
  margin: 0;
  padding: 0;
  font-size: 24px;
  overflow-x: hidden;
}
</style>