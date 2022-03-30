<template>
  <form action="" method="post">
    <div id="div_username" class="item">
        <label for="in_user">Username </label>
        <input id="in_user" placeholder="Username">
    </div>
    <div id="div_pass" class="item">
      <label for="in_pass">Password</label>
      <input id="in_pass" placeholder="Password">
    </div>
    <div id="div_buttons">
      <button type="submit">Submit</button>
    </div>
  </form>
</template>

<script>
export default {
name: "FormConnect"
}
</script>

<style scoped>

  .item{
    display: block;
    margin-bottom: 5%;
  }
  #div_buttons{
    display: flex;
    justify-content: center;
    align-items: center;
  }
  label{
    display: inline-block;
  }
  input{
    border-radius: 4px;
  }
  button{
    display: inline-block;
    border-radius: 4px;
  }
</style>
