<template>
  <div>
    <div class="ui inverted vertical masthead center aligned segment">
      <div class="ui container">
        <sidebar/>
      </div>
      <div class="ui container">
        <landing-header/>
      </div>
    </div>
    <nuxt/>
    <my-footer/>
  </div>
</template>

<script>
import MyFooter from '~components/Footer.vue'
import Sidebar from '~components/Sidebar.vue'
import LandingHeader from '~components/LandingHeader.vue'

export default {
  components: {
    MyFooter, Sidebar, LandingHeader
  }
}
</script>