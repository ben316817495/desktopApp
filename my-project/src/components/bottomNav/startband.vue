<template>
	<transition name="slide-fade">
		<div class="startband" v-show="startband">
			<div class="">
				<ul class="setUpPanel">
					<li><router-link to="/">首页</router-link></li>
					<li><div class="leftspliter"></div></li>
					<li><router-link to="/folderPanel">文件夹</router-link></li>
					<li><router-link to="/login">登陆页面</router-link></li>
					<li><router-link to="/lockPage">锁屏页</router-link></li>
				</ul>
			</div>
		</div>
	</transition>
</template>

<script>
	export default {
		props: ['startband'],
		data(){
			return {
			}
		},//data()
	}	
</script>
