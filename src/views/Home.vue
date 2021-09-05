<template>
  <div class="home">
    <div class="container">
      <div class="row">
        <img
          class="col"
          alt="Vue logo"
          src="../assets/connectegypt/cover.jpg"
        />
      </div>
      <h3><b>The Products</b></h3>
      <TheProducts />
      <Services />
      <ContactUs />
    </div>
  </div>
</template>

<script>
  // @ is an alias to /src
  import TheProducts from "@/components/TheProducts.vue";
  import Services from "@/components/Services.vue";
  import ContactUs from "@/components/ContactUs.vue";

  export default {
    name: "Home",
    components: { TheProducts, Services, ContactUs },
  };
</script>

<style scoped>
  h3 {
    background-color: #f5f6fa;
    padding: 15px;
    margin-top: 10px;
  }
</style>
