<template>
    <div class="px-5 pt-8 pb-5 flex flex-col justify-between gap-3 rounded-lg bg-lightGreen">
        <div class="flex flex-col w-full gap-3">
            <span class="font-baloo text-lg">
                {{ $t('support_title') }}
            </span>
            <p class="text-sm sm:text-base">
                {{ $t('support_p') }}
            </p>
        </div>
        <div class="mt-10 w-full">
            <div id="paypal-checkout"></div>
        </div>

    </div>
</template>
<script>
import { usePaypalButton } from "../../node_modules/nuxt-paypal/dist/runtime/composables/usePaypal"
export default {
    mounted() {
        usePaypalButton({
            onApprove: async (data, actions) => {
                try {
                    const details = await actions.order?.capture();
                    console.log('Payment completed successfully:', details);
                } catch (error) {
                    console.error('Error capturing payment:', error);
                }
            },
        })
    }
}
</script>