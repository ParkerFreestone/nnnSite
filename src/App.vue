<template>
  <div id="app">
    <div id="nav">
      <div class="logo">
        <h1> <router-link :to="{ name : Home}"> <font-awesome-icon icon="female" /> The NNN Struggle </router-link> </h1>
      </div>
      <div class="right">
        <div class="links">
          <router-link :to="{ name : OurCause}">Our Cause</router-link>
          <router-link :to="{ name : Leaderboard}">Leaderboard</router-link> 
        </div>
        <div class="bg-purple text-white p-5 rounded bold ml-10">
            No Refunds
        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style>

body {
  background-color: #1F2937;
  margin: 0px;
  padding: 0px;
  overflow-x: hidden;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #F3F4F6;
}

#nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-left: 100px;
  padding-right: 100px;
  background-color: #111827;
}

a {
  color: #F3F4F6;
  text-decoration: none;
  transition: 0.3s ease;
  padding-left: 20px;
  padding-right: 20px;
}

a:hover {
  color: #af81ff;
}

.text-white {
  color: white;
}

.p-5 {
  padding: 10px 15px 10px 15px;
}

.bold {
  font-weight: bold;
}

.rounded {
  border-radius: 10px;
}

.bg-purple {
  background-color: #7C3AED;
}

.bg-dark {
  background-color: #111827;
}

.container {
  height: 60vh;
  padding: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

h2 {
  font-size: 3rem;
}

.right {
  display: flex;
  align-items: center;
  justify-content: center;
}

.ml-10 {
  margin-left: 3rem;
}

.text-lg {
  font-size: 1.4rem;
}

</style>
