<script setup lang="ts">
defineProps<{
  img: string
	alt: string
	wdth: number
}>()
</script>

<template>
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" style="width:88%;">
	<tr>
	<td>
		<!--[if mso]><center><![endif]-->
		<a href="%%">
			<slot />
		</a>
		<!--[if mso]></center><![endif]-->
	</td>
	</tr>
	</table>
</template>