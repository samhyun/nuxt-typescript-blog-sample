<template>
    <nav class="top-0 fixed z-50 w-full flex flex-wrap items-center justify-between px-2 py-2 h-16 navbar-expand-lg bg-teal-500">
        <div class="container mx-auto flex flex-wrap items-center justify-between">
            <div class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start">
                <nuxt-link :to="{path: '/'}">
                    <a class="text font-bold leading-relaxed inline-block mr-4 py-2 whitespace-no-wrap uppercase text-white">
                        blog sample
                    </a>
                </nuxt-link>
                <button class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded
                                bg-transparent block lg:hidden outline-none focus:outline-none" type="button">
                    <i class="text-white fas fa-bars"></i>
                </button>
            </div>
        </div>
    </nav>
</template>
<script lang="ts">
    import {Component, Vue} from 'vue-property-decorator';

    @Component
    export default class TopBar extends Vue {}
</script>
