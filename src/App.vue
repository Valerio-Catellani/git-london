<template>
  <HeaderComponent />
  <main>
    <ExpenseComponent/>
    <ListToDoComponent/>
  </main>
</template>

<script>
import ExpenseComponent from './components/ExpenseComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import ListToDoComponent from './components/ListToDoComponent.vue';
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      ExpenseComponent,
      ListToDoComponent
    }
  }
</script>

<style lang="scss" scoped>

</style>