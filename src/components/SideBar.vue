<template>
  <div class="profile">
    <div class="listed-items">
      <ul>
      <li><i class="las la-user-circle"></i>Profile</li>
      <li><i class="las la-cog"></i>Account</li>
      <li><i class="las la-key"></i>Password</li>
      <li> <i class="las la-bell"></i>Notification</li>
      <li><i class="las la-wallet"></i>Billing</li>
       <li><i class="las la-network-wired"></i>Integration</li>
    </ul>
    </div>
     <FormPage class="formPage"/>
  </div>
</template>

<script>
import FormPage from './FormPage.vue';
export default {
   components: {
    FormPage
  }
};
</script>

<style scoped>
.profile {
  display: flex;
    background: #fff;
  padding-bottom: 40px;
  width: 100%;
  max-width: 97%;
  /* height: 550px; */
  margin: -60px 20px;
  border-radius: 10px;
  
}
.listed-items{
  /* border-right: 2px solid #999; */
  
}
.formPage{
  flex-grow: 2;
 
}
 
ul {
padding: 5px 10px;
list-style: none;
font-size: 16px;
font-weight: 600;
font-family: 'Open Sans', sans-serif;
/* border-right: 1px solid #999; */

}
ul:hover {
  
}
li {
  display: block;
  margin: 20px 10px;
 
}
.las {
    padding-right: 10px;
    color: darkgray;
}
li:hover {
    background: lightblue;
   
}
</style>
