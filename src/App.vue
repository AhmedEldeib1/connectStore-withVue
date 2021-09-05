<template>
  <div id="app">
    <div class="container">
      <div id="nav">
        <h1>eCommerce Store</h1>

        <div class="dropdown">
          <i class="fas fa-ellipsis-h dropbtn"></i>
          <div class="dropdown-content">
            <a href="#"><router-link to="/">Home</router-link></a>
            <a href="#"><router-link to="/about">About</router-link></a>
          </div>
        </div>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }

  #nav {
    padding: 10px;
    display: flex;
    justify-content: space-between;
    background-color: #f53b57;

    a {
      font-weight: bold;
      color: #2c3e50;

      &.router-link-exact-active {
        color: blue;
      }
    }
  }
  .dropbtn {
    // background-color: #4caf50;
    color: white;
    padding: 16px;
    font-size: 16px;
    border: none;
    cursor: pointer;
  }

  .dropdown {
    position: relative;
    display: inline-block;
  }

  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
    top: 45px;
    right: 0px;
  }

  .dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    transition: margin-right 0.3s ease-out 100ms;
  }

  .dropdown-content a:hover {
    background-color: #f1f1f1;
    margin-right: 10px;
  }

  .dropdown:hover .dropdown-content {
    display: block;
  }
</style>
