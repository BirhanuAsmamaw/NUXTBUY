<template>
  <div>
    <p> Product details for {{ id }}</p>
    <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
        Ratione eligendi ipsum fuga quaerat veritatis! Magni molestiae accusantium nostrum eius 
        ipsam in maiores ab deleniti enim quisquam fugiat facere optio, ipsa voluptatem! Natus amet nulla doloribus magnam odio totam ipsam odit.
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute.params
</script>

<style  scoped>

</style>