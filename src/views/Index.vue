<template>
  <div class="wrap">
    <the-header />
    <router-view />
    <the-footer />
  </div>
</template>

<script>
import TheHeader from './layouts/TheHeader';
import TheFooter from './layouts/TheFooter';

export default {
  components: {
    TheHeader,
    TheFooter,
  },
}
</script>