<template>
  <section>
    <h1 class="ui center aligned header">
      Warning: We have {{ error.statusCode }} situation
    </h1>
    <h2 class="ui center aligned header">
      This may means "{{ error.message }}"
    </h2>
    <div class="ui center aligned header">
      <nuxt-link to="/" class="ui animated fade button" tabindex="0">
        <div class="visible content">Go back to homepage</div>
        <div class="hidden content">
          <i class="left arrow icon"></i>
        </div>
      </nuxt-link>
    </div>
  </section>
</template>
<script>
export default {
  props: ['error']
}
</script>

<style>
  .last.container {
    margin-bottom: 300px !important;
  }
  h1.ui.center.header {
    margin-top: 3em;
  }
  h2.ui.center.header {
    margin: 4em 0em 2em;
  }
  h3.ui.center.header {
    margin-top: 2em;
  }
</style>