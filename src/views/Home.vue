<template>
  <div class="home">
    <LandingPage msg="USed Cars"/>
  </div>
</template>

<script>
// @ is an alias to /src
import LandingPage from '@/components/LandingPage.vue';

export default {
  name: 'Home',
  components: {
    LandingPage,
  },
};
</script>
