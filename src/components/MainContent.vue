<script setup lang="ts">
	import HeroBlock from './HeroBlock.vue'
	import CopyBlock from './CopyBlock.vue'
	import ImageLeftCopyRightBlock from './ImageLeftCopyRightBlock.vue'
</script>

<template>
	<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" width="600" style="background-color: #ffffff;border-radius:8px;width:100%;max-width: 600px;">
	<tr>
	<td align="center" style="padding-top:40px;">
		<table align="center" border="0" cellpadding="0" cellspacing="0" role="presentation" width="600" style="width:100%;">
		<tr>
		<td align="center" style="padding-bottom:50px;">
			<HeroBlock img="hero-01.png" alt="This is an image" wdth="150"/>
			<CopyBlock headline="Fname, keep using your&nbsp;card" bodyOne="Keep using your $X,XXX credit line to get" bodyTwo="the most value out of your Prosper"/>
			<ImageLeftCopyRightBlock headline="There are many ways to use <br class='mblhd'/>your credit line" bulletOne="In-person" bulletTwo="Online" bulletThree="In your digital wallet"/>
		</td>
		</tr>
		</table>
	</td>
	</tr>
	</table>
</template>