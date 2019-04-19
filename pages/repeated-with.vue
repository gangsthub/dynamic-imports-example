<template>
  <div>
    <!-- This are async -->
    <letter-a></letter-a>
    <letter-b></letter-b>
  </div>
</template>

<script>
// here I'm using https://webpack.js.org/guides/code-splitting/#dynamic-imports
// `webpackChunkName` "magic comment" is optional
const LetterA = () =>
  import(/* webpackChunkName: "A" */ '~/components/ComponentA.vue')
const LetterB = () =>
  import(/* webpackChunkName: "B" */ '~/components/ComponentB.vue')

export default {
  layout: 'subpage',
  components: {
    LetterA,
    LetterB
  }
}
</script>
