<template>
  <SchemaForm v-bind="bind" />
</template>

<script type="text/javascript">
import View from 'src/app/Agnostic/Adapters/View'
import Schema from 'src/domains/Admin/Action/Schema/ActionSchema'

/**
 */
export default {
  /**
   */
  extends: View,
  /**
   */
  name: 'ActionForm',
  /**
   */
  schema: Schema
}
</script>

<style
  lang="stylus"
  rel="stylesheet/stylus"
>
</style>
