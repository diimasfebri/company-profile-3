<template>
<div class="body-container"> 
  <div class="background">
    <img class="bg-content" src="https://images.unsplash.com/photo-1479888230021-c24f136d849f?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80">
    <div class="semua">test</div>
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
 .background{
   position: relative;
   width: 100vw;
   height: 100vh;
   display: flex;
    img.bg-content{
      position: absolute;
      width: 100vw;
      height: 100vh;
    }
    .semua{
      position: relative;
      display: flex;
      width: 100%;
      height: 100%;
      justify-content: center;
      align-items: center;
      color: white;
    }
 }
}
</style>
