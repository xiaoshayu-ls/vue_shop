<template>
  <h1>Welcome</h1>
</template>
<script>
import hub from '../hub'
export default {
  name: 'welcome',
  created() {
      hub.$emit('savaNavState','')
  }
}
</script>
<style lang="stylus" scoped></style>
