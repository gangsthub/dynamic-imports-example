<template>
  <div>
    <h1 class="title">Dynamic imports</h1>
    <div class="links mt-12">
      <nuxt-link to="/with" class="button--green">With 😊</nuxt-link>
      <nuxt-link to="/without" class="button--grey">Without 😞</nuxt-link>
    </div>
    <div class="links mt-4">
      <nuxt-link to="/repeated-with" class="button--green"
        >Duplicated Page With 😊</nuxt-link
      >
      <nuxt-link to="/repeated-without" class="button--grey"
        >Duplicated Page Without 😞</nuxt-link
      >
    </div>
  </div>
</template>
