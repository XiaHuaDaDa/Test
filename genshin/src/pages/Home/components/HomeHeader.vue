<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe685;</span>
    </div>
    <div class="header-middle">
      <span class="iconfont search-icon">&#xe67d;</span>
      <div class="kw">输入关键字</div>
      <input type="text" class="header-input" />
    </div>
    <div class="header-right">
      <span>城市</span>
      <span class="iconfont">&#xe688;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~styles/variables.styl';

.header {
  display: flex;
  width: 100%;
	height: .88rem;
	color: #fff;
	background-color: $bgColor;
}

.header .header-left {
	width: .8rem;
	height: 100%;
	text-align: center;
	line-height: .88rem;
}

.header .header-middle {
	position: relative;
	flex: 1;
	margin: .14rem 0;
}

.header .header-middle .search-icon {
	position: absolute;
	top: .13rem;
	left: .2rem;
	color: #e4e7ea;
}

.header .header-middle .kw {
	position: absolute;
	top: .16rem;
	left: .65rem;
	color: #e4e7ea;
}

.header .header-middle .header-input {
	width: 100%;
	height: 100%;
	border-radius: .06rem;
}

.header .header-right {
	min-width: 1.12rem;
	padding: 0 .1rem;
	height: 100%;
	text-align: center;
	line-height: .88rem;
	color: #fff;
}
</style>
