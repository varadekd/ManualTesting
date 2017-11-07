<template>
		<ul id="panel">
			<li>
				<img src="../assets/build.png" v-on:click="build">
			</li>
			<li>
				<img src="../assets/analysis.png" v-on:click="analysis">
			</li>
			<li>
				<img src="../assets/sync.png" v-on:click="sync">
			</li>
			<li>
				<img src="../assets/tool.png" v-on:click="tool">
			</li>
			<li>
				<img src="../assets/device.png" v-on:click="device">
			</li>
		</ul>
</template>

<script>
	export default{
		name:'SidePanel',
		methods:{
			build: function(){
				return alert('This is a build button');
			},
			analysis: function(){
				return alert('This is a analysis button');
			},
			sync: function(){
				return alert('You can refresh using this');
			},
			tool: function(){
				return alert('This button is a tool icon');
			},
			device: function(){
				return alert('This is for device info');
			}
		}
	}
</script>

<style scoped>
	#panel{
			border: 0 solid;
			margin: 0;
			padding: 0;
			text-align: center;
			width: 32px;
			height: auto;
			background: #ADD8E6;
		}

		#panel li{
			list-style-type: none;
			display: block;
			margin-top: 5px;
		}

		#panel li img{
			width: 20px;
			text-align: center;
		}

		#panel li:hover{
			background: #E5E5FF;
		}
</style>