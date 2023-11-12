<script setup lang="ts">
defineProps<{
  bodyOne: string
  bodyTwo: string
	headline: string
}>()
</script>

<template>
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" style="width:68%;" class="w88">
	<tr>
	<td align="center" style="padding-top:24px;padding-bottom: 60px;">
		<h1 style="margin:0;padding:0;color:#4d4d4d;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif; font-size:28px;font-weight:700;line-height:38px;text-align:center;" class="txt-lft">{{headline}}</h1>
		<p style="margin:0;padding:0;margin-top:10px;color:#303030;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif; font-size:16px;line-height:22px;text-align:center;" class="txt-lft">{{ bodyOne }} <br class="mblhd" />{{ bodyTwo }}<span style="font-size:8px;line-height: 0;vertical-align: 6px;">&reg;</span>&nbsp;card.</p>
	</td>
	</tr>
	</table>
</template>