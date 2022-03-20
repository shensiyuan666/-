<template>
  <div>
    <h3 @click="$emit('pass',666)">{{msg}}</h3>
    <slot name="num"></slot>
  </div>
</template>

<script>

export default {
  props:['msg'],
  data() {  
    return {

    }
  }
}
</script>

