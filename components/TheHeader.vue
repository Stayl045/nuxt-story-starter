<template class="py-1.5">
  <section class="mt-8">
    <header>
      <h1 class="text-xl">Dev Ed Landing Page</h1>
    </header>
    <div class="links">
      <NuxtLink to="/" class="text-black font-extrabold mx-3"
        >Merch Store</NuxtLink
      >
      <NuxtLink to="/" class="text-black font-extrabold mx-3">Login</NuxtLink>
      <NuxtLink to="/" class="text-black font-extrabold mx-3">Sign Up</NuxtLink>
    </div>
  </section>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  text-decoration: none;
  list-style: none;
  box-sizing: border-box;
}

/* template {
} */

/* NuxtLink {
  text-decoration: none;
  list-style-type: none;
} */
/* 
.links {
  display: flex;
  text-decoration: none;
  list-style-type: none;
} */

section {
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  align-items: center;
  background-color: #39537b;
  color: white;
  margin: 5px;
  padding: 10px;
}

/* header {
  background-color: #39537b;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding-top: 20px;
  padding-bottom: 20px;
  width: 100%;
  text-align: center;
  border: 2px solid black;
  color: white;
  font-family: 'Open Sans', sans-serif;
  animation: slide-in 1000ms;
  animation-timing-function: linear;
} */

nav {
  display: flex;
  justify-content: space-evenly;
  opacity: 0.7;
  width: 100%;
}

nav ul {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  justify-content: center;
}

li {
  display: flex;
  justify-content: end;
  flex-direction: column;
  color: white;
}
</style>
