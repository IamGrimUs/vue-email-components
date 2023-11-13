<script setup lang="ts">
defineProps<{
	tableWidth: string
	className: string
	paddingTop: string
	paddingBottom: string
}>()
</script>

<template>
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" :style="{width:tableWidth}" :class="{className}">
	<tr>
	<td align="center" :style="{'padding-top':`${paddingTop}px`, 'padding-bottom': `${paddingBottom}px`}">
			<slot name="headline" />
			<slot name="bodyCopy" />
	</td>
	</tr>
	</table>
</template>