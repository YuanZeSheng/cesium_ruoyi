<template>
  <div>
    ???
    <a @click="toPage()">sss</a>
  </div>
</template>

<script>
import { mapState, mapMutations } from "vuex";

export default {
  components: {},
  data() {
    return {};
  },
  computed: {},
  methods: {
    toPage() {
      this.$router.push({
        path: "/admin",
      });
    }
  },
  watch: {},
  beforeCreate() {},
  created() {},
  beforeMount() {},
  mounted() {},
  beforeUpdate() {},
  updated() {},
  beforeDestroy() {},
  destroyed() {},
};
</script>

<style scoped lang="less"></style>
