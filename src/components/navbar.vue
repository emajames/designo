<template>
    <div class="container px-md-2">
        <nav class="navbar navbar-expand-sm pt-3">
             <a class="navbar-brand" href="#"><img class="designo" src="../assets/logo-dark.png" alt=""></a>
            <button class="navbar-toggler d-lg-none" type="button" data-toggle="collapse" data-target="#collapsibleNavId" aria-controls="collapsibleNavId"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"><i class="fa fa-bars" aria-hidden="true"></i></span>
            </button>
            <div class="collapse navbar-collapse" id="collapsibleNavId">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link pl-5" href="#">OUR COMPANY</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link pl-5" href="#">LOCATIONS</a>
                    </li>
                     <li class="nav-item">
                        <a class="nav-link pl-5" href="#">CONTACT</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
    
</template>

<style scoped>
.designo{
    width: 50%;
}
.nav-link{
    color: #000 !important;
    font-size: 15px;
    font-weight: bold;
}
.navbar{
    padding: 0;
    margin: 0;
}


@media (min-width: 0px) and (max-width: 767.98px) {
    .designo{
    width: 12rem;
}
/* .nav-link{
    padding: 0 !important;
} */
 }

</style>

