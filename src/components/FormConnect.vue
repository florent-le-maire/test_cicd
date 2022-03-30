<template>
  <form action="" method="get">
    <div id="div_username" class="item">
        <label for="in_user">Username </label>
        <input id="in_user">
    </div>
    <div id="div_pass" class="item">
      <label for="in_pass">Password</label>
      <input id="in_pass">
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

  form{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: stretch;
    width: 25%;
  }
  .item{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: stretch;
    margin-bottom: 6%;
    width: 100%;
  }
  #div_buttons{
    display: flex;
    justify-content: center;
    align-items: center;
  }
  label{
    display: block;
    font-size: 20px;
    color: whitesmoke;
    margin-bottom: 3%;
  }
  input{
    display: block;
    border-radius: 4px;
    border-style: none;
    padding: 3%;
  }
  button{
    display: inline-block;
    border-radius: 4px;
    width: 100%;
    background: #3871ec;
    text-transform: uppercase;
    color: whitesmoke;
    padding: 3%;
    border-style: none;
  }
</style>
