<template>
  <div id="app">
      <div class="ding">
          <img src="../assets/切图/logo.png" class="fang">
          <div class="tu">
            <div class="wo"><img src="../assets/img/2.png" ><p>我的</p></div>
            <div class="dao"><img src="../assets/img/1.png"><p>导航</p></div>
          </div>
      </div>
  </div>
</template>
<style lang="scss">
*{
  margin: 0;
  padding: 0;
}
#app{
  width: 100%;
  height: 100%;
}
.ding{
  width: 100%;
  height: 82px;
  background: red;
  .fang{
    width: 120px;
    height: 50px;
    margin-left: 18px;
    margin-top: 16px;
    margin-bottom: 16px;
  }
  .tu{
      position: fixed;
      top: 16px;
      right: 6px;
      text-align: center;
      
     .wo{
    width: 40px;
    height: 65px;
    font-size: 10px;
    color: #999999;
    float: left;
    img{
      width: 40px;
      height: 45px;
    }
  }
  .dao{
    width: 40px;
    height: 65px;
    font-size: 10px;
    color: #999999;
   margin-left: 20px;
   float: left;
   margin-top: 10px;
    img{
      width: 40px;
      height: 33px;
    }
  }
  }
 
}
</style>

