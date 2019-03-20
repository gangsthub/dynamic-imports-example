<template>
  <div>
    <letter-a></letter-a>
    <letter-b></letter-b>
  </div>
</template>

<script>
import LetterA from '~/components/ComponentA.vue'
import LetterB from '~/components/ComponentB.vue'

export default {
  layout: 'subpage',
  components: {
    LetterA,
    LetterB
  }
}
</script>
