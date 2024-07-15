<template>
  <div class="content">
    <h1>hello</h1>
    {{ msg }}
    <button @click="msgChange">点击</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "hello world"
    };
  },
  methods: {
    msgChange() {
      this.msg = "112233";
    }
  }
};
</script>

<style scoped>
.content {
  color: aquamarine;
  display: flex;
}
</style>
