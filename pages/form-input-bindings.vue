<!-- Notes on Form Input Bindings. https://vuejs.org/v2/guide/forms.html. -->

<template>
  <!-- Form Input Modifiers -->
  <div>
    <!-- `.lazy` modifier-->
    <div>
      <p>
        <code>v-model</code> by default syncs with data on every <code>input</code> event.
      </p>
      <textarea v-model="nonLazydata"></textarea>
      <p>{{ nonLazydata }}</p>

      <textarea v-model.lazy="lazyData"></textarea>
      <p>{{ lazyData }}</p>
    </div>
  </div>
</template>

<script>
  export default {
    data: function () {
      return {
        nonLazydata: '',
        lazyData: ''
      }
    }
  }
</script>

<style>

</style>
