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
			<slot />
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


