<template>
    <div>
        Please wait...
    </div>
</template>

<script>
import { mapActions } from 'vuex';

export default {
  name: 'AuthHandler',
  methods: mapActions(['finalizeLogin']),
  created() {
      console.log('epa');
      this.finalizeLogin(window.location.hash);
  }
};
</script>
