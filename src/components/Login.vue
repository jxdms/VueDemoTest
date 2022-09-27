<template>
  <div>
    <h1 align="center">欢迎登录</h1>
    <table align="center">
      <tr>
        <td>用户名:<input type="text" v-model="username" /></td>
      </tr>
      <tr>
        <td><input type="submit" v-on:click="doLogin()" v-bind:value="btnname" /> </td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: "Login",
  data:function(){
    return {
      username:"",
      password:"",
      btnname:"提交"
    };
  },
  methods:{
    doLogin(){
      console.log("......")
    }
  }
}
</script>

<style scoped>

</style>
