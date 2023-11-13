<script setup lang="ts">
defineProps<{
  headline: string
  bulletOne: string
	bulletTwo: string
	bulletThree: string
}>()
</script>

<template>
<!-- use your card in different ways-->
<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" style="width:100%;">
	<tr>
	<td align="center">
		<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" style="background-color:#F8F8F8;border-collapse: separate;border: 1px solid #F8F8F8;border-radius:8px;width:88%;" class="w100 brd-rad">
		<tr>
		<td align="center" style="font-size:0;padding-top:36px;padding-bottom: 20px;">
			<!--[if mso]>
			<table border="0" cellspacing="0" cellpadding="0" style="width:528px;">
			<tr>
			<td valign="middle" align="center" style="width:215px;">
			<![endif]-->
			<div style="display: inline-block; width: 100%; max-width: 215px; vertical-align: middle;" class="mw100">
			<table cellpadding="0" cellspacing="0" border="0" role="presentation" style="width:100%;">
			<tr>
			<td style="padding-top:20px;">
				<img src="../assets/secondary-phone.png" alt="" width="215" style="border:0;display:block;outline: 0;padding: 0;width:215px;" />
			</td>
			</tr>
			</table>
			</div><!--[if mso]></td><td valign="middle" align="center" style="width:273px;"><![endif]--><div style="display: inline-block; width: 100%; max-width: 273px; vertical-align: middle;" class="mw100">
			<table align="center" cellpadding="0" cellspacing="0" border="0" role="presentation" style="width:85%;">
			<tr>
			<td align="center" valign="top" style="padding-top:20px;">
				<slot name="subHeadline"/>
			</td>
			</tr>
			<tr>
			<td align="center" style="padding-top: 10px;">
				<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" style="width:100%;">
				<tr>
				<td width="16" style="padding:4px 0;">
					<slot name="iconImage"></slot>
				</td>
				<td align="center" style="padding:4px 0;padding-left:10px;">
					<slot name="bulletOne"></slot>
				</td>
				</tr>
				<tr>
				<td width="16" style="padding:4px 0;">
					<slot name="iconImage"></slot>
				</td>
				<td align="center" style="padding:4px 0;padding-left:10px;">
					<slot name="bulletTwo"></slot>
				</td>
				</tr>
				<tr>
				<td width="16" style="padding:4px 0;">
					<slot name="iconImage"></slot>
				</td>
				<td align="center" style="padding:4px 0;padding-left:10px;">
					<slot name="bulletThree"></slot>
				</td>
				</tr>
				</table>
			</td>
			</tr>
			</table>
			</div>
			<!--[if mso]>
			</td>
			</tr>
			</table>
			<![endif]-->
		</td>
		</tr>
		</table>
	</td>
	</tr>
	</table>
	<!--/use your card in different ways-->
</template>