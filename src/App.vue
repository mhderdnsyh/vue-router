<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/contact">Contact</router-link>
    <router-link to="/activity">Activity</router-link>
    <router-link to="/basketball">Basketball</router-link>
    <router-link to="/resume">Resume</router-link>
  </nav>
  <router-view />
</template>

<style>
@import url("https://fonts.googleapis.com/css?family=Quicksand:400,700&display=swap");

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: white;
  /* margin-top: 60px; */
  padding: 0;
  margin: 0;
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
  height: 60px;
}

nav a {
  font-weight: bold;
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 35px;
  color: #ffffff;
  cursor: pointer;
  padding: 5px;
  width: fit-content;
  font-family: Impact;
  letter-spacing: 2px;
  color: #000000e1;
}

nav a:hover {
  border-bottom: 2px solid #000000;
  color: #728394;
}

nav a:active {
  background-color: #728394;
  color: rgb(0, 0, 0);
}

body {
  background-color: black;
  padding: 0;
  margin: 0;
}
</style>
