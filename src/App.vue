<template>
  <div id="nav">
    <img id="logo" src="@/assets/v12-logo.jpeg" alt="logo"/>
    <div>
      <router-link to="/">FBMP</router-link> |
      <router-link to="/about">Classifieds</router-link> |
      <router-link to="/crm">CRM</router-link>
    </div>
  </div>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-left: 20px;
  margin-right: 20px;
}

#nav a {
  font-weight: bold;
  color: #90C207;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#logo {
  width: 150px;
  height: 150px
}
</style>
