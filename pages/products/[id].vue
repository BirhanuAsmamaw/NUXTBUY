<template>
  <div>
    <p> Product details for {{ id }} </p>
    <p> It is very important for the customer to pay attention to the adipiscing process. 
      The reason for choosing the flight itself is to seek the truth! For those of us who accuse him of great trouble, 
      let him avoid making the choice, the very pleasure, in the elders. Born with no pains,
       he hates the whole thing with a great hatred.
    </p>
  </div>
</template>
  
<script setup>
   const { id } = useRoute().params
   
   definePageMeta({
    layout: 'products',
   })
</script>

<style  scoped>

</style>