<template>
  <ul>
    <p> Client List </p>
    <li :clients="c in clients">
      {{c.name}} | {{c.ssn}}
    </li>
  </ul>
<template>
<script>
export default {
  name: 'ClientList',
  props: {
    clients: Array
  }
}
</script>

<!--
 <ClientList clients=[
   { name: nemo, ssn: 777-77-7777},
   { name: dora, ssn: 999-99-9999}
 ] >
--> 
