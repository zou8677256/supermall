<template>
	<div >
		  <div id='tab-bar'>
			  <slot></slot>
		  </div>
	</div>
</template>

<script>
	export default {
			name: "TabBar"
		}
</script>

<style>
	#tab-bar {
		 display: flex;
		 background-color: lavender;
		 
		 position: fixed;
		 left: 0;
		 right: 0;
		 bottom: 0;
		 box-shadow: 0 -4px 1px rgba(100,100,100,0.2);
	}
	
	.tab-bar-item{
		 flex:1;
		 text-align: center;
		 height: 49px;
	}
	.tab-bar-item img{
		width: 23px;
		height: 23px;
		vertical-align:middle ;
		margin-top: 3px;
	}
</style>
