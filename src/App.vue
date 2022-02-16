<template>
  <div id="nav">
   
    <router-link to="/">Home</router-link> |
    <router-link to="/english">English</router-link>
  </div>
  <router-view /> 

  
</template>
<script>


export default{

data() { 
  return {
  
    }
  }

}
</script>

<style>


#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html,
body {
  font-family: Arial, Helvetica, sans-serif;
}
.result {
  padding-bottom: 20px;
}
#app {
  width: 100%;
  height: 100vh;
  margin: auto;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: lightblue;
}



button {
  cursor: pointer;
  display: inline-block;
  background: teal;
  color: white;
  font-size: 18px;
  border: 0;
  padding: 1rem 1.5rem;
}

button:focus {
  outline: none;
}

button:hover {
  transform: scale(0.99);
}

</style>