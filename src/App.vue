<template>
  <div id="app">
    <header>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/movies">Movies</RouterLink>
      </nav>
    </header>

    <main>
      <RouterView></RouterView>
    </main>
    
    
  </div>
</template>

<script>
export default {};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
nav{
  padding: 20px, 20px,20px, 20px;
}
nav a {
  text-decoration: none;
  color: black;
  margin: 3px;
  padding: 3px;
  border: 1px solid black;
}

main {
  padding: 10px;
}
</style>
