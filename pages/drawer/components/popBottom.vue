<template>
	<myp-drawer ref="pop" pos="bottom" width="750rpx" height="x-1000rpx" @overlayClicked="hide">
		<bottom></bottom>
		<myp-xbar bgType="primary" boxStyle="width:750rpx;"></myp-xbar>
	</myp-drawer>
</template>

<script>
	import bottom from './bottom.vue'
	
	export default {
		components: {
			bottom
		},
		methods: {
			hide() {
				this.$refs['pop'].hide()
			},
			show() {
				this.$refs['pop'].show()
			}
		}
	}
</script>

<style lang="scss" scoped>
</style>
