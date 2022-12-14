<template>
    <h2 class="Contact">Contact Us</h2>
    <div class="row col-6 form">
        <div class="mb-3">
      <label for="exampleFormControlInput1" class="form-label">Email address</label>
      <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
    </div>
    <div class="mb-3">
      <label for="exampleFormControlTextarea1" class="form-label">Message</label>
      <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
    </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    .form {
    margin: auto;
    margin-top: 50px;
}
h2 {
    font-family: 'Josefin Slab', serif;
    font-size: 70px;
    margin-top: 25px;
    color: rgb(255, 255, 255);
}
.form-label {
  font-family: 'Josefin Slab', serif;
  color: white;
  font-size: x-large;
}
</style>