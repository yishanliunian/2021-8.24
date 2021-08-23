<template>
  <div id="app">
    <!-- 顶部 -->
      <div class="ding">
          <img src="../assets/切图/logo.png" class="fang">
          <div class="tu">
            <div class="wo"><i class="iconfont icon-user"></i><p>我的</p></div>
            <div class="dao"><i class="iconfont icon-nav"></i><p>导航</p></div>
          </div>
      </div>
      <!-- 轮播图 -->
    <van-swipe class="lun" :autoplay="3000" indicator-color="white">
      <van-swipe-item><img  src="../assets/切图/banner.jpg"></van-swipe-item>
      <van-swipe-item><img  src="../assets/切图/banner1.jpg"></van-swipe-item>
      <van-swipe-item><img  src="../assets/切图/banner2.jpg"></van-swipe-item>
      <van-swipe-item><img  src="../assets/切图/banner3.jpg"></van-swipe-item>
    </van-swipe>

      <!-- 图标 -->
      <div class="biao">
          <ul>
            <li class="li1"><i class="iconfont icon-nav"></i><p>装修方案</p></li>
            <li class="li2"><i class="iconfont icon-case"></i><p>效果图</p></li>
            <li class="li3"><i class="iconfont icon-pics"></i><p>设计师</p></li>
            <li class="li4"><i class="iconfont icon-construction-site"></i><p>装修工地</p></li>
            <li class="li5"><i class="iconfont icon-decorate"></i><p>装修攻略</p></li>
            <li class="li6"><i class="iconfont icon-loans"></i><p>装修贷款</p></li>
            <li class="li7"><i class="iconfont icon-pencle"></i><p>免费预约</p></li>
            <li class="li8"><i class="iconfont icon-ten"></i><p>十秒报价</p></li>
          </ul>
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
  height: 60px;
  
  .fang{
    width: 65px;
    height: 30px;
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
    height: 35px;
    font-size: 10px;
    color: #999999;
    float: left;
    img{
      width: 20px;
      height: 25px;
    }
  }
  .dao{
    width: 40px;
    height: 35px;
    font-size: 10px;
    color: #999999;
   margin-left: 20px;
   float: left;
   .icon-user{
     color: #999999;
       width: 20px;
      height: 25px;
    }
  }
  }
 
}
.lun{
  width: 100%;
  height:150px;
  img{
     width: 360px;
  height: 150px;
  }
}
.biao{
  width: 100%;
  height: 100%;
  ul{
    list-style: none;
    li{
      width: 50px;
      height: 50px;
      border-radius: 50%;
      background: red;
      float: left;
      margin-left: 30px;
      margin-top: 35px;
      text-align: center;
      p{
        
        font-size: 10px;
      }
      i{
      font-size: 29px;
      color:white;
      padding-top: 60px;
      line-height: 65px;
    }
      
    }
    
    .li1{
      background:#39c894;
    }
    .li2{
      background:#feb505;
    }
    .li3{
      background:#eed215;
    }
    .li4{
      background:#00b2b2;
    }
    .li5{
      background:#1b9af7;
    }
    .li6{
      background:#7b72e9;
    }
    .li7{
      background:#ff4351;
    }
    .li8{
      background:#fe8864;
    }
  }
}

</style>

