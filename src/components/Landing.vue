<template>
  <section>
    <article class="col1">
      <div class='text'>
        <p id="welcome">Welcome to Total Health Portal!</p>
        <p id="fluff">We offer an innovative telemedicine application.</p>
      </div>
      <div class='gs_btn'>
        <button id="gs_btn">Get Started</button>
      </div>
    </article>
    <article class="col2">
      <div>
        <img id="pic3" alt="pic3" src="src/assets/person-3.jpg">
        <img id="pic4" alt="pic4" src="src/assets/person-4.jpg">
      </div>
      <div>
        <img id="pic2" alt="pic2" src="src/assets/person-2.jpg">
        <img id="pic1" alt="pic1" src="src/assets/person-1.jpg">
      </div>
    </article>
  </section>
</template>

<script>
export default {
  name: "Landing"
}
</script>

<style scoped>
section{
  display: flex;
  height: 1000px;
  max-width: 100%;
  background: linear-gradient(to right, #FFFFFF 0%, #347DB4 72%, #133576 100%)
}
.col1{
  display: flex;
  flex-direction: column;
  flex: 60%;
  margin-top: 200px;
}
#welcome{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-size: 60px;
  color: #133576;
}
#fluff{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-size: 32px;
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
#gs_btn{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-size: 16px;
  text-align: center;
  background-color: white;
  color:#133576;
  width: 140px;
}
.col2{
  display: flex;
  flex-direction: column;
  flex: 40%;
  align-self: center;
}
#pic1{
  height: 300px;
  width: 300px;
  padding: 7px;
}
#pic2{
  height: 300px;
  width: 300px;
  padding: 7px;
}
#pic3{
  height: 300px;
  width: 300px;
  padding: 7px;
}
#pic4{
  height: 300px;
  width: 300px;
  padding: 7px;
}
</style>