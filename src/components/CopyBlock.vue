<script setup lang="ts">
defineProps<{
	headline: string
}>()
</script>

<template>
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" style="width:68%;" class="w88">
	<tr>
	<td align="center" style="padding-top:24px;padding-bottom: 60px;">
		<h1 style="margin:0;padding:0;color:#4d4d4d;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif; font-size:28px;font-weight:700;line-height:38px;text-align:center;" class="txt-lft">
			<slot name="headline" />
		</h1>
		<p style="margin:0;padding:0;margin-top:10px;color:#303030;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif; font-size:16px;line-height:22px;text-align:center;" class="txt-lft">
			<slot name="bodyCopy" />
		</p>
	</td>
	</tr>
	</table>
</template>