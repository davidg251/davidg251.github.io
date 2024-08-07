<script setup>
console.log("epa")
const { data } = await useAsyncData('home', () => queryContent().find())
//const data = queryContent()
console.log(data)
</script>

<template>
  <pre>
    epa
    {{ data }}
  </pre>
</template>