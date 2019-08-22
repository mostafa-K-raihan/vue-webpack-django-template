<template>
  <div class="page">
    <Topbar/>
    <Sidebar/>
    <MainContent/>
  </div>
</template>

<script>

import Topbar  from "./Topbar";
import Sidebar from "./Sidebar";
import MainContent from "./MainContent";
export default {
  name: 'Page',
  components: {
    Topbar,
    Sidebar,
    MainContent
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .page {
    display: grid;
    grid-template-columns: 30% 1fr;
    grid-template-rows: 20% 1fr;
    grid-gap: .5rem;
    border: 1px solid black;
    padding : .5rem;
    height: 100vh;
  }

</style>
