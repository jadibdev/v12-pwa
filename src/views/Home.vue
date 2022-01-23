<template>
  <div class="home" id="showcase">
    <h1><span>SHOWCASE YOUR INVENTORY</span> ON FACEBOOK, INSTAGRAM AND MARKETPLACE</h1>
    <img src="@/assets/mac-facebook.jpeg" alt="mac-facebook"/>
  </div>

  <div class="home">
    <h1>Post Inventory To Marketplace</h1>
    <p id="fb-post">V12Software will continue to post inventory on behalf of its customers, 
    saving you time and ensuring you continue to get hot leads from Marketplace.</p>
    <img src="@/assets/fb-stairs.png" alt="fb stairs"/>
  </div>

  <div class="home">
    <h1>Showcase Vehicle Listings on Your Dealership Page</h1>
    <p id="fb-post">With V12Software, keeping your inventory up to date on your Facebook Page, is done on your behalf.</p>
    <p id="fb-post">You can use our feed to showcase your full inventory on the vehicles tab of your Facebook Business page.</p>
    <img src="@/assets/fb-laptop.png" alt="fb stairs"/>
  </div>
</template>

<script>

//import About from "./About.vue"

export default {
  name: "Home",
  components: {
    
  }
};
</script>

<style>
.home {
  margin-top: 50px;
  margin-right: 20px
}
img {
  max-width: 100%;
  height: auto;
}
span {
  color: #89C34A
}
#fb-post {
  font-size: 28px
}
</style>