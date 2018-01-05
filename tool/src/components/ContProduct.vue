<template>
  <div>
    <div class="mycard">
        <div class="card_title">
          <div class="card_progress">
            <div class="progressbar">1</div>
            <div class="progressbar">2</div>
            <div class="progressbar">3</div>
          </div>
          <div class="card_btn">
            <!--<a class="mybtn pro">上一步</a>-->
            <a class="mybtn next">下一步</a>
          </div>
        </div>
        <div class="card_body">
          <div class="body_cont">
            <div>
              <div>
                <img src="../assets/share.png" alt="">
              </div>
              <div>产品+版本</div>
            </div>
            <div>
              <div>
                <img src="../assets/friend.png" alt="">
              </div>
              <div>产品+版本</div>
            </div>
            <div>
              <div>
                <img src="../assets/share.png" alt="">
              </div>
              <div>产品+版本</div>
            </div>
            <div>
              <div>
                <img src="../assets/friend.png" alt="">
              </div>
              <div>产品+版本</div>
            </div>
            <div>
              <div>
                <a>+</a>
              </div>
            </div>
          </div>
          <div class="alert">
            <div class="alert_cont">
              <div>
                <span class="title">选择厂商</span>
                <div>
                  <div><input type="checkbox">标准输出</div>
                  <div><input type="checkbox">标准输出</div>
                  <div><input type="checkbox">标准输出</div>
                  <div><input type="checkbox">标准输出</div>
                  <div><input type="checkbox">标准输出</div>
                  <div><input type="checkbox">标准输出</div>
                  <div><input type="checkbox">标准输出</div>
                </div>
              </div>
              <div>
                <span class="title">选择产品</span>
                <div>
                  <div><input type="checkbox">标准输出</div>
                </div>
              </div>
              <div>
                <span class="title">选择版本</span>
                <div>
                  <div><input type="checkbox">标准输出</div>
                </div>
              </div>
            </div>
            <div class="alert_btn">
              <a></a>
            </div>
          </div>

        </div>
      </div>
    </div>
</template>
<script>
  export default {
    name: 'ContProduct',
    data () {
      return {
        msg: 'ContentProduct'
      }
    }
  }
</script>
<style scoped>
  .mybtn{
    display:inline-block;
    width:170px;
    height:56px;
    line-height:56px;
    background-color:#BCCBDD;
    color:#fff;
    text-align: center;
    border-radius:6px;
  }
  .mycard{
    margin:17px;
    border:1px solid #dfebf9;
    border-radius: 8px;
    background-color:#fff;
    /*padding:30px 40px;*/
    box-sizing: border-box;
  }
  .card_title{
    padding:30px 40px;
    height:78px;
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    border-bottom:1px solid #dfebf9;
  }
  .card_title .card_progress{
    width:600px;
    height:10px;
    background-color:#88E9CA;
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }
  .card_title .card_progress .progressbar{
    width:52px;
    height:52px;
    border-radius: 50%;
    border:10px solid #2BCC97;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color:#fff;
    font-size:28px;
  }
  .body_cont{
    padding:24px 0;
    display:flex;
    flex-direction: row;
    flex-wrap: wrap;
  }
  .body_cont>div{
    padding:24px 40px;
  }
  .body_cont>div>div:nth-of-type(1){
    width:248px;
    height:106px;
    /*border:1px dashed #0b7cff;*/
    background-color:#eee;
  }
  .body_cont>div>div:nth-of-type(2){
    text-align: center;
  }
  .body_cont>div a{
    display: flex;
    height:100%;
    justify-content: center;
    align-items: center;
    font-size:50px;
    color:#0b7cff;
    text-align: center;
  }

  .alert_cont{
    display: flex;
    flex-direction: row;
    border:1px solid #dfebf9;
    width:930px;
    border-radius:8px;
    font-size:18px;
    color:rgb(127,146,166);
  }
  .alert_cont>div{
    width:310px;
    display:flex;
    flex-direction: column;
    align-items: center;
    padding:20px 0;
    border-left:1px solid #dfebf9;
  }
  .alert_cont>div .title{
    font-size:24px;
    color:rgb(127,146,166);
    margin-bottom:25px;
  }
  .alert_cont>div:nth-of-type(1){
    border:none;
  }
  .alert_cont>div>div{
    display:flex;
    flex-direction: column;
  }
</style>
