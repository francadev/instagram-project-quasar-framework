<template>
  <q-page class="flex flex-center column">
    <q-img src="../../../src/assets/instadev-logo.svg"></q-img>
    <q-input filled v-model="text" label="User" />
    <q-input filled v-model="text" label="Password" />
    <a href="">Forgot Password?</a>
    <q-btn color="primary" label="Log In" />
    <div class="flex row">
      <q-img src="../../../src/assets/facebook-logo.svg"></q-img>
      <a href="">Log in with Facebook</a>
    </div>
    <div class="full-width">
      <q-separator />
      or
      <q-separator />
    </div>
    <div>
      Don’t have an account? <a href="">Sign up.</a>
    </div>
    <div class="full-width">
      <q-separator />Instagram от Facebook
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'SignIn',
  methods: {
  },
  data(){
    return{
      text: '',
    }
  },
}
</script>
