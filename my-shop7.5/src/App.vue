<template>
  <div id="app">
    <HeaderComponent />
    <ProductList />
    <FooterComponent />
  </div>
</template>

<script>
import ProductList from './components/ProductList.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  components: {
    HeaderComponent,
    ProductList,
    FooterComponent,
  },
};
</script>