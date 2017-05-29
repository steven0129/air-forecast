<template>
  <div>
    <div class="ui inverted vertical masthead center aligned segment">
      <div class="ui container">
        <sidebar/>
      </div>
      <div class="ui text container">
        <h1 class="ui inverted header">
          PM2.5空氣預報系統
        </h1>
      </div>
    </div>
    <nuxt/>
    <my-footer/>
  </div>
</template>

<script>
import MyFooter from '~components/Footer.vue'
import Sidebar from '~components/Sidebar.vue'

export default {
  components: {
    MyFooter, Sidebar
  }
}
</script>

<style>
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