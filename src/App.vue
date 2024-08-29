<script setup>
import MyCard from './components/MyCard.vue';
import MyNav from './components/MyNav.vue';
import items from './god.json'
import Reference from './components/Reference.vue';
</script>

<template>
    <div class="container">
    <header>
      <MyNav />
    </header>
    <main>
      <h1>12 เทพเจ้าแห่งโอลิมปัส</h1>
      <div className="grid-container">
        <MyCard v-bind="items[0]" />
        <MyCard v-bind="items[1]" />
        <MyCard v-bind="items[2]" />
        <MyCard v-bind="items[3]" />
        <MyCard v-bind="items[4]" />
        <MyCard v-bind="items[5]" />
        <MyCard v-bind="items[6]" />
        <MyCard v-bind="items[7]" />
        <MyCard v-bind="items[8]" />
        <MyCard v-bind="items[9]" />
        <MyCard v-bind="items[10]" />
        <MyCard v-bind="items[11]" />
      </div>
    </main>
    </div>
    <footer>
      <Reference />
    </footer>
</template>

<style scoped>
body{
    text-align: center;
}
.grid-container {
    display: grid;
    grid-column-gap: 0.5rem;
    grid-row-gap: 0.5rem;
}
footer{
    border: 1px solid black;
    background-color: grey;
}
@media (min-width: 576px) {
  .grid-container { grid-template-columns: repeat(1, 1fr); }
}
@media (min-width: 992px) {
  .grid-container { grid-template-columns: repeat(3, 1fr); }
}

</style>





