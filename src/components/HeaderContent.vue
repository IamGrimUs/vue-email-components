<script setup lang="ts">
defineProps<{
  img: string
}>()
</script>

<template>
  <!--header-->
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" width="600" style="width:100%;">
	<tr>
	<td align="center" style="padding:24px 0;">
		<!--[if mso]>
		<table align="center" border="0" cellspacing="0" cellpadding="0" style="width:600px;">
		<tr>
		<td valign="top" align="center">
		<![endif]-->
		<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" style="width:64%;" class="w88">
		<tr>
		<td>
			<!--[if mso]><center><![endif]-->
			<a href="%%"><img v-bind:src="'src/assets/' + img" alt="Prosper" width="113" style="display:block; border:0; outline:0; padding:0;font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#4d4d4d;width:113px;margin:0 auto;" class="lft-algn" /></a>
			<!--[if mso]></center><![endif]-->
		</td>
		</tr>
		</table>
		<!--[if mso]>
		</td>
		</tr>
		</table>
		<![endif]-->
	</td>
	</tr>
	</table>
	<!--/header-->
</template>


