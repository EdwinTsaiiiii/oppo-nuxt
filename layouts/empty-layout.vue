<template>
	<div class="home">
		<!-- 空白布局 -->
		<slot></slot>
	</div>
</template>
<script lang="ts" setup>
export interface IProps {
	title: string;
}
const props = withDefaults(defineProps<IProps>(),{
	title:'',
})
</script>
<style lang="scss"></style>