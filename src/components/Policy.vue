<template>
  <div class="side-down">
    <div class="">
      <h3>Privacy</h3>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
    </div>
    <div class="flex">
      <div class="content">
        <h3>Available to hire</h3>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <i class="las la-toggle-on"></i>
    </div>
    <div class="flex">
      <div class="content">
        <h3>Available to hire</h3>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <i id="icon" class="las la-toggle-on"></i>
    </div>
    <div class="flex">
      <div class="content">
        <h3>Available to hire</h3>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <i class="las la-toggle-on"></i>
    </div>
    <div class="flex">
      <div class="content">
        <h3>Available to hire</h3>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <i class="las la-toggle-on"></i>
    </div>
    <button class="save">Save</button>
      <button class="cancel">Cancel</button>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.side-down {
  padding: 20px 10px;
}
.flex {
  /* display: flex; */
 padding: 20px 0px;
  border-bottom: 1px solid whitesmoke;
}
p {
      color: #999;
      font-size: 13px;
}
.las {
  font-size: 36px;
  color: #0b4657;
  flex-grow: 2;
  float: right;
  margin: -20px 0px;
}
#icon {
  opacity: 0.5;
  color:darkgrey;
}
button {
  float: right;
  padding: 10px 25px;
  border: none;
  margin: 20px 10px;
  font-size: 16px;
}
.cancel {
  background: whitesmoke;
  color: #0b4657;
}
.save {
  background: #0b4657;
  color: white;
}
</style>
