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
      <!-- 全屋装修 -->
      <div class="quan">
        <p class="shang"><span class="xiu">全屋装修</span><span class="bao">包设计</span>
        <span class="bao">包主材</span><span class="bao">包水电</span>
        <span class="bao">包施工</span>
        </p>
        <p class="lun2">
           <van-swipe class="lun" :autoplay="3000" indicator-color="white">
          <van-swipe-item><img  src="../assets/切图/img1.jpg"></van-swipe-item>
          <van-swipe-item><img  src="../assets/切图/house_info.jpg"></van-swipe-item>
         </van-swipe>
        </p>
         <p class="xia">
           <i class="iconfont icon-zero"><span>0增项，标准施工</span></i>
           <i class="iconfont icon-protection-fill"><span>杜绝项目外包</span></i>
           <i class="iconfont icon-price"><span>装修贷款</span></i>
         </p>
      </div>
      <!-- 装修预定 -->
      <div class="zhuang">
          <p class="shang"><span class="xiu">装修预订</span>
          <span class="bao">免费上门量房，设计方案满意为止</span>
        </p>
        <p class="inp">
          <input type="text" placeholder="小区名">
        </p>
        <p class="inp">
          <input type="text" placeholder="手机号">
        </p>
        <p class="inp">
          <input type="text" placeholder="建筑面积">
        </p>
        <p class="inp">
          <button class="btn">立即申请</button>
        </p>
      </div>
  </div>
</template>
<style lang="scss">
* {
  margin: 0;
  padding: 0;
}
#app {
  width: 100%;
  height: 800px;
  background: #cccccc;
}
.ding {
  width: 100%;
  height: 60px;
  background: white;

  .fang {
    width: 65px;
    height: 30px;
    margin-left: 18px;
    margin-top: 16px;
    margin-bottom: 16px;
  }
  .tu {
    position: fixed;
    top: 16px;
    right: 6px;
    text-align: center;

    .wo {
      width: 40px;
      height: 35px;
      font-size: 10px;
      color: #999999;
      float: left;
      img {
        width: 20px;
        height: 25px;
      }
    }
    .dao {
      width: 40px;
      height: 35px;
      font-size: 10px;
      color: #999999;
      margin-left: 20px;
      float: left;
      .icon-user {
        color: #999999;
        width: 20px;
        height: 25px;
      }
    }
  }
}
.lun {
  width: 100%;
  height: 150px;
  img {
    width: 360px;
    height: 150px;
  }
}
.biao {
  width: 100%;
  height: 220px;
  background: white;
  ul {
    list-style: none;
    li {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      background: red;
      float: left;
      margin-left: 30px;
      margin-top: 35px;
      text-align: center;
      p {
        font-size: 10px;
      }
      i {
        font-size: 29px;
        color: white;
        padding-top: 60px;
        line-height: 65px;
      }
    }

    .li1 {
      background: #39c894;
    }
    .li2 {
      background: #feb505;
    }
    .li3 {
      background: #eed215;
    }
    .li4 {
      background: #00b2b2;
    }
    .li5 {
      background: #1b9af7;
    }
    .li6 {
      background: #7b72e9;
    }
    .li7 {
      background: #ff4351;
    }
    .li8 {
      background: #fe8864;
    }
  }
}
.quan {
  width: 100%;
  height: 300px;
  background: white;
  .shang {
    width: 100%;
    height: 30px;
    margin-top: 10px;

    .xiu {
      font-size: 20px;
      color: black;
      margin-left: 10px;
    }
    .bao {
      font-size: 15px;
      color: #999999;
      margin-left: 15px;
    }
  }
  .xia {
    margin-top: 36px;
    width: 100%;
    font-size: 15px;
    i {
      color: #39c894;
      span {
        color: black;
      }
    }
  }
  .lun2 {
    width: 100%;
    height: 150px;
    margin-top: 30px;
  }
}
.zhuang {
  width: 100%;
  height: 300px;
  background: white;
  text-align: center;
  .shang {
    width: 100%;
    height: 30px;
    margin-top: 10px;
    .xiu {
      font-size: 20px;
      color: black;
      margin-left: 10px;
    }
    .bao {
      font-size: 15px;
      color: #999999;
      margin-left: 15px;
    }
  }
  .inp{
    margin-top: 25px;
    input{
      width: 300px;
      height: 31px;
      border: 1px solid #999999;
      color: #999999;
    }
    .btn{
      width: 300px;
      height: 31px;
      background: #feb505;
      color: white;
      border: 1px solid white;
    }
  }
}
</style>

