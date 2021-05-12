<template>
  <div>
    {{ fo }}
  </div>
</template>

<script>
import * as _ from 'lodash'
import Component from 'Component.vue'

export default {
  props: ['foo', 'bar']
}
</script>
