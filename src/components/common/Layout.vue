<template>
  <div class="">
    <div class="header">header</div>
    <div class="content">
      <keep-alive>
        <router-view></router-view>
      </keep-alive>
    </div>
    <div class="footer">footer</div>
  </div>
</template>

<style lang="scss">
@import '../../assets/css/common/global';
</style>
<style lang="scss" scoped>
.content {
  background-color: $bgColor;
}
</style>
<style>
@import '../../assets/css/common/reset';
</style>

<script>
export default {
  components: {},
  data () {
    return {}
  },
  props: {},
  watch: {},
  methods: {},
  filters: {},
  computed: {},
  created () { },
  mounted () { },
  destroyed () { }
}
</script>
