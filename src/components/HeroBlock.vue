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
		<a href="%%"><img :src="'src/assets/' + img" :alt="alt" :width="wdth" style="display:block; border:0; outline:0; padding:0;font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#4d4d4d;width:150px;margin:0 auto;" class="lft-algn" /></a>
		<!--[if mso]></center><![endif]-->
	</td>
	</tr>
	</table>
</template>