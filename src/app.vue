<template>
  <div>
    <img
      v-lazy="`http://s1.jiguo.com/${cover}/640?imageView2/1/w/640/h/640/q/100`"
      :src="`http://s1.jiguo.com/${cover}/640?imageView2/1/w/50/h/50/q/30`"
    />
  </div>
</template>
<script>
  export default {
    data () {
      return {
        cover: '58e7ad7b-63e4-457c-ba41-4f9b87950214'
      }
    }
  }
</script>

