<template>
  <header class="header">
  	<a href="" class="header-left iconfont icon-fanhui"></a>
  	<div class="header-center">
  		<a href="">
  			<i class="center-left iconfont icon-fangdajing"></i>
  			<span class="center-right">输入城市/景点/游玩主题xxxxxx</span>
  		</a>
  	</div>
  	<div class="header-right">
  		<a href="">
  			<span class="city">北京</span>
  		</a>
  	</div>
  </header>
</template>

<script>
export default {

  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>

.header {
	position: relative;
	width:100%;
	height:.88rem;
	background:#00bcd4;
	text-align: center;
	color: #fff;
}

.header-left {
	float:left;
	font-size: .36rem!important;
	line-height: .88rem;
	color:#fff;
	font-weight: 900;
	padding:0 .2rem;
}

.header-center {
    background: #fff;
    width: 5.38rem;
    line-height: .6rem;
    border-radius: .06rem;
	float: left;
	margin: .14rem 0;
}

.header-center a {
	height: .6rem;
	display:block;
	line-height: .6rem;
	text-align: left;
	padding-left: .2rem;
}

.center-left {
	font-size: .32rem!important;
	color: #e4e7ea;
	font-weight: 900;

}

.center-right {
	font-size: .28rem;
	color: #e4e7ea;
}

.header-right{
	float: left;
	height:100%; 
}

.header-right a{
	line-height: .88rem;	
}

.city {
	font-size: .28rem;
	color:#fff;
	font-weight: 100;
	padding-left:.22rem;
}

.city:after {  
    border-left: 6px solid transparent;  
    border-right: 6px solid transparent;  
    border-top: 6px solid #fff;  
    content: "";  
    position: relative;      
    width: 0;  
    top:24%;
    left:10%;
}  
</style>