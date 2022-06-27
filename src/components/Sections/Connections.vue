<!-- eslint-disable max-len -->
<template>
  <section id="connections">
    <b-container>
      <div class="content">
        <div class="description">
          <div class="divider"></div>
          <h2 data-aos="fade-left" data-aos-delay="200">Our services</h2>
        </div>
      </div>
      <div class="card mb-3">
        <div class="row g-0" style="max-width:540px">
          <div class="col-4">
           <img src="../../assets/images/Creatives.png" class="img-fluid" />
          </div>
          <div class="col-8">
            <div class="card-body">
              <h5 class="card-title">yo
              </h5>
              <p class="card-text">heyy yo</p>
            </div>
          </div>
        </div>
      </div>
      <div class="card mb-3">
        <div class="row g-0" style="max-width:540px">
          <div class="col-4">
           <img src="../../assets/images/Creatives.png" class="img-fluid" />
          </div>
          <div class="col-8">
            <div class="card-body">
              <h5 class="card-title">yo
              </h5>
              <p class="card-text">heyy yo</p>
            </div>
          </div>
        </div>
      </div>
    </b-container>

  </section>
</template>

<style>
.card1 {
  flex-direction: row;
  align-items: center;
  border-radius: 95%;
}
.card1-title1 {
  font-weight: bold;
}
.card1-img1 {
  flex-direction: row;
  width: 20%;
  border-radius: 50%;
}
@media only screen and (max-width: 768px) {

.card1-1body {
  padding: 0.5em 1.2em;
}
.card1-body .card1-text {
  margin: 0;
}
.card1 img {
  width: 20%;
}
}
@media only screen and (max-width:1200px) {
  .card1 img {
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

  width: 100%;
}
.serviceimage2 {

width: 50%;
border-radius: 90%;
}
.description {
  color: black;
}
</style>
