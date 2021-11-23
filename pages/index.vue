<template>
  <div>
    <Default/>
  </div>
</template>

<script lang="ts">
import Default from '../layouts/default.vue'
export default({
   head(){
    return {
      title: 'Welcome To Dad Jokes',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Best place for corny dad jokes'
        }
      ]
    }
  },
  components: {
    Default
  }
})
</script>
