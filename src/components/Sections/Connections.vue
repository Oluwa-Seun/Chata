<!-- eslint-disable max-len -->
<template>
  <section id="connections">
    <b-container>
      <div class="content">
       <!--- <div class="image">
          <div class="profile-image">
            <b-img src="../../assets/images/connections.png" fluid data-aos="fade-right" data-aos-delay="200"></b-img>
          </div>
        </div> --->
        <div class="description">
          <div class="divider"></div>
          <h2 data-aos="fade-left" data-aos-delay="200">Our services</h2>

        </div>
      </div>
    </b-container>
    <div class="card">
        <img src="../../assets/images/Creatives.png" class="card-img" />
        <div class="card-body">
          <h5 class="card-title">Add money</h5>
          <p class="card-text">Fund your wallet</p>
       </div>
      </div>
      <div class="card">
        <img src="../../assets/images/Creatives.png" class="card-img" />
        <div class="card-body">
          <h5 class="card-title btn btn-primary">Airtime to cash</h5>
          <p class="card-text">Fund your wallet</p>
       </div>
      </div>
  </section>
</template>

<style>
.card {
  flex-direction: row;
  align-items: center;
  border-radius: 95%;
}
.card-title {
  font-weight: bold;
}
.card-img {
  flex-direction: row;
  width: 20%;
  border-radius: 50%;
}
@media only screen and (max-width: 768px) {

.card-body {
  padding: 0.5em 1.2em;
}
.card-body .card1-text {
  margin: 0;
}
.card img {
  width: 20%;
}
}
@media only screen and (max-width:1200px) {
  .card img {
    width: 40%;
  }
}
</style>
<script>
export default {
  name: 'Connections',
};
</script>
<style lang="scss">
@import "../../assets/scss/style.scss";

.service {
  height: 50%;
  width: 80%;
}
.serviceimage {
height: 20%;
width: 50%;
border-radius: 50%;
}
.description {
  color: black;
}
</style>
