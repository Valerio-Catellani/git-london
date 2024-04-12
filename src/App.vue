<template>
  <HeaderComponent />
  <main>
    <ExpenseComponent />
    <ListToDoComponent />
    <InfoComponent />
    <FooterComponent />
  </main>
</template>

<script>
import ExpenseComponent from './components/ExpenseComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import ListToDoComponent from './components/ListToDoComponent.vue';
import InfoComponent from './components/InfoComponent.vue';
import FooterComponent from './components/FooterComponent.vue'
export default {
  name: 'App',
  components: {
    HeaderComponent,
    ExpenseComponent,
    ListToDoComponent,
    InfoComponent,
    FooterComponent,
  }
}
</script>

<style lang="scss" scoped></style>