<template>
  <div>
    <div class="right_top">
        <div class="card top_left">
          <span class="title">入门</span>
          <ul>
            <li><a href="#">在5分钟内生成您的第一个应用</a></li>
            <li><a href="#">针对问题的一些提示和技巧，在最大程度上提升工作效率</a></li>
            <li><a href="#">在5分钟内生成您的第一个应用</a></li>
            <li><a href="#">针对问题的一些提示和技巧，在最大程度上提升工作效率</a></li>
            <li><a href="#">在5分钟内生成您的第一个应用</a></li>
            <li><a href="#">针对问题的一些提示和技巧，在最大程度上提升工作效率</a></li>
          </ul>
        </div>
        <div class="card top_right">
          <span class="title">系统公告</span>
          <ul>
            <li><a href="#">在5分钟内生成您的第一个应用</a></li>
            <li><a href="#">针对问题的一些提示和技巧，在最大程度上提升工作效率</a></li>
            <li><a href="#">在5分钟内生成您的第一个应用</a></li>
            <li><a href="#">针对问题的一些提示和技巧，在最大程度上提升工作效率</a></li>
            <li><a href="#">在5分钟内生成您的第一个应用</a></li>
            <li><a href="#">针对问题的一些提示和技巧，在最大程度上提升工作效率</a></li>
          </ul>
        </div>
      </div>
    <div class="right_bottom">
        <div class="card bottom_left">
          <span class="title">最近</span>
          <ul>
            <li><img src="../assets/4.jpg" alt=""><span>华润项目名称</span></li>
            <li><img src="../assets/4.jpg" alt=""><span>19楼完成项目名称</span></li>
            <li><img src="../assets/4.jpg" alt=""><span>万科之城项目名称</span></li>
            <li><img src="../assets/4.jpg" alt=""><span>USA项目</span></li>
            <li><img src="../assets/4.jpg" alt=""><span>还有啥项目</span></li>
          </ul>
          <div class="btn_group">
            <a class="btn danger">新建</a>
            <a class="btn success">打开</a>
          </div>

        </div>
        <div class="card bottom_center">
          <img src="../assets/view1.png" alt="">
        </div>
        <div class="card bottom_right">
          <img src="../assets/tab1.png" alt="" width="100%">
        </div>
      </div>
  </div>
</template>

<script>
  export default {
    name: 'ContHome',
    data () {
      return {
        msg: 'head'
      }
    }
  }
</script>
<style scoped>
  .right_top{
    display: flex;
    flex-direction: row;
  }
  .right_top .top_right,.top_left{
    width:50%;
  }
  .right_top .top_right,.top_left a{
    color:rgb(81,99,120)
  }
  .right_top .top_right a{
    color:rgb(76,144,255);
  }
  .right_bottom{
    display: flex;
    flex-direction: row;
  }
  .right_bottom ul li{
    display: flex;
    align-items: center;
    height:38px;
    line-height:38px;
  }
  .right_bottom ul li span{
    margin-left:10px;
  }
  .right_bottom .bottom_left{
    width:380px;
    position:relative;
  }
  .right_bottom .bottom_left .btn_group{
    position:absolute;
    width:75%;
    bottom:30px;
    margin:0 auto;
  }
  .right_bottom .bottom_center{
    width:28%;
  }
  .right_bottom .bottom_right{
    width:606px;
  }
</style>
