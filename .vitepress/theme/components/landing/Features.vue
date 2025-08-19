<script setup>
import { useData } from 'vitepress';
import SectionBlock from '@components/landing/SectionBlock.vue';
import FeatureItem from '@components/landing/FeatureItem.vue';

const { frontmatter } = useData();
</script>


<template>
    <div class="p-4 md:p-0">

        <section class="py-12 relative">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 p-6 mb-12">
                <div class="flex flex-col gap-4">
                    <div class="flex items-center gap-3">
                        <svg class="size-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#888b93">
                            <path
                                d="M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22ZM16.8201 17.0761C18.1628 15.8007 19 13.9981 19 12C19 8.13401 15.866 5 12 5C10.9391 5 9.9334 5.23599 9.03241 5.65834L10.0072 7.41292C10.6177 7.14729 11.2917 7 12 7C14.7614 7 17 9.23858 17 12H14L16.8201 17.0761ZM14.9676 18.3417L13.9928 16.5871C13.3823 16.8527 12.7083 17 12 17C9.23858 17 7 14.7614 7 12H10L7.17993 6.92387C5.83719 8.19929 5 10.0019 5 12C5 15.866 8.13401 19 12 19C13.0609 19 14.0666 18.764 14.9676 18.3417Z">
                            </path>
                        </svg>
                        <span class="text-sm uppercase tracking-widest text-[#9ca3af]">
                            What is Paymenter?
                        </span>
                    </div>
                    <div class="text-3xl font-semibold ">
                        A next-generation billing platform for modern hosting businesses
                    </div>
                </div>
                <div class="flex flex-col justify-end">
                    <span class="flex justify-center font-normal text-[var(--vp-c-text-2)]">
                        Paymenter simplifies billing, enhances transactions, and supports seamless customizations to
                        meet
                        your
                        unique business needs.
                    </span>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-5 gap-6 p-6">
                <FeatureItem icon="robot-3-fill" title="Automation"
                    description="Streamline operations with automated billing and service deployment." />
                <FeatureItem icon="phone-find-fill" title="Responsive"
                    description="Perfect user experience across all devices, from desktop to mobile." />
                <FeatureItem icon="flashlight-fill" title="Performant"
                    description="Lightning-fast operations for smooth and reliable transactions." />
                <FeatureItem icon="brush-ai-fill" title="Personalization"
                    description="Create custom themes and experiences tailored to your business." />
                <FeatureItem icon="open-source-fill" title="Open-Source"
                    description="Free to use, transparent code, and backed by a growing community of developers." />
            </div>
        </section>

        <section class="py-12">

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 p-6 items-center relative">

                <div class="absolute inset-0 z-0">

                    <div
                        class="animate-pulse ![animation-duration:8s] ![animation-iteration-count:infinite] relative w-full h-[500px] bg-[var(--vp-c-brand-1)]/5 transform-3d rotate-x-25 rotate-y-18 -rotate-z-8 mask-x-from-70% mask-x-to-100% mask-y-from-70% mask-y-to-100%">
                        <div
                            class="absolute inset-0 bg-[linear-gradient(90deg,color-mix(in_srgb,var(--vp-c-brand-1)_10%,transparent)_1px,transparent_1px)] bg-[size:40px_100%]">
                        </div>
                        <div
                            class="absolute inset-0 bg-[linear-gradient(0deg,color-mix(in_srgb,var(--vp-c-brand-1)_10%,transparent)_1px,transparent_1px)] bg-[size:100%_40px]">
                        </div>
                        <div
                            class="absolute inset-0 bg-[linear-gradient(90deg,color-mix(in_srgb,var(--vp-c-brand-1)_20%,transparent)_1px,transparent_1px)] bg-[size:80px_100%]">
                        </div>
                    </div>

                </div>

                <div
                    class="order-1 lg:order-2 -ml-4 lg:-ml-20 flex flex-col gap-14 transform-3d rotate-x-25 rotate-y-18 -rotate-z-8 mask-r-from-80%">
                    <div
                        class="overflow-hidden group/card ![animation-duration:9s] ![animation-iteration-count:infinite] animate-rotate-border transition-all duration-500 ease-out transform-3d rounded-3xl bg-conic/[from_var(--border-angle)] from-[var(--vp-c-divider)] via-[var(--vp-c-text-3)] to-[var(--vp-c-divider)] hover:via-[var(--vp-c-brand-1)] from-80% via-90% to-100% p-px w-auto max-w-fit">
                        <div class="bg-[var(--vp-c-bg)] p-6 rounded-3xl flex flex-col items-start gap-8 relative z-10">
                            <div class="flex h-full items-center gap-3">
                                <div
                                    class="p-2 border border-dashed border-[var(--vp-c-text-3)]/60 group-hover/card:border-[var(--vp-c-brand-1)] rounded-lg">
                                    <div
                                        class="h-4 w-4 bg-[var(--vp-c-text-3)]/60 rounded-sm group-hover/card:bg-[var(--vp-c-brand-1)] animate-pulse ![animation-duration:3s] ![animation-iteration-count:infinite]">
                                    </div>
                                </div>
                                <p class="uppercase tracking-widest font-light font-mono text-[var(--vp-c-text-3)]">
                                    Servers</p>
                            </div>
                            <div class="flex items-center gap-2">
                                <a href="/docs/extensions/convoy" class="relative group/app">
                                    <convoy
                                        class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-[#1B1B1B] ring-6 ring-white/10" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/cpanel" class="relative group/app">
                                    <cpanel
                                        class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-[#FF6C2C] ring-6 ring-[#FF6C2C]/30" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/enhance" class="relative group/app">
                                    <enhance
                                        class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-[#211451] ring-6 ring-[#7363af]/40" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/plesk" class="relative group/app">
                                    <plesk
                                        class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-white ring-6 ring-white/20" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/pterodactyl" class="relative group/app">
                                    <pterodactyl
                                        class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-[#10529F] ring-6 ring-[#10529F]/40" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/directadmin" class="relative group/app">
                                    <directadmin
                                        class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-[#22272E] ring-6 ring-[#22272E]/40" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/virtualizor" class="relative group/app">
                                    <virtualizor
                                        class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-white ring-6 ring-white/20" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/virtfusion" class="relative group/app">
                                    <virtfusion
                                        class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-[#166BBD] ring-6 ring-[#166BBD]/40" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                            </div>
                        </div>
                    </div>
                    <div
                        class="overflow-hidden lg:ml-24 group/card ![animation-duration:9s] ![animation-iteration-count:infinite] animate-rotate-border transition-all duration-500 ease-out transform-3d rounded-3xl bg-conic/[from_var(--border-angle)] from-[var(--vp-c-divider)] via-[var(--vp-c-text-3)] to-[var(--vp-c-divider)] hover:via-[var(--vp-c-brand-1)] from-80% via-90% to-100% p-px w-auto max-w-fit">
                        <div class="bg-[var(--vp-c-bg)] p-6 rounded-3xl flex flex-col items-start gap-8 relative z-10">
                            <div class="flex h-full items-center gap-3">
                                <div
                                    class="p-2 border border-dashed border-[var(--vp-c-text-3)]/60 group-hover/card:border-[var(--vp-c-brand-1)] rounded-lg">
                                    <div
                                        class="h-4 w-4 bg-[var(--vp-c-text-3)]/60 rounded-sm group-hover/card:bg-[var(--vp-c-brand-1)] animate-pulse ![animation-duration:3s] ![animation-iteration-count:infinite]">
                                    </div>
                                </div>
                                <p class="uppercase tracking-widest font-light font-mono text-[var(--vp-c-text-3)]">
                                    Payment
                                    Gateways</p>
                            </div>
                            <div class="flex items-center gap-2">
                                <a href="/docs/extensions/mollie" class="relative group/app">
                                    <mollie
                                        class="group-hover/app:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-black ring-6 ring-white/10" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <xendit
                                    class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-[#3b68ff] ring-6 ring-[#3b68ff]/20" />
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/paypal" class="relative group/app">
                                    <paypal
                                        class="group-hover/app:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-white ring-6 ring-white/20" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <a href="/docs/extensions/stripe" class="relative group/app">
                                    <stripe
                                        class="group-hover/app:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-[#635BFF] ring-6 ring-[#635BFF]/40" />
                                    <div
                                        class="absolute -top-4 -right-4 hidden group-hover/app:block bg-[var(--vp-c-text-3)]/60 p-0.5 rounded-sm pointer-events-none">
                                        <arrow-right-up-box-fill class="size-6" />
                                    </div>
                                </a>
                                <div class="h-px w-4 border border-dashed border-[var(--vp-c-text-3)]/60"></div>
                                <midtrans
                                    class="hover:scale-120 flex items-center justify-center size-18 rounded-xl p-4 bg-white ring-6 ring-white/20" />
                            </div>
                        </div>
                    </div>
                </div>

                <div class="flex flex-col order-2 lg:order-2 z-10">

                    <SectionBlock icon="puzzle-2-fill" tagline="Extensible" title="Powerful Extensions & Integrations"
                        description="Customize your billing platform with a growing marketplace of extensions. From payment gateways to service integrations, build the perfect solution for your business.">
                        <div class="flex gap-6 justify-start mt-8">
                            <a href="/marketplace/" class="btn btn-primary svg-left" style="color:white;">
                                {{ frontmatter.featuresLanding.extensible.marketplaceButton }}
                                <arrow-right-up-box-fill class="size-5" />
                            </a>
                            <a href="https://github.com/Paymenter/Paymenter/tree/master/extensions" target="_blank"
                                class="btn svg-left">
                                Bundled Extensions
                                <arrow-right-fill class="size-5" />
                            </a>
                        </div>
                    </SectionBlock>
                </div>

            </div>

        </section>

        <section class="py-16 relative overflow-hidden mask-y-from-90% mask-y-to-100%">

            <div
                class="absolute inset-0 z-0 flex items-center justify-center transform-3d rotate-x-55 rotate-y-0 -rotate-z-45">
                <div
                    class="h-auto w-full ![animation-duration:4s] ![animation-iteration-count:infinite] animate-rotate-border transition-all duration-500 ease-out transform-3d rounded-full bg-conic/[from_var(--border-angle)] from-[var(--vp-c-border)] via-[#1fe6a3] to-[var(--vp-c-border)] from-80% via-90% to-100% p-px shadow-2xl shadow-[#1fe6a3]/10">
                    <div class="bg-[var(--vp-c-bg)] p-20 rounded-full">

                        <div
                            class="![animation-duration:3s] ![animation-iteration-count:infinite] animate-rotate-border transition-all duration-500 ease-out transform-3d rounded-full bg-conic/[from_var(--border-angle)] from-[var(--vp-c-border)] via-[#1fe6a3] to-[var(--vp-c-border)] from-80% via-90% to-100% p-px">

                            <div class="bg-[var(--vp-c-bg)] p-20 rounded-full">

                                <div
                                    class="![animation-duration:2s] ![animation-iteration-count:infinite] animate-rotate-border transition-all duration-500 ease-out transform-3d rounded-full bg-conic/[from_var(--border-angle)] from-[var(--vp-c-border)] via-[#1fe6a3] to-[var(--vp-c-border)] from-80% via-90% to-100% p-px">

                                    <div class="bg-[var(--vp-c-bg)] p-20 rounded-full">
                                        <div
                                            class="animate-pulse ![animation-duration:3s] ![animation-iteration-count:infinite] p-10 rounded-full border border-[#1fe6a3] shadow-2xl shadow-[#4060ff]/20 text-[var(--vp-c-text-1)]/50">

                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex flex-col p-6 items-center relative">
                <div class="flex flex-col gap-6 lg:max-w-2xl items-center text-center">
                    <div class="flex items-center gap-3 text-[#9ca3af]">
                        <braces-fill class="size-5" />
                        <span class="text-sm uppercase tracking-widest text-[#9ca3af]">
                            Paymenter API
                        </span>
                    </div>
                    <div class="text-3xl font-semibold ">
                        Extend and Automate with the API
                    </div>
                    <span class="flex font-normal text-[var(--vp-c-text-2)]">
                        Our REST API gives you the power to control your entire platform. Build custom solutions,
                        automate complex workflows, and integrate everything seamlessly.
                    </span>
                    <div class="flex gap-4 justify-center mt-4">
                        <a href="/api/" class="btn btn-primary svg-left" style="color:white;">
                            Explore the API
                            <arrow-right-up-box-fill class="size-5" />
                        </a>
                        <a href="https://paymenter.org/openapi.json" target="_blank" class="btn svg-left">
                            OpenAPI Spec
                            <arrow-right-fill class="size-5" />
                        </a>
                    </div>
                </div>
            </div>

        </section>

        <section class="py-16">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 p-6">

                <SectionBlock icon="service-fill" tagline="Sponsors"
                    title="Building Together a Sustainable Future for Open-Source Billing" />

                <div class="flex flex-col justify-end">
                    <span class="flex justify-center font-normal text-[var(--vp-c-text-2)]">
                        The continued development and maintenance of Paymenter is made possible by these generous
                        sponsors:
                    </span>
                </div>

            </div>
            <div class="p-6 grid grid-cols-1 md:grid-cols-4 gap-4">
                <a class="h-18 md:w-72 w-full flex justify-center items-center border border-[var(--vp-c-divider)] rounded-lg opacity-75 grayscale hover:grayscale-0 hover:opacity-100"
                    href="https://www.quape.com/?rel=paymenter" target="_blank" aria-label="QUAPE PTE LTD   ">
                    <svg xmlns="http://www.w3.org/2000/svg" version="1.0" width="193" height="24" viewBox="0 0 936.000000 250.000000" preserveAspectRatio="xMidYMid meet">
                        <g transform="translate(0.000000,250.000000) scale(0.100000,-0.100000)" fill="#f04122" stroke="none">
                            <path d="M1056 2490 c-521 -66 -931 -450 -1033 -968 -22 -116 -22 -338 1 -445 49 -224 151 -426 292 -577 l43 -46 -169 -219 c-93 -121 -170 -223 -170 -227 0 -5 85 -8 189 -8 l189 0 102 134 102 134 92 -44 c435 -206 961 -121 1318 214 243 229 371 526 371 867 0 156 -16 255 -65 395 -142 402 -483 696 -897 774 -103 20 -276 27 -365 16z m367 -329 c296 -78 550 -332 628 -626 12 -46 23 -127 26 -190 31 -636 -606 -1095 -1201 -867 -38 15 -71 32 -73 37 -2 6 121 172 272 369 151 198 275 361 275 363 0 1 -87 3 -192 3 l-193 -1 -209 -275 -209 -274 -29 32 c-49 57 -119 176 -148 251 -88 227 -77 495 31 712 121 243 344 418 609 476 112 25 300 20 413 -10z"/>
                            <path d="M5117 2418 c-20 -18 -596 -1238 -1028 -2176 l-38 -82 170 2 170 3 154 330 c85 182 158 336 163 344 7 12 17 9 60 -17 240 -148 555 -149 793 -2 27 16 53 30 57 30 4 0 79 -156 167 -345 l160 -345 168 0 c132 0 168 3 164 13 -57 137 -1052 2246 -1064 2255 -26 19 -69 14 -96 -10z m213 -941 l153 -327 -24 -26 c-36 -38 -155 -92 -229 -104 -117 -18 -258 21 -348 97 l-33 28 157 338 c87 185 161 334 165 330 3 -5 75 -155 159 -336z"/>
                            <path d="M2520 1607 c0 -938 -4 -894 87 -1077 39 -80 61 -109 137 -186 77 -76 106 -97 186 -137 52 -25 124 -54 160 -63 89 -24 282 -24 369 0 262 71 454 256 542 521 l24 70 3 848 3 847 -150 0 -150 0 -3 -817 c-3 -805 -4 -819 -25 -874 -44 -116 -128 -214 -226 -262 -275 -135 -598 32 -646 333 -7 41 -11 350 -11 843 l0 777 -150 0 -150 0 0 -823z"/>
                            <path d="M6440 1295 l0 -1135 155 0 155 0 0 514 0 515 318 3 c313 4 318 4 398 31 381 127 543 562 339 913 -46 80 -161 186 -246 228 -135 65 -142 66 -656 66 l-463 0 0 -1135z m961 804 c69 -33 128 -89 160 -155 36 -74 34 -188 -4 -266 -30 -62 -83 -115 -149 -150 -42 -22 -52 -23 -350 -26 l-308 -3 0 316 0 316 298 -3 297 -3 56 -26z"/>
                            <path d="M8060 1295 l0 -1135 650 0 650 0 0 155 0 155 -500 0 -500 0 0 380 0 380 500 0 500 0 0 155 0 155 -500 0 -500 0 0 295 0 295 500 0 500 0 0 150 0 150 -650 0 -650 0 0 -1135z"/>
                        </g>
                    </svg>
                </a>

                <a class="h-18 md:w-72 w-full flex justify-center items-center gap-2 border border-[var(--vp-c-divider)] rounded-lg opacity-75 grayscale hover:grayscale-0 hover:opacity-100"
                    href="https://github.com/sponsors/Paymenter" target="_blank" aria-label="Become a Sponsor">
                    Become a Sponsor
                    <arrow-right-up-fill class="size-5" />
                </a>

            </div>
        </section>


        <section class="py-12 relative overflow-hidden">

            <div
                class="absolute inset-0 z-0 flex items-center justify-center transform-3d rotate-x-55 rotate-y-0 -rotate-z-45">
                <div
                    class="![animation-duration:4s] ![animation-iteration-count:infinite] animate-rotate-border transition-all duration-500 ease-out transform-3d rounded-3xl bg-conic/[from_var(--border-angle)] from-[var(--vp-c-border)] via-[var(--vp-c-brand-1)] to-[var(--vp-c-border)] from-80% via-90% to-100% p-px shadow-2xl shadow-[#4060ff]/20">
                    <div class="bg-[var(--vp-c-bg)] p-20 rounded-3xl">

                        <div
                            class="![animation-duration:3s] ![animation-iteration-count:infinite] animate-rotate-border transition-all duration-500 ease-out transform-3d rounded-3xl bg-conic/[from_var(--border-angle)] from-[var(--vp-c-border)] via-[var(--vp-c-brand-1)] to-[var(--vp-c-border)] from-80% via-90% to-100% p-px">

                            <div class="bg-[var(--vp-c-bg)] p-20 rounded-3xl">

                                <div
                                    class="![animation-duration:2s] ![animation-iteration-count:infinite] animate-rotate-border transition-all duration-500 ease-out transform-3d rounded-3xl bg-conic/[from_var(--border-angle)] from-[var(--vp-c-border)] via-[var(--vp-c-brand-1)] to-[var(--vp-c-border)] from-80% via-90% to-100% p-px">

                                    <div class="bg-[var(--vp-c-bg)] p-20 rounded-3xl">
                                        <div
                                            class="animate-pulse ![animation-duration:3s] ![animation-iteration-count:infinite] p-10 rounded-3xl bg-[#4060ff]/20 border border-[#4060ff] shadow-2xl shadow-[#4060ff]/20 text-[var(--vp-c-text-1)]/50">
                                            <cloud-fill class="size-24" />
                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="relative grid grid-cols-1 md:grid-cols-2 gap-12 p-6 mb-12 mt-20">

                <SectionBlock icon="cloud-fill" tagline="Cloud" title="Hassle-free cloud hosting"
                    description="Deploy Paymenter instantly on our optimized cloud infrastructure. Scale effortlessly as your business grows, with automatic updates and backups included. Start for just $5/month with our beginner-friendly hosting solution." />

                <div class="flex flex-col justify-center lg:items-center items-start">
                    <div class="flex gap-4 justify-center">
                        <a href="https://paas.paymenter.org/" class="btn btn-primary svg-left" style="color:white;">
                            {{ frontmatter.featuresLanding.cloud.paasButton }}
                            <arrow-right-up-box-fill class="size-5" />
                        </a>
                        <a href="https://paas.paymenter.org" target="_blank" class="btn svg-left">
                            About PaaS
                            <arrow-right-fill class="size-5" />
                        </a>
                    </div>
                </div>
            </div>

            <div class="relative grid grid-cols-1 md:grid-cols-5 gap-6 p-6">
                <FeatureItem icon="translate-2" title="Multi-language"
                    description="Support multiple languages seamlessly with built-in translation." />
                <FeatureItem icon="currency-fill" title="Multi-currency"
                    description="Accept payments with automatic currency conversion and rates." />
                <FeatureItem icon="customer-service-fill" title="Support System"
                    description="Manage customer issues with an integrated ticketing solution." />
                <FeatureItem icon="megaphone-fill" title="Announcements"
                    description="Keep your customers informed with a built-in blog system." />
                <FeatureItem icon="hand-coin-fill" title="Affiliates"
                    description="Grow your business with a powerful affiliate tracking and reward system." />
            </div>
        </section>

        <section class="py-12">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 p-6 mb-12">

                <SectionBlock icon="team-fill" tagline="Community" title="Connect With Our Community"
                    description="Connect with thousands of hosting providers and developers. Share insights, get support, and contribute to making Paymenter even better. Join our Discord server and GitHub to be part of the journey.">
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-6">
                        <FeatureItem icon="download-fill" title="+24,000" description="Total Software Downloads" />
                        <FeatureItem icon="github-fill" title="+920" description="GitHub Stars and Growing" />
                        <FeatureItem icon="user-community-fill" title="+2,450" description="Active Community Members" />
                    </div>
                </SectionBlock>

                <div class="flex flex-col justify-center lg:items-center items-start">
                    <div class="flex gap-4 justify-center">
                        <a href="https://discord.gg/paymenter-882318291014651924" class="btn btn-secondary svg-right">
                            <discord-fill class="size-5 fill-[#5865F2]" />
                            Discord
                        </a>
                        <a href="https://github.com/Paymenter/Paymenter" target="_blank" class="btn svg-left">
                            {{ frontmatter.supportbanner.howToContribute }}
                            <arrow-right-fill class="size-5" />
                        </a>
                    </div>
                </div>

            </div>
        </section>

    </div>
</template>
