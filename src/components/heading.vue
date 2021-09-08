<template>
<div class="container px-md-2">
    <div class="heading d-flex">
      <div class="heading-con py-md-5 pl-md-5">
        <div class="py-md-5 pl-md-5 text-white px-1 pt-2">
          <h2 class="award pb-3">
            Award-winning custom <br>
            designs and digital <br>
            branding solutions
          </h2>
          <p class="para pb-3">
            With over 10 years in the industry, we are experienced in <br>
            creating fully responsive websites, app design, and engaging
            <br>
            brand experiences. Find out more about our services.
          </p>
          <button class="btn py-2">Learn More</button>
        </div>
      </div>
      <div class="heading-image">
        <img src="../assets/desktop/bg-pattern-hero-home.svg" alt="" width="580rem">
      </div>
      <div class="heading-circle">
        <img src="../assets/desktop/image-hero-phone.png" alt="" width="570rem" class="image">
      </div>
    </div>

</div>
    
</template>

<style scoped>
.heading {
  position: relative;
  border-radius: 1rem;
  background-color: #e7816b;
  padding: 2rem 0px;
  overflow: hidden;
  margin-top: 3rem;
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



@media (min-width: 0px) and (max-width: 767.98px){
.heading {
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  position: relative;
  border-radius: 1rem;
  background-color: #e7816b;
  padding-bottom: 20rem;
  overflow: hidden;
  margin-top: 3rem;
}
.award {
  font-size: 25px;
  text-align: center;
}
.para {
  font-size: 10.5px;
  text-align: center;
}
/* .heading-image {
  position: absolute;
  top: 5rem !important;
  right: 0;
} */
.heading-circle {
  z-index: 3;
  width: 29rem !important;
  position: absolute;
  top: 11rem;
  right: -2.2rem;
}
/* .btn{
margin-right: auto !important;
margin-left: auto !importantS;
} */
}

</style>