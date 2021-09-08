<template>
<div class="container px-md-2">
     <div class="sectionone">
      <div class="grid-item1 item text-white">
        <div class="name pb-1">Web Design</div>
        <div class="view">
          View Projects
          <span class="arrow pl-2"> <i class="far fa-chevron-right"></i></span>
        </div>
      </div>
      <div class="grid-item2 item text-white">
        <div class="name pb-1">App Design</div>
        <div class="view">
          View Projects
          <span class="arrow pl-2"> <i class="far fa-chevron-right"></i></span>
        </div>
      </div>
      <div class="grid-item3 item text-white">
        <div class="name pb-1">Graphic Design</div>
        <div class="view">
          View Projects
          <span class="arrow pl-2"> <i class="far fa-chevron-right"></i></span>
        </div>
      </div>
    </div>

</div>
    
</template>


<style scoped>
.sectionone {
    margin-top: 8rem;
  display: grid;
  grid-template-columns: auto auto;
  grid-gap: 25px;
}
.grid-item1 {
  border-radius: 1rem;
  height: 591px;
  grid-row: 1/3;
  background-blend-mode: overlay;
  background-color: rgba(0, 0, 0, 0.342);
  background-image: url(../assets/desktop/image-web-design-large.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.grid-item2 {
  border-radius: 1rem;
  background-blend-mode: overlay;
  background-color: rgba(0, 0, 0, 0.342);
  background-image: url(../assets/desktop/image-app-design.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.grid-item3 {
  border-radius: 1rem;
  background-blend-mode: overlay;
  background-color: rgba(0, 0, 0, 0.342);
  background-image: url(../assets/desktop/image-graphic-design.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-transform: uppercase;
}
.name {
  font-size: 35px;
  letter-spacing: 2px;
}
.view {
  font-size: 14px;
  letter-spacing: 3px;
}
.arrow {
  font-size: 10px;
  color: #e7816b;
}
@media (min-width: 0px) and (max-width: 767.98px) {
  .sectionone{
    display: block !important;
    margin-top: 3rem;
  }
  .grid-item1 {
  height: auto;
}
.item{
  height: 15rem;
  margin-bottom: 1.5rem;
}
}

</style>