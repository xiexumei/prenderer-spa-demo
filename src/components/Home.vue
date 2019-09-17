<template>
	<div>
		我是首页
		<router-link to='/Test'>我是测试</router-link>
		<router-view/>
	</div>
</template>
<script type="text/javascript">
	export default{
		name:'Home'
	}
</script>