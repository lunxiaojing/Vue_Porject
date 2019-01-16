<template>
  <div id="app">
    <div class="header">
    	<div class="maxWidth clearfix">
    		<div class="head_left fl"><img src="./assets/img/dh.png" class="dh_img"/></div>
    		<div class="head_cent fl">
    			<ul class="headUl clearfix">
			        <li class="fl">
			          	<router-link :to="{path:'/home'}">
			            	<i class="icon iconfont icon-liuliangyunpingtaitubiao02"></i>
			            	备课
			          	</router-link>
			        </li>
			        <li class="fl">
			          	<router-link :to="{path:'/about'}">
			            	<i class="icon iconfont icon-gongcheng-"></i>
			            	题库
			          	</router-link>
			        </li>
			        <li class="fl">
			          	<router-link :to="{path:'/members'}">
			            	<i class="icon iconfont icon-fl-renyuan"></i>
			            	课题报告
			          	</router-link>
			        </li>
			        <li class="fl">
			          	<router-link :to="{path:'/management/zcfgl'}">
			            	<i class="icon iconfont icon-tiaoshi"></i>
			            	个人中心
			          	</router-link>
			        </li>
			    </ul>
    		</div>
    		<div class="head_right fl">
    			<p>
    				<!--<i-button type="primary">Primary</i-button>-->
    				<span>Alice</span>
    				<span>教师</span>
    			</p>
    		</div>
    	</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
@import url("http://at.alicdn.com/t/font_526979_2hi6t3g6j4h.css");
@import url('style/base.css');
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.header{
	width: 100%;
	height: 70px;
	line-height: 70px;
	background: cadetblue;
}
.dh_img{
	display: block;
	vertical-align: middle;
	padding: 15px 0;
}
.headUl{
	margin-left: 50px;
}
.headUl li{
  height: 70px;
  line-height: 70px;
}
a.router-link-active {
  border-top:3px solid #EFF9FE;
  color: #EFF9FE;
}
.headUl a {
  padding: 23px 50px;
  color: #FFFFFF;
  font-size: 16px;
}
</style>
