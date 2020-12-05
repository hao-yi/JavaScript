/*
	小结
*/
2020/12/1
####
待续
####
2020/12/3
js脚本有俩种引入方式
	嵌入内部： {
		<script>
			// js
		</script>
	},
	外部引入: {
		<script src="index.js"></script>
	}
script H5为其制定了6个属性
	type src async defer charset language

	再不使用 async defer 属性的情况下js脚本会按照由上到下的顺序执行

	defer：延迟脚本，到文档解析遇到</html>时才会执行，外部脚本
	async: 异步脚本，加载完立即执行，但加载的时间不确定