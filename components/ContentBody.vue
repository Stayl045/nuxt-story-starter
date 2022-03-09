<template>
  <section class="mt-7">
    <div class="box box-a">
      <div class="card-container grid">
        <header>
          <h1 class="text-xl text-white">Coding and a Design Course</h1>
        </header>
        <p>
          Learn Program Technology like HTML, CSS, JavaScript, React and more.
        </p>
        <h2 class="card-btn">
          <a href="#" class="text-white flex flex-center align-center"
            >View Courses</a
          >
        </h2>
      </div>
    </div>
  </section>
</template>

<style scoped>
section {
  display: flex;
  justify-content: center;
  align-items: center;
}

.card-container {
  margin-top: 150px;
}

.box-a {
  background-image: url('https://images.pexels.com/photos/251225/pexels-photo-251225.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260');
  background-size: cover;
  background-repeat: no-repeat;
  border-radius: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 90vw;
  height: 90vh;
  box-shadow: 0 12px 12px -4px lightblue;
  color: black;
  font-weight: 900;
}

.btn {
  color: black;
}
</style>
