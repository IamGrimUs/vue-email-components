<template>
	<!--footer-->
	<table cellpadding="0" cellspacing="0" border="0" style="width:100%;max-width:600px;">
	<tr>
	<td align="center" style="padding-top:42px;">
		<table align="center" cellpadding="0" cellspacing="0" border="0" style="width:90%">
		<tr>
		<td>
			<!--[if mso]><center><![endif]-->
			<slot name="footerImage"></slot>
			<!--[if mso]></center><![endif]-->
		</td>
		</tr>
		<tr>
		<td align="center">
			<slot name="disclaimerCreditCard"></slot>
		</td>
		</tr>
		<tr>
		<td align="center" style="padding:20px 0;">
			<table align="center" cellpadding="0" cellspacing="0" border="0" style="width:84%" class="w100">
			<tr>
			<td align="center"><hr style="border-width: 0; background: #E6E6E6; color: #E6E6E6; height:1px;">
			</td>
			</tr>
			</table>
		</td>
		</tr>
		<tr>
		<td align="center">
			<slot name="marketingFooterCreditCardAbandon"></slot>
		</td>
		</tr>
		</table>
	</td>
	</tr>
	</table>
	<!--/footer-->
</template>