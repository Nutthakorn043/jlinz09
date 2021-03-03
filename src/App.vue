<template>
 <div id="app">
    <div id="nav">
     <b-navbar toggleable="lg" type="dark" variant="warning">
    <b-navbar-brand href="#"  > <router-link to="/">Color Grop</router-link></b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
 <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit" variant="outline-dark">Search</b-button>
        </b-nav-form>
      </b-navbar-nav>
  </b-navbar>
</div>
      
    
    <router-view />
  </div>
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
  padding: 30px;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}
#nav a.router-link-exact-active {
  color: #ffffff;
}
</style>