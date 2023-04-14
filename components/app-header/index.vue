<template>
	<div class="app-header">
		app-header
	</div>
</template>
<script lang="ts" setup>
export interface IProps {
	title?: string;
}
const props = withDefaults(defineProps<IProps>(),{
	title:'',
})
</script>
<style lang="scss"></style>