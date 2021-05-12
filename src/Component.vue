<template>
  <div>
    <div v-for="[key,value] of values">
        
    </div>
  </div>
</template>

<script>
export default {
  props: {
      values: {
          type: Map,
          required: true
      }
  }
}
</script>
