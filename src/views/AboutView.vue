<script setup>
// import Header from "../components/Header.vue";
</script>
<template>
  <!-- <Header /> -->
  

  <div class="row">
    <div class="col-sm-12 mt-5">
      <div class="about-me">
        <div class="profile-card">
          <div class="profile-body-content">
            <div class="profile-image">
              <img src="" alt="">
            </div>
            <h2 style="text-align: center;">Franklin <br> Ramos</h2>
            <small style="text-align: center;" class="text-muted">Graphic designer & <br> Motion graphic animator</small>
          </div>
          <div class="profile-footer">
            <a href=""><span class="fa-brands fa-linkedin"></span></a>
            <a href=""><i class="fa-brands fa-instagram"></i></a>
            <a href=""><i class="fa-brands fa-behance"></i></a>
          </div>
        </div>
        <div class="profile-content">
          <h1 class="header-title">
            HELLO!
          </h1>
          <small class="self-intro">
            I am Franklin P. Ramos. I am a graphic artist and designer in the Philippines. I’ve been in the industry since 2009. I started as a trainer for 2D Animation classes and aspiring graphic artists and designers. I have my National Certificate (NC) in 2D Animation NC – III and Visual Graphic Design (VGD–NC–III). My previous employment involved so much designing related works like logo design, promo banners, ad campaigns, product packaging, flyers, brochures, infographics, Image editing, Video editing, and the like.
          </small>
          <div class="mt-5 action-btn">
            <a href="" class="btn btn-outline-info">Download CV</a>
            <a href="" class="btn btn-outline-info">Portfolio</a>
          </div>
          
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.about-me {
  /* margin-top: 300px; */
  /* margin: auto; */
  vertical-align: middle;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 3rem;
}
.profile-card {
  /* position: absolute; */
  width: 30%;
  height: auto;
  background-color: #fff;
  border-radius: 7px;
  box-shadow: 0px 4px 40px rgba(0, 0, 0, 0.1), -20px 20px 0px rgba(147, 147, 147, 0.1);
}
.profile-body-content {
  padding: 2rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 2rem;
}
.profile-image {
  width: 180px;
  height: 180px;
  border-radius: 90px;

  background: #D9D9D9;
}
.profile-footer {
  background-color: #eeeeeeab;
  height: 50px;
  border-top: 1px solid rgba(153, 153, 153, 0.3);
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 2rem;
}
.profile-footer a {
  font-size: 16pt;
}
.profile-content {
  width: 30%;
}
.header-title {
  font-size: 80px;
  font-weight: bold;
}

.self-intro {
  width: 100%;
}
.action-btn {
  display: flex;
  gap: 2rem;
}
</style>
