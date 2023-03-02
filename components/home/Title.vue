<template>
    <h1 class="text-white cffont uppercase text-[55px] leading-[72px]">{{content}} <span class="cffont text-black">{{ specialWord }}</span></h1>
</template>

<script>
export default {
  props: ['content', 'specialWord']
}
</script>

<style scoped>
    span {
        -webkit-text-stroke: 2px #B188EA; /* width and color */
    }
</style>