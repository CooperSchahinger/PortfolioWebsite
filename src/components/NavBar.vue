<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
</template>

<style scoped>
#nav {
  padding: 30px;
  font-weight: bold;
  text-align: center;
}

#nav a {
  color: whitesmoke;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: purple;
}
</style>
