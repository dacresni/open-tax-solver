<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <WelcomePage msg="Welcome to Open Tax Solver"/>
    <ClientList clients= [] />
  </div>
</template>

<script>
// @ is an alias to /src
import WelcomePage from '@/components/WelcomePage.vue'

export default {
  name: 'Home',
  components: {
    WelcomePage
  }
}
</script>
