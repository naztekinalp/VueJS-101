<template>
    <div class="Main">
        <Header/>
        <Card/>
        <Table/>
    </div>
</template>

<script>
import Header from './TopSection/Header.vue';
import Card from './Cards/Card.vue';
import Table from './Footer/Table.vue';

export default {
  name: 'main',
  components: {
    Header,
    Card,
    Table,
  },
};
</script>

<style lang="scss" scoped>
.Main{
    float:right;
    width: 80%;
    height:610px;
    background-color: #F1F3F9;
}
</style>
