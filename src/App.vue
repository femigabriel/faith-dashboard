<template>
<link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/line-awesome/1.3.0/line-awesome/css/line-awesome.min.css"
  />
  <Header />
  <SideBar />
  <!-- <FormPage /> -->
  
</template>

<script>
import Header from './components/Header.vue'
import SideBar from './components/SideBar.vue'
// import FormPage from './components/FormPage.vue'
export default {
  name: 'App',
  components: {
    Header,
    SideBar,
    // FormPage
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;1,400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,500;1,400&display=swap');
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body {
    background: whitesmoke;
    color:#222;
    font-family: 'Open Sans', sans-serif;
    /* font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; */
}

</style>
