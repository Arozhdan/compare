<template>
	<div class="sidebar">
		<div class="compare-type-wrapper">
			<label class="compare-type-item">Все параметры
				<input type="radio" checked="checked" name="compare-type-item">
				<span class="checkmark"></span>
			</label>
			<label class="compare-type-item">Только отличающиеся
				<input type="radio" name="compare-type-item">
				<span class="checkmark"></span>
			</label>
		</div>
	</div>
</template>

<script>
    export default {
        name: "Sidebar"
    }
</script>

<style scoped>
	@import "../assets/style/modules.css";
	.compare-type-item{
		margin-bottom: 30px;
	}

</style>