<template>
  <div id="nav">
    <i class="far fa-heart"></i>
    <router-link to="/">İlk component</router-link> |
    <router-link to="/about">2. component</router-link>|
    <router-link to="/3component">3. component</router-link>|

    <router-link to="/4component">4. component</router-link>|
     <router-link to="/5component">5. component</router-link>
     |
     <router-link to="/6component">6. component</router-link>
      |
     <router-link to="/7component">7. component</router-link>
     |
     <router-link to="/8component">8. component</router-link>
      |
     <router-link to="/9component">9. component</router-link>
     |
     <router-link to="/10component">10. component</router-link>
  </div>
  
  <router-view />
</template>

<style lang="scss">
* {
  background-color: transparent;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
h1 {
  font-family: "Open Sans", sans-serif;
  font-weight: 10 !important;
  line-height: 1.2;
  font-size: 1.5rem;
  color: #f8f9fa;
}
a {
  text-decoration: none;
}
</style>
