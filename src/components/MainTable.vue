<script setup lang="ts">
	defineProps<{
		tableWidth: string
		paddingTop: string
		paddingBottom: string
	}>()
</script>

<template>
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" :width="tableWidth" :style="{'background-color': '#ffffff', 'border-radius':'8px', width:'100%', 'max-width': `${tableWidth}px`}">
	<tr>
	<td align="center" :style="{'padding-top': `${paddingTop}px`}">
		<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" :width="tableWidth" style="width:100%;">
		<tr>
		<td align="center" :style="{'padding-bottom': `${paddingBottom}px`}">
			<slot name="imageBlock" />
			<slot name="copyBlock" />
			<slot name="detailsBlock" />
		</td>
		</tr>
		</table>
	</td>
	</tr>
	</table>
</template>