<template>
	<div class="page-not-find">page-not-find  404</div>
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