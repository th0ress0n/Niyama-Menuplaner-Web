<template>
  <div>
    <slot :header="header"></slot>
  </div>
</template>
<script>
import Vue from 'vue';
import Component from 'vue-class-component';
export default Component({})(
  class Settings extends Vue {
    header = 'How To Build Vue Apps Like A Pro 😎';
  }
);
</script>