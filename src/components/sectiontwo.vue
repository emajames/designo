<template>
<div class="container px-md-2">
    <div class="sectiontwo d-flex justify-content-between mb-5">
      <div class="item text-center">
        <div class="item-image py-4">
          <div class="circle">
            <img src="../assets/desktop/bg-pattern-hero-home.svg" alt="" width="160rem">
            <div class="image">
              <img src="../assets/desktop/illustration-passionate.svg" alt="" width="150rem">
            </div>
          </div>
        </div>
        <div class="item-name pb-4">Passionate</div>
        <div class="item-details">
          Each Project starts with an in-depth brand research <br>
          to ensure we only create products that serve a <br>
          purpose. We merge art, design, and technology <br>
          into exciting new solutions.
        </div>
      </div>
      <div class="item text-center">
        <div class="item-image py-4">
          <div class="circle">
            <img src="../assets/desktop/bg-pattern-hero-desktop.svg" alt="" width="160rem">
            <div class="image">
              <img src="../assets/desktop/illustration-resourceful.svg" alt="" width="150rem">
            </div>
          </div>
        </div>
        <div class="item-name pb-4">resourceful</div>
        <div class="item-details">
          Everything that we do has a stategic purpose. We <br>
          use an agile approach in all of our projects and <br>
          value customer collaboration. It guarantees <br>
          superior results that fulfill our clients' needs.
        </div>
      </div>
      <div class="item text-center">
        <div class="item-image py-4">
          <div class="circle">
            <img src="../assets/desktop/bg-pattern-hero-home.svg" alt="" width="160rem">
            <div class="image">
              <img src="../assets/desktop/illustration-friendly.svg" alt="" width="150rem">
            </div>
          </div>
        </div>
        <div class="item-name pb-4">friendly</div>
        <div class="item-details">
          We are a group of enthusiastic folks who know <br>
          how to put people first. Our success depends on <br>
          our customers, and we strive to give them the best <br>
          experience a company can provide.
        </div>
      </div>
    </div>

</div>
    
</template>

<style scoped>
.item-name {
  text-transform: uppercase;
  font-size: 18px;
  font-weight: 500;
  letter-spacing: 4px;
}
.circle {
  position: relative;
  z-index: 1;
}
.image {
  z-index: 50;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
}
.item-details {
  font-size: 15px;
}
@media (min-width: 0px) and (max-width: 767.98px) {
  .sectiontwo{
    display: block !important;
  }
  .item-details{
    font-size: 12px;
  }
  .item{
    margin-top: 3rem;
  }
}

</style>