<template>
  <div class="content mx-5">
    <h1>Todo App</h1>
    <form>
      <div class="field">
        <div class="control">
          <input type="text" />

        </div>
      </div>
      <button type="submit" class="button is-info">Add</button>
    </form>
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

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
