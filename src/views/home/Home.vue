<template>
  <div>
    <h2>欢迎{{ user.uname }}！您的 uid 为{{ user.uid }}</h2>
    <router-link to="/login">
      <el-button> 登出 </el-button>
    </router-link>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        uname: "",
        uid: null,
      },
    };
  },
};
</script>

<style scoped>
</style>