<template>
  <ul>
    <p> Client List </p>
    <li v-for="c in clients" :key=c.id>
      {{ c.name }} : {{ c.ssn }}
    </li>
  </ul>
</template>
<script>
export default {
  //name: 'ClientList',
  data() {
    return {
      clients: [
       { name: 'nemo', ssn: '777-77-7777'},
       { name: 'dora', ssn: '999-99-9999'}
     ] }
  }
}
</script>
 
