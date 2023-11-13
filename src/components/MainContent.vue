<script lang="ts">
	import ImageBlock from './ImageBlock.vue'
	import CopyBlock from './CopyBlock.vue'
	import MainTable from './MainTable.vue'
	import ImageLeftCopyRightBlock from './ImageLeftCopyRightBlock.vue'
	export default {
  components: {
    ImageBlock,
		CopyBlock,
		ImageLeftCopyRightBlock,
		MainTable
  }
}
</script>

<template>
	<MainTable tableWidth="600" paddingTop="40" paddingBottom="50">
		<template v-slot:imageBlock>
			<ImageBlock tableWidth="88%">
				<a href="%%">
					<img src="src/assets/hero-01.png" alt="alt" width="150" style="display:block; border:0; outline:0; padding:0;font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#4d4d4d;width:150px;margin:0 auto;" class="lft-algn" />
				</a>
			</ImageBlock>
		</template>
		<template v-slot:copyBlock>
			<CopyBlock tableWidth="68%" className="w88" paddingBottom="60" paddingTop="24">
				<template v-slot:headline>
					<h1 style="margin:0;padding:0;color:#4d4d4d;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif; font-size:28px;font-weight:700;line-height:38px;text-align:center;" class="txt-lft">Fname, keep using your&nbsp;card</h1>
				</template>
				<template v-slot:bodyCopy>
					<p style="margin:0;padding:0;margin-top:10px;color:#303030;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif; font-size:16px;line-height:22px;text-align:center;" class="txt-lft">Keep using your $X,XXX credit line to get <br class="mblhd" />the most value out of your Prosper<span style="font-size:8px;line-height: 0;vertical-align: 6px;">&reg;</span>&nbsp;card.</p>
				</template>
			</CopyBlock>
		</template>
		<template v-slot:detailsBlock>
			<ImageLeftCopyRightBlock>
				<template v-slot:iconImage>
					<img src="../assets/icn-checkmark-orange.png" alt="" width="16" style="width:16px;" />
				</template>
				<template v-slot:subHeadline>
					<h2 style="margin:0;padding:0;color:#4d4d4d;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif; font-size:28px;font-weight:700;line-height:38px;text-align:left;">There are many ways to use <br class='mblhd'/>your credit line</h2>
				</template>
				<template v-slot:bulletOne>
					<p style="margin:0;padding:0;color:#4d4d4d;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif;font-size:14px;line-height:20px;text-align:left;">bullet One</p>
				</template>
				<template v-slot:bulletTwo>
					<p style="margin:0;padding:0;color:#4d4d4d;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif;font-size:14px;line-height:20px;text-align:left;">Online</p>
				</template>
				<template v-slot:bulletThree>
					<p style="margin:0;padding:0;color:#4d4d4d;font-family:'Helvetica Neue', Helvetica, Arial, sans-serif;font-size:14px;line-height:20px;text-align:left;">In your digital wallet</p>
				</template>
			</ImageLeftCopyRightBlock>
		</template>
	</MainTable>
</template>