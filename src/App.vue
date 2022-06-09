<template>
  <div id="app">
    <DcHeader/>

    <main>
        <MyJumbo/>
        <MyComics/>
        <DcMerchandise/>
    </main>

    <DcFooter/>
  </div>
</template>

<script>
import DcHeader from './components/DcHeader.vue';
import MyJumbo from './components/MyJumbo.vue';
import DcMerchandise from './components/DcMerchandise.vue';
import DcFooter from './components/DcFooter.vue';
import MyComics from './components/MyComics.vue';

export default {
  name: 'App',
  components: {
    DcHeader,
    MyJumbo,
    DcMerchandise,
    DcFooter,
    MyComics
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>
