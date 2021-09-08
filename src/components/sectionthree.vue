<template>
    <div class="container px-md-2">
         <div class="sectionthree py-4 px-md-5 text-light d-flex justify-content-between flex-wrap">
      <div class="circle">
        <img  src="../assets/desktop/bg-pattern-call-to-action.svg" alt="" width="75%">
      </div>
      <div class="px-4 pt-4 oop">
        <h2>
          Let's talk about <br>
          your project
        </h2>
        <p>
          Ready to take it to the next level? Contactus today and find out how
          <br>
          our expertise can help your business grow.
        </p>
      </div>
      <div class="d-flex align-items-center px-md-4 oop">
        <button class="btn py-2 px-2">Get In Touch</button>
      </div>
    </div>
    </div>
</template>

<style scoped>

.container {
  position: relative;
}
.circle {
  position: absolute;
  top: -43%;
  right: -220px;
}
.sectionthree {
  background-color: #e7816b;
  border-radius: 1rem;
  position: relative;
  bottom: -50px;
  overflow: hidden;
}

h2 {
  font-size: 37px;
}
.btn {
  background-color: #fff;
  text-transform: uppercase;
  font-size: 15px !important;
  font-weight: 500;
}
.oop {
  z-index: 10;
}


@media (min-width: 0px) and (max-width: 767.98px){
  h2 {
  font-size: 23px;
  text-align: center;
}
  p{ font-size: 13px;
}
.btn{
  margin-left: 6.5rem ;
}
.sectionthree{
  bottom: -20px;
}

}
</style>