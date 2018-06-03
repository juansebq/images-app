<template>
  <div>
    <AppHeader />
    <div style="margin-top:2rem" class="ui container">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader';
export default {
  name: 'App',
  components: {
    AppHeader
  }

}
</script>

<style>

</style>
