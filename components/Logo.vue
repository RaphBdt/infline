<template>
    <NuxtLink to="/">
        <p :class="`cffont logo logo-${color}`">Infline</p>
    </NuxtLink>
</template>

<script>
export default {
  props: ['color']
}
</script>
