<template>
  <q-layout class="p1">
    <q-input outlined v-model="userName" label="用户名" class="name"/>
    <q-input outlined v-model="userPwd" label="密码" class="pwd"/>
    <q-btn color="primary" label="登录" size="lg" class="loginBtn"/>
  </q-layout>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'LoginPage',
  data () {
    return {
      count: 1,
      userName: '',
      userPwd: ''
    }
  },
  methods: {
    login () {
    },
    log () {
    }
  }
})
</script>

<style lang="scss">
.p1 {
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-left: 10px;
  margin-right: 10px;
  width: auto;

  .pwd {
    margin-top: 20px;
  }
  .loginBtn{
    margin-top: 40px;
  }
}

</style>
