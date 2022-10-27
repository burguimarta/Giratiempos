<script>
import Counter from './Counter.vue'

export default {
  data() {
    return {
      counters: [
        {
            name: "prueba"
        }
      ]
    }
  }
}
</script>
    
<template>
    <div class="counters" v-bind="counters"></div>
</template>
    
<style scoped>
.counters {
    width: 960px;
}
</style>