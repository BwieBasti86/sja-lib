<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { SjaLibSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  SjaLibSample,
  // }
});
</script>

<template>
  <div id="app">
    <sja-lib-sample />
  </div>
</template>
