<template>
<div class="bg">
  <div class="mh">
    <div class="login_body">
      <div class="login_main">
        <form class="login_form" action="javascript:;" method="post">
          <h3>团队管理中心</h3>
          <h5 style="padding-bottom: 10px">Team Management Center</h5>
          <!-- 帐号登录 -->
          <div id="MobileBox" class="item-box">
            <div class="dw">
              <div class="input-group user-name">
                <span class="input-group-addon">
                  <i class="icon-user"></i>
                </span>
                <input type="text" name="username" class="form-control" placeholder="请输入帐号">
              </div>
            </div>
            <div class="dw">
              <div class="input-group password"> 
                <span class="input-group-addon">
                  <i class="icon-lock"></i>
                </span>
              <input type="password" name="password" class="form-control" placeholder="请输入密码">
              </div>
            </div>
            <div class="login_btn_panel">
            <button class=" btn btn-primary btn-block btn-lg" data-ajax="post" type="submit" data-callback="success">登录</button>
            <div class="check-tips"></div>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</div>
</template>

<script>
</script>

<style>
@import '../assets/css/zui.css';
.bg{
  position: fixed;
  width: 100%;
  height: 100%;
  background-size: 100% 100%;
  background-image: url('../assets/img/bg.jpg');
  background-repeat: no-repeat;
}
.mh{
  position:fixed;
  left:0;
  z-index:555;
  height:100%;
  width:100%;
  background:rgba(0, 0, 0, 0.295);
}
.login_body{
  width: 400px;
  background-color: rgba(38,43,54,.9);
  margin-top: -300px;
  margin-left: -200px;
  border-radius: 5px;
  position: absolute;
  top: 50%;
  left: 50%;
  padding: 20px;
}
.login_body{
  position: relative;
}
.login_form{
  width: 370px;
  margin: 0 auto;
  padding: 20px 30px 13px 23px;
}
.login_form h3{
  font-size: 26px;
  font-weight: 500;
  padding:0;
  line-height: 30px;
  text-align: center;
  color: #259dab;
}
.login_form h5{
  font-size: 20px;
  font-weight: 400;
  line-height: 30px;
  text-align: center;
  color: #259dab;
  border-bottom: 1px solid #555;
}
.login_form .item-box{
  margin-top: 18px;
}
.login-form .input-group{
  width: 319px;
  margin-bottom: 15px;
  border-radius: 4px;
  position: relative;
  display: table;
  border-collapse: separate;
}
.login-form .input-group .input-group-addon{
  width: 43px;
  border: none;
  background: #fff;
}
.login-form .input-group .input-group-addon i{
  color:rgba(38,43,54,.9);
  font-size:24px
  }
.dw{
  height: 50px;
}
</style>
