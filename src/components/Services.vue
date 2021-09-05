<template>
  <div class="container">
    <h3><b>Our Services</b></h3>
    <div class="row theService">
      <video
        class="theVideo"
        autoplay
        muted
        loop
        src="@/assets/connections.mp4"
      ></video>
      <div class="video-content">
        <h2>Welcome to Connect</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Services",
  };
</script>

<style scoped>
  .theService {
    position: relative;
    text-align: center;
  }
  .video-content {
    position: absolute;
    align-self: center;
    color: blanchedalmond;
    font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  }
  h3 {
    background-color: #f5f6fa;
    padding: 15px;
  }
</style>
