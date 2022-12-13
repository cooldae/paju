<template>
  <div id="app">
    <div id="nav">
      
    </div>
    <div>
      <Main></Main>
    </div>
    <router-view/>
  </div>
</template>

<script>
import Main from '@/views/Main.vue'
    export default {
        name: 'App',
        data() {
            return {

            }
        },
        components: {
          Main
        }
    }
    
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

#nav {
  margin-bottom: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  padding-right: 10px;
}

#nav a:not(:first-child) {
  padding-left: 20px; 
}

.topnav {
  background-color: #EAEAEA;
  overflow: hidden;
}

/* Style the links inside the navigation bar */
.topnav a {
  float: left;
  padding: 10px 15px;
  text-decoration: none;
  font-size: 9px;
}
</style>