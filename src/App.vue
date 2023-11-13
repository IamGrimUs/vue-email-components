<!-- eslint-disable vue/no-parsing-error -->
<script lang="ts">
import HeaderContent from './components/HeaderContent.vue';
import FooterContent from './components/FooterContent.vue';
import MainContent from './components/MainContent.vue'

export default {
  components: {
    HeaderContent,
    MainContent,
    FooterContent
  }
}
</script>

<template>
  <HeaderContent>
    <a href="%%">
      <img src="src/assets/logo-psp-standard.png" alt="Prosper" width="113" style="display:block; border:0; outline:0; padding:0;font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#4d4d4d;width:113px;margin:0 auto;" class="lft-algn" />
    </a>
  </HeaderContent>
  <MainContent />
  <FooterContent>
    <template v-slot:footerImage>
      <img src="https://d15k2d11r6t6rl.cloudfront.net/public/users/Integrators/669d5713-9b6a-46bb-bd7e-c542cff6dd6a/20aea02fc3644b97a7541437bd6f9d79/Body/CreditCardITA/logo-psp-footer.png" alt="Propser Logo" width="43" style="border:0;display:block;margin:0 auto;outline:0;padding:0;color:#818181;font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size:12px;width:43px;" class="lft-algn" />
    </template>
    <template v-slot:disclaimerCreditCard>
      <!-- {{{ snippet "DisclaimerCreditCardAutomaticIncreases" 1 }}}
 	    {{{ snippet "DisclaimerCreditCardAnnualFee" 2 }}}
	    {{{ snippet "DisclaimerCreditCardUnsecured" }}} -->
    </template>
    <template v-slot:marketingFooterCreditCardAbandon>
      <!-- {{{ snippet "MarketingFooterCreditCardAbandon" }}} -->
    </template>
  </FooterContent>
</template>
