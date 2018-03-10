<template>
  <div class="wrapper">
    <h2>Keep your pets healthy with</h2>
    <h1 class="name">
      <span>Laurel Springs</span> Animal Hospital</h1>
    <nuxt-link to="/aboutus" class="about-link">About Us</nuxt-link>
    <video src="https://res.cloudinary.com/kaptivating-io/video/upload/f_auto,q_auto/v1520718021/Puppiness_c5u1r7.mp4" autoplay loop></video>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.wrapper {
  width: 100%;
  height: 100vh;
  overflow: hidden;
}

.wrapper video {
  /*object-fit: contain;*/
  /*       object-fit: fill; */
  object-fit: cover;
  width: 100%;
  height: 100%;
}

h2 {
  font-family: sans-serif;
  color: white;
  margin-left: 20px;
  position: absolute;
  z-index: 2;
  font-size: 50px;
  top: 20%;
  text-shadow: 4px 4px 0 rgba(0, 0, 0, 0.4);
  text-transform: uppercase;
}
h1 {
  font-family: sans-serif;
  color: white;
  margin-left: 40%;
  position: absolute;
  z-index: 2;
  font-size: 50px;
  bottom: 5%;
  text-shadow: 4px 4px 0 rgba(0, 0, 0, 0.4);
  text-transform: uppercase;
}
span {
  color: #0eb32c;
}

.about-link {
  font-family: sans-serif;
  color: #3E99EF;
  margin-left: 10%;
  position: absolute;
  z-index: 2;
  font-size: 40px;
  bottom: 30%;
  text-shadow: 4px 4px 0 rgba(0, 0, 0, 0.4);
  text-transform: uppercase;
  text-decoration: none;
  font-weight: bold;

}
</style>
