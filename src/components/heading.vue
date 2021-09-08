<template>
  <div class="container px-md-5 mb-5">
    <div class="heading d-flex">
      <div class="heading-con py-md-5 pl-md-5">
        <div class="py-md-5 pl-md-5 text-white px-1 pt-3 words">
          <h2 class="award pb-3">
            Award-winning custom <br />
            designs and digital <br />
            branding solutions
          </h2>
          <p class="para pb-3">
            With over 10 years in the industry, we are experienced in <br />
            creating fully responsive websites, app design, and engaging
            <br />
            brand experiences. Find out more about our services.
          </p>
          <button class="btn py-2">Learn More</button>
        </div>
      </div>
      <div class="heading-image">
        <img
          src="../assets/desktop/bg-pattern-hero-home.svg"
          alt=""
          width="580rem"
        />
      </div>
      <div class="heading-circle">
        <img
          src="../assets/desktop/image-hero-phone.png"
          alt=""
          width="570rem"
          class="image"
        />
      </div>
    </div>
    <div class="leaf-con">
      <img src="../assets/desktop/bg-pattern-leaf.svg" alt="" class="leaf" />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.leaf-con {
  position: absolute;
  left: -6.5rem;
  bottom: -11.5rem;
}
.leaf {
  width: 90%;
}
.container {
  position: relative;
}
.heading {
  position: relative;
  border-radius: 1rem;
  background-color: #e7816b;
  padding: 2rem 0px;
  overflow: hidden;
  z-index: 3;
}
.heading-image {
  position: absolute;
  top: 0;
  right: 0;
}
.heading-circle {
  z-index: 3;
  position: absolute;
  top: -35px;
  right: -45px;
}
.award {
  font-size: 44px;
}
.para {
  font-size: 15px;
}
.btn {
  background-color: #fff;
  text-transform: uppercase;
  font-size: 13px !important;
  font-weight: 500;
}
@media (min-width: 768px) and (max-width: 1023.98px) {
  .container {
    padding: 0 !important;
  }
  .heading {
    padding: 0rem 0px;
    display: flex;
    justify-content: center !important;
    align-items: center !important;
    padding-bottom: 22rem;
  }
  .words {
    padding-left: 0 !important;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center !important;
    align-items: center !important;
  }
  .heading-con {
    padding: 0rem !important;
  }
  .heading-image {
    position: absolute;
    top: 0;
    right: 0;
  }
  .heading-circle {
    z-index: 3;
    position: absolute;
    top: 250px;
    left: auto !important;
    right: auto !important;
  }
  .award {
    font-size: 44px;
  }
  .para {
    font-size: 15px;
  }
  .btn {
    background-color: #fff;
    text-transform: uppercase;
    font-size: 13px !important;
    font-weight: 500;
  }
}
@media (min-width: 0px) and (max-width: 767.98px) {
  .leaf-con {
    display: none;
  }
  .container {
    padding: 0;
    position: relative;
  }
  .heading {
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    border-radius: 0rem;
    padding: 0px 1rem;
    padding-top: 3rem;
    padding-bottom: 29rem;
  }
  .heading-image {
    position: absolute;
    top: 0;
    right: 0;
  }
  .heading-circle {
    position: absolute;
    left: auto !important;
    right: auto !important;
    top: 250px;
  }
  br {
    display: none;
  }
  .image {
    width: 700px !important;
  }
  .award {
    font-size: 35px;
  }
  .para {
    font-size: 18px;
  }
}
@media (min-width: 375px) and (max-width: 424.98px) {
  .heading {
    padding: 0px 1rem;
    padding-top: 2rem;

    padding-bottom: 27rem;
  }
  .heading-circle {
    top: 230px;
  }
  .image {
    width: 650px !important;
  }
  .award {
    font-size: 33px;
  }
  .para {
    font-size: 15.5px;
  }
}
@media (min-width: 0px) and (max-width: 374.98px) {
  .heading {
    padding: 0px 1rem;
    padding-top: 2rem;

    padding-bottom: 22rem;
  }
  .heading-circle {
    top: 200px;
  }
  .image {
    width: 530px !important;
  }
  .award {
    font-size: 28px;
  }
  .para {
    font-size: 13px;
  }
}
</style>