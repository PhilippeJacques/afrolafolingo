<template>
    <section id="contact" class="mt-[90px] px-5 w-full sm:px-[10vw] grid gap-16 sm:grid-cols-2">
        <div class=" pt-20 flex flex-col w-full h-auto">
            <span class="text-2xl font-baloo">
                {{ $t('question') }}
            </span>
            <p class="text-sm sm:text-base">
                {{ $t('question_p') }}
            </p>
            <div class="mt-5 w-full h-auto flex flex-col gap-2">
                <a href="https://t.me/afrolingo"
                    class="p-1 h-16 w-full flex gap-3 border border-[#e5e5e5] rounded-full">
                    <div class="h-full aspect-square rounded-full flex justify-center items-center bg-[#f5f5f5]">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M11.9854 15.4083L15.2268 19.0936C16.4277 20.4589 17.0282 21.1416 17.6567 20.9754C18.2852 20.8092 18.5008 19.9108 18.9318 18.1138L21.3229 8.1459C21.9868 5.37832 22.3187 3.99454 21.5808 3.312C20.843 2.62947 19.564 3.13725 17.0061 4.15282L5.13876 8.86449C3.09293 9.67674 2.07001 10.0829 2.00507 10.7808C1.99842 10.8522 1.99831 10.9241 2.00474 10.9955C2.06754 11.6937 3.08921 12.1033 5.13255 12.9223C6.05838 13.2934 6.5213 13.479 6.8532 13.8344C6.89052 13.8743 6.9264 13.9157 6.96078 13.9584C7.26658 14.3384 7.39709 14.8371 7.65808 15.8344L8.14653 17.701C8.4005 18.6715 8.52749 19.1568 8.86008 19.223C9.19267 19.2891 9.48225 18.8867 10.0614 18.0819L11.9854 15.4083ZM11.9854 15.4083L11.6676 15.0771C11.3059 14.7001 11.1251 14.5117 11.1251 14.2775C11.1251 14.0433 11.3059 13.8548 11.6676 13.4778L15.2406 9.75409"
                                stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                        </svg>
                    </div>
                    <div class="flex flex-col h-full justify-center">
                        <span class="font-baloo text-sm sm:text-base">Telegram</span>
                        <p class="text-[10px] text-grisTxt text-sm">{{ $t('telegram_desc') }}</p>
                    </div>
                </a>
                <a href="mailto:philippejacques@afrolingo.org"
                    class="p-1 h-16 w-full flex gap-3 border border-[#e5e5e5] rounded-full">
                    <div class="h-full aspect-square rounded-full flex justify-center items-center bg-[#f5f5f5]">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M7 8.5L9.94202 10.2394C11.6572 11.2535 12.3428 11.2535 14.058 10.2394L17 8.5"
                                stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                            <path
                                d="M2.01577 13.4756C2.08114 16.5412 2.11383 18.0739 3.24496 19.2094C4.37608 20.3448 5.95033 20.3843 9.09883 20.4634C11.0393 20.5122 12.9607 20.5122 14.9012 20.4634C18.0497 20.3843 19.6239 20.3448 20.7551 19.2094C21.8862 18.0739 21.9189 16.5412 21.9842 13.4756C22.0053 12.4899 22.0053 11.5101 21.9842 10.5244C21.9189 7.45886 21.8862 5.92609 20.7551 4.79066C19.6239 3.65523 18.0497 3.61568 14.9012 3.53657C12.9607 3.48781 11.0393 3.48781 9.09882 3.53656C5.95033 3.61566 4.37608 3.65521 3.24495 4.79065C2.11382 5.92608 2.08114 7.45885 2.01576 10.5244C1.99474 11.5101 1.99475 12.4899 2.01577 13.4756Z"
                                stroke="#141B34" stroke-width="1.5" stroke-linejoin="round" />
                        </svg>
                    </div>
                    <div class="flex flex-col h-full justify-center">
                        <span class="font-baloo text-sm sm:text-base">Email</span>
                        <p class="text-[10px] text-grisTxt text-sm">{{ $t('telegram_desc') }}</p>
                    </div>
                </a>
            </div>
        </div>
        <div class="hidden sm:flex sm:w-full sm:aspect-square bg-slate-200 rounded-lg">
            <NuxtImg src="/contact.png" class="w-full h-full object-cover rounded-lg" alt="" />
        </div>
    </section>
</template>