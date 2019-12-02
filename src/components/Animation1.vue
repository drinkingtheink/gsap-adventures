<template>
  <div class="animation-1">
    <h2>Animation 1</h2>

    <div ref="box" class="box"></div>
  </div>
</template>

<script>
export default {
  name: 'Animation1'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.animation-1 {
	.box { 
		height: 60px; 
		width: 60px; 
		background: red; 
	}
}
</style>
