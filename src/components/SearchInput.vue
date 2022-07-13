<template>
  <div class="side-bar">
    <div class="search">
      <i id="search" class="las la-search"></i>
      <div class="search-input">
        <input type="text" placeholder="Search" />
      </div>
    </div>
    <div class="profile">
      <i class="lar la-bell"></i>
      <img src="../images/Dp.png" alt="profile" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.side-bar {
  float: right;
  display: flex;
  margin: -25px 50px;
}
input {
  background: #76767621;
  color: #fff;
  width: 100%;
  font-size: 22px;
  border: none;
  outline: none;
  border-radius: 10px;
  /*  */
}
.search {
  margin-right: -40px;
}

input::placeholder {
  color: #fff;
  padding-left: 30px;
  font-size: 15px;
  opacity: 0.5;
}
.las {
  font-size: 22px;
  color: #fff;
  position: relative;
  left: 25px;
  top: 7px;
  opacity: 0.5;
}
.search {
  display: flex;
}
.profile {
  display: flex;
  padding: ;
}

.lar {
  font-size: 32px;
  color: whitesmoke;
  margin: 0 40px;
  opacity: 0.5;
}
.profile img {
  width: 35px;
}
</style>
