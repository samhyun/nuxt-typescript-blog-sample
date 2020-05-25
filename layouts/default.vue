<template>
    <div>
        <top-bar>
        </top-bar>
        <div class="container mx-auto pt-24">
            <nuxt></nuxt>
        </div>
    </div>
</template>

<script lang='ts'>
    import {Component, Vue} from 'vue-property-decorator';
    import TopBar from '@/components/topBar.vue';

    @Component({
        components: {
            TopBar
        },
    })
    export default class DefaultLayout extends Vue {}
</script>
