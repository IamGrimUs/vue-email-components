<template>
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" width="600" style="background-color: #ffffff;border-radius:8px;width:100%;max-width: 600px;">
	<tr>
	<td align="center" style="padding-top:40px;">
		<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" width="600" style="width:100%;">
		<tr>
		<td align="center" style="padding-bottom:50px;">
			<slot name="heroBlock" />
			<slot name="copyBlock" />
			<slot name="detailsBlock" />
		</td>
		</tr>
		</table>
	</td>
	</tr>
	</table>
</template>