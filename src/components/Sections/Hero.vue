<!-- eslint-disable max-len -->
<template>
  <section id="hero">
    <b-container>
      <b-row>
        <h3 data-aos="fade-up" class="message col-10">Welcome Ibukun! <br> <span class="ibukun">What would you like to send today</span></h3>
         <div>
          <b-button variant="primary" class="test1 btn__primary2 wallet bg-transparent" data-aos="fade-left"
            >10,000 NGN(wallet)</b-button
          >
        </div>
        <div class="hero-content">
          <b-button variant="primary" class="test btn__primary2" data-aos="fade-left"
            >Track Order</b-button
          >
        </div>
      </b-row>
    </b-container>
  </section>
</template>

<script>

export default {
  name: 'Hero',
};
</script>

<style lang="scss">
@import "../../assets/scss/style.scss";

.ibukun {
  color:white;
  font-size: 15px;
}
.message {
  color:white;
  font-size: 25px;
}
#hero {
  padding: 7rem 0;
  background-color:red;
  h4 {
    color: white;
  }
  h1 {
    font-size: 20px;
    color: white;
  }
  h2{
    font-size: 10px;
    line-height: 1;
    text-align: left;
    color: $white;
    margin: 5rem 10rem;
    font-size: 64px;
    width: 100%;
    max-width: 615px;
    margin: 0 auto;
  }

  p {
    color: $gray;
    text-align: right;
    width: 100%;
    max-width: 320px;
    font-size: 18px;
    line-height: 156%;
  }

  b {
    color: $green !important;
  }

  .btn__primary2 {
    left: 10%;
    position: relative;
  }

  .btn__primary {
    border: none;
    outline: none;
    width: 250%;
    border-radius: 5px;
    padding: 12px 32px;
    font-weight: bold;
    font-size: 12px;
    line-height: 16px;
    text-transform: uppercase;
    -webkit-text-decoration: none;
    text-decoration: none;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: all 0.2s ease;
    max-width: 298px;
    height: 40px;
  }
  .test1 {
    color: $primary;
  }
  .test {
    width: 80%;
  }
  .hero-content {
    position: relative;
    right: 6%;
    padding: 48px 0 20px 0;
    width: 200%;
    max-width: 665px;
    margin: 0 auto;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;

    -webkit-box-pack: justify;
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
    -webkit-align-items: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    position: relative;
  }

  .hero-shades {
    position: relative;

    &:after {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      -webkit-transform: translateY(-25%);
      -ms-transform: translateY(-25%);
      transform: translateY(-25%);
      width: 100%;
      height: 100%;
      z-index: -1;
      background: radial-gradient(
        50% 50% at 50% 50%,
        #4f0de9 0%,
        rgba(20, 17, 17, 0) 100%
      );
      opacity: 0.4;
    }
  }
}
</style>
