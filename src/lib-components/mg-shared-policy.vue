<script>

export default /*#__PURE__*/{
  name: 'MgSharedPolicy', // vue component name
  props: {
    content: String
  }
}
</script>

<template>
  <div class="privacy-container" v-html="content" />
</template>
