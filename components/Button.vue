<template>
    <NuxtLink :class="`button cffont rounded-lg min-w-[180px] px-5 pt-3 pb-4 text-[12px] text-center ${type}`" :to="link">{{ content }}</NuxtLink>
</template>

<script>
export default {
    props: ['content', 'link', 'type']
}
</script>

<style scoped>
    .primary {
        background-color: #ffffff;
    }

    .white {
        background-color: #B188EA;
        color: #ffffff;
    }
</style>