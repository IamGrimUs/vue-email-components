<script setup lang="ts">
	import HeroBlock from './HeroBlock.vue'
	import CopyBlock from './CopyBlock.vue'
	import MainTable from './MainTable.vue'
	import ImageLeftCopyRightBlock from './ImageLeftCopyRightBlock.vue'
</script>

<template>
	<MainTable>
		<template v-slot:heroBlock>
			<HeroBlock>
				<img src="src/assets/hero-01.png" alt="alt" width="150" style="display:block; border:0; outline:0; padding:0;font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#4d4d4d;width:150px;margin:0 auto;" class="lft-algn" />
			</HeroBlock>
		</template>
		<template v-slot:copyBlock>
			<CopyBlock>
				<template v-slot:headline>
					Fname, keep using your&nbsp;card
				</template>
				<template v-slot:bodyCopy>
					Keep using your $X,XXX credit line to get <br class="mblhd" />the most value out of your Prosper<span style="font-size:8px;line-height: 0;vertical-align: 6px;">&reg;</span>&nbsp;card.
				</template>
			</CopyBlock>
		</template>
		<template v-slot:detailsBlock>
			<ImageLeftCopyRightBlock bulletTwo="Online" bulletThree="In your digital wallet">
				<template v-slot:headline>
					<ImageLeftCopyRightBlock bulletOne="In-person" bulletTwo="Online" bulletThree="In your digital wallet">There are many ways to use <br class='mblhd'/>your credit line</ImageLeftCopyRightBlock>
				</template>
				<template v-slot:iconImage>
					<img src="../assets/icn-checkmark-orange.png" alt="" width="16" style="width:16px;" />
				</template>
			</ImageLeftCopyRightBlock>
		</template>
	</MainTable>
</template>