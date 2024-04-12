<template>
  <HeaderComponent />
  <main>
    <ExpenseComponent/>
  </main>
</template>

<script>
import ExpenseComponent from './components/ExpenseComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      ExpenseComponent,
    }
  }
</script>

<style lang="scss" scoped>

</style>