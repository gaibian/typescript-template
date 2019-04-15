<template>
  <div class="page">
    这是测试的
  </div>
</template>
<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class Test extends Vue {
  created() {
    console.log(this.$xiaojun(89))
  }
}
</script>
