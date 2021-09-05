<template>
  <div class="contact">
    <div class="container">
      <footer class="footerBG text-center text-lg-start">
        <div class="container p-4">
          <div class="row">
            <div class="col-lg-6 col-md-12 mb-4 mb-md-0">
              <h4 class="text-center">Connect Egypt</h4>
              <img
                src="../assets/connectegypt/p.p.jpg"
                class="rounded mx-auto d-block"
                alt="..."
              />
            </div>
            <div class="col-lg-6 col-md-12 mb-4 mb-md-0 text-center">
              <div>
                <h4>Stay Connected</h4>
                <div class="socialMedia">
                  <a
                    href="https://www.facebook.com/connectEGYPT1"
                    target="_blank"
                    ><i class="fab fa-facebook fa-3x"></i
                  ></a>
                  <a
                    href="https://www.instagram.com/connectegypt1/"
                    target="_blank"
                    ><i class="fab fa-instagram fa-3x"></i
                  ></a>

                  <a href="#" target="_blank"
                    ><i class="fab fa-twitter fa-3x"></i
                  ></a>
                </div>
              </div>
              <div>
                <h4>Address</h4>
                <p>11st train station Tanta</p>
              </div>
            </div>
          </div>
        </div>

        <!-- Copyright -->
        <div class="text-center p-3" style="background-color: #fc5c65">
          © 2021 Copyright:
          <a class="text-dark" href="https://mdbootstrap.com/"
            >ConnectEgypt.com</a
          >
        </div>
        <!-- Copyright -->
      </footer>
    </div>
  </div>
</template>

<script>
  export default {
    name: "ContactUs",
  };
</script>

<style scoped>
  img {
    width: 20%;
  }
  .socialMedia {
    display: flex;
    justify-content: space-evenly;
    margin-bottom: 3%;
  }
  .footerBG {
    background-color: #f5f6fa;
  }
</style>
