<script setup lang="ts">
	defineProps<{
		tableWidth: string
	}>()
</script>

<template>
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" :style="{width:tableWidth}">
	<tr>
	<td>
		<!--[if mso]><center><![endif]-->
			<slot />
		<!--[if mso]></center><![endif]-->
	</td>
	</tr>
	</table>
</template>