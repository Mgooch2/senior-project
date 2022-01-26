<template>
  <header>
    <div class="logo">
      <img id="logo" alt="logo" src="src/assets/medlogo.png">
    </div>
    <div class="buttons">
      <button id="login">Log In</button>
      <button id="register">Register</button>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
header{
  display:flex;
}
#logo{
  height: 75px;
  width: 180px;
}
#login{
  margin-inline-end: 5px;
  background-color:white;
  color: #133576;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-size: 14px;
  width: 120px;
}
#register{
  margin-inline-end: 5px;
  background-color:#133576;
  color: white;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-size: 16px;
  width: 120px;
}
button{
  padding:10px;
  border-radius: 8px;
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
  cursor: pointer;
}
button:hover{
  background-color:navy
}
.buttons{
  text-align: right;
  margin-bottom: 20px;
}
.logo{
  display: flex;
  flex-direction:row;
  flex:auto;
  text-align: left;
}
</style>