<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <WelcomePage msg="Welcome to Open Tax Solver"/>
    <ClientList  />
  </div>
</template>

<script>
// @ is an alias to /src
import WelcomePage from '@/components/WelcomePage.vue'
import ClientList from '@/components/ClientList.vue'


export default {
  name: 'Home',
  components: {
    WelcomePage,
    ClientList 
  }
}
</script>
