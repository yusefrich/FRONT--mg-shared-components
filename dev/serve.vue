<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { MgSharedComponentsSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  MgSharedComponentsSample,
  // }
});
</script>

<template>
  <div id="app">
    <mg-shared-components-sample />
  </div>
</template>
