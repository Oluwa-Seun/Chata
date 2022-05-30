<!-- eslint-disable max-len -->
<template>
  <section id="achievements">
    <b-container id="sendme">
      <div class="content">
        <div class="description">
          <div class="divider"></div>
          <h2 class="divd" data-aos="fade-right" data-aos-delay="200">Send a package</h2>
          <p class="divd1" data-aos="fade-up" data-aos-delay="200"> Enjoy quick delivery to any destination
          </p>
          <div>
          <b-button variant="primary" class="btn__primary" data-aos="fade-left"
            >Send/Pick up</b-button
          >
         </div>
        </div>
        <div class="image">
          <div class="gamification-image">
            <b-img src="../../assets/images/Creatives.png" fluid data-aos="fade-left" data-aos-delay="200"></b-img>
          </div>
        </div>
      </div>
    </b-container>
  </section>
</template>

<style lang="scss">
@import "../../assets/scss/style.scss";

#achievements {
  background-color: white;
  .image {
    &:before, &:after {
      background: none !important;
    }
  }
}

</style>
