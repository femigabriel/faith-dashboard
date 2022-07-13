<template>
  <div class="hello">
    <header>
      <div class="header">
        <div class="logo">
          <img src="../images/logo.png" alt="">
          <!-- <h3>Logo</h3> -->
        </div>
        <ul>
          <li><span>Dashboard</span></li>
          <li>Job</li>
          <li>Applicants</li>
          <li>Company</li>
        </ul>
        
      </div>
      <SearchInput />
        <h1>Settings</h1>
    </header>
  

    
  </div>
</template>

<script>
import SearchInput from "./SearchInput.vue";
export default {
  name: "HelloWorld",
  components: {
    SearchInput,
  },
  props: {
    msg: String,
  },
};
</script>

<style scoped>
header {
  padding-top: 10px;
  padding-bottom: 80px;
  background: #0a596f;
}
.logo {
  display: flex;
   
}
.logo img {
  margin: 0 30px;
  /* width: 20px; */
}
header h3 {
  font-size: 20px;
  margin: 0 40px;
  color: greenyellow;
}
header h1 {
  color: #fff;
  margin-left: 40px;
  margin-top: 40px;
}
.header {
  display: flex;
  margin: 0 10px;
}
ul {
  list-style-type: none;
  color: #fff;
  font-size: 16px;
}
li {
  display: inline-block;
  margin: 5px 10px;
}
span{
  background: #0b4657;
  padding: 5px 5px;
  border-radius: 5px;

}
/* search input */
</style>
