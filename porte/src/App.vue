<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> | 
      <router-link to="/pictures">Pictures</router-link>|
       <router-link to="/skills">Skills</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
  font-size: 10px;
  
  
  
  
  
  
  
}
body{

  background-color: silver;
 
  
}
a {
  color: black;
}


#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: black;

    &.router-link-exact-active {
      color: #E19873; 
      lighting-color: silver;
    }
  }

  a:hover {
    background-color: brown; 
    
  }
}

</style>
!