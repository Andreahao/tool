<template>
  <div class="hello">
    <nav class="myheader">
      <div class="container">
        <div class="head">
          <div class="logo">
            <!--公司logo-->
            <img src="../assets/logo.png" alt="">
          </div>
          <div class="active">
            <a><img src="../assets/6.jpg" alt=""><span>新建</span></a>
            <a><img src="../assets/6.jpg" alt=""><span>打开</span></a>
            <a><img src="../assets/6.jpg" alt=""><span>保存</span></a>
            <a><img src="../assets/6.jpg" alt=""><span>发布</span></a>
            <a><img src="../assets/6.jpg" alt=""><span>返回</span></a>
          </div>
          <div class="user">
            <!--用户头像-->
            <img src="../assets/user.png" alt="">
            <span>用户名</span>
          </div>
        </div>
      </div>
    </nav>
    <div class="container">
      <div class="body">
        <div class="body_left">
          <div class="top">
            <img src="../assets/toggle2.png" alt="">
            <span class="line"></span>
          </div>
          <div>
            <ul>
              <li><img src="../assets/6.jpg" alt=""><span>输出项目模型</span></li>
              <li><img src="../assets/5.jpg" alt=""><span>加载标准MODAL</span></li>
              <li><img src="../assets/4.jpg" alt=""><span>调整业务场景</span></li>
              <li><img src="../assets/3.jpg" alt=""><span>调整业务场景</span></li>
              <li><img src="../assets/2.jpg" alt=""><span>系统参数配置</span></li>
              <li><img src="../assets/1.jpg" alt=""><span>调整映射关系</span></li>
            </ul>
          </div>



        </div>
        <div class="body_right">
          <ContHome v-if="false"></ContHome>
          <ContProduct></ContProduct>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
  import ContHome from './ContHome.vue'
  import ContProduct from './ContProduct.vue'
  export default {
    name: 'HelloWorld',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App',
        seehome: false
      }
    },
    components: {
      ContHome,
      ContProduct
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  /*头部*/
  .myheader{
    background-color:#fff;
  }
  .head{
    /*height:104px;*/
    padding:28px 0;
    overflow: hidden;
  }
  .head>div{
    float:left;
  }
  .head .logo{
    width:312px;
  }
  .head .active{
    margin-left:34px;
    display: flex;
    flex-direction: row;
  }
  .active a{
    display:inline-block;
    display:flex;
    align-items: center;
    width:148px;
    height:48px;
    line-height:48px;
    text-align:center;
    justify-content: center;
    /*padding:10px 30px;*/
    text-decoration: none;
    border:1px solid #ccc;
    border-radius: 6px;
    margin-left:18px;
    color:#8a9bad;
    box-sizing: border-box;
  }
  .active a:nth-of-type(1){
    margin-left:0;
  }
  .head .user{
    float:right;
    display: flex;
    align-items: center;
  }
  /*/!*内容*!*/
  .body{
    display:flex;
    flex-direction: row;
  }
  .body_left{
    width:312px;
    margin-top:34px;
    border:1px solid #dfebf9;
    border-radius: 8px;
    background-color:#fff;
    box-sizing: border-box;
    padding:42px 0;
    margin-bottom:34px;
  }
  .body_left .top{
    text-align: center;
    height:52px;
  }
  .body_left .line{
    display:block;
    height:1px;
    width:80%;
    background-color:#dfebf9;
    margin:20px auto;
    /*margin:0 34px;*/
  }
  .body_left ul li{
    padding-left:37px;
    height:62px;
    display: flex;
    align-items: center;
    color:#607185;
    border-left:6px solid #fff;
    /*box-sizing: border-box;*/
  }
  .body_left ul li span{
    margin-left:23px;
    color:rgb(81,99,120);
  }
  .body_left ul li:hover{
    background-color:#f9fafc;
    border-left:6px solid #0b7cff;
    /*box-sizing: border-box;*/
  }
  .body_right{
    width:80%;
    /*margin-left:20px;*/
    margin:17px;
    display: flex;
    flex-direction: column;
  }
  /*.right_top{*/
    /*display: flex;*/
    /*flex-direction: row;*/
  /*}*/
  /*.right_top .top_right,.top_left{*/
    /*width:50%;*/
  /*}*/
  /*.right_top .top_right,.top_left a{*/
    /*color:rgb(81,99,120)*/
  /*}*/
  /*.right_top .top_right a{*/
    /*color:rgb(76,144,255);*/
  /*}*/
  /*.right_bottom{*/
    /*display: flex;*/
    /*flex-direction: row;*/
  /*}*/
  /*.right_bottom ul li{*/
    /*display: flex;*/
    /*align-items: center;*/
    /*height:38px;*/
    /*line-height:38px;*/
  /*}*/
  /*.right_bottom ul li span{*/
    /*margin-left:10px;*/
  /*}*/
  /*.right_bottom .bottom_left{*/
    /*width:380px;*/
    /*position:relative;*/
  /*}*/
  /*.right_bottom .bottom_left .btn_group{*/
    /*position:absolute;*/
    /*width:75%;*/
    /*bottom:30px;*/
    /*margin:0 auto;*/
  /*}*/
  /*.right_bottom .bottom_center{*/
    /*width:28%;*/
  /*}*/
  /*.right_bottom .bottom_right{*/
    /*width:606px;*/
  /*}*/
</style>
