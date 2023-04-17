<template>
    <div class="dc-card">
        <img :src="data.thumb" :alt="data.type">
        <span class="text-white">{{ data.series }}</span>
    </div>
</template>

<script>


    export default {
        props: {
            data: {
                type: Array,
                required: true
            }
        }
    }
</script>

<style lang="scss" scoped>
    .dc-card{
        max-width: 176px;
        img{
            max-width: 100%;
            height: 100%;
        }
    }
</style>