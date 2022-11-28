<template>
  
  <div class="layer"></div>
  <!-- ! Body -->
  <a class="skip-link sr-only" href="#skip-target">Skip to content</a>
      <div class="page-flex">
        <!-- ! Sidebar -->
        <SideBar/>
        <div class="main-wrapper">
          <!-- ! Main nav -->
          <NavBar/>
          <!-- ! Main -->
          <!-- <MainTable/> -->
         <MainAdmin/>
          <!-- ! Footer -->
          
      </div>
  </div>
</template>

  
<script>
import SideBar from './components/SideBar.vue';
import NavBar from './components/NavBar.vue';
import MainAdmin from './components/MainAdmin.vue';

// import "bootstrap/dist/css/bootstrap.min.css";
// import MainTable from './components/MainTable.vue';


export default {
  name: "App",
  components: {
    SideBar,
    NavBar,
    MainAdmin,
    // MainTable
}
}
</script>