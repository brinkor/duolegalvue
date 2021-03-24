<template>
    <footer class="footer has-cards">
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h4 class="text-duo font-weight-light mb-2">Kontakt</h4>
                    <div class="container">
                        <div class="row align-items-end">
                            <div class="col-1">
                                <i class="fa fa-map-marker test duolegal_color" aria-hidden="true"/>
                            </div>
                            <div class="col-11">
                                <h5 class="mb-0 font-weight-light">ul. Twarda 18</h5>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-1">
                            </div>
                            <div class="col-11">
                                <h5 class="mb-0 font-weight-light">00-105 Warszawa (City Office)</h5>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-1">
                                <i class="fa fa-phone duolegal_color" aria-hidden="true"/>
                            </div>
                            <div class="col-11">
                                <h5 class="mb-0 font-weight-light">+48 508 599 448</h5>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-1">
                                <i class="fa fa-envelope duolegal_color" aria-hidden="true"/>
                            </div>
                            <div class="col-11">
                                <h5 class="mb-0 font-weight-light">office@duolegal.pl</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a class="duolegal_color duolegal_color_hover" href="#/">Duolegal</a>
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a href="#/contact" class="nav-link">Kontakt</a>
                        </li>
                        <li class="nav-item">
                            <router-link to="/policy" class="nav-link">Polityka</router-link>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link nav-link-icon" href="https://www.facebook.com/duolegal.pl" target="_blank" rel="noopener"
                            data-toggle="tooltip" title="Like us on Facebook">
                                <i class="fa fa-facebook-square"></i>
                                <span class="nav-link-inner--text d-lg-none">Facebook</span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link nav-link-icon" href="https://www.instagram.com/duolegal.pl/" target="_blank" rel="noopener"
                            data-toggle="tooltip" title="Follow us on Instagram">
                                <i class="fa fa-instagram" aria-hidden="true"></i>
                                <span class="nav-link-inner--text d-lg-none">Instagram</span>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
.test {
    padding-top: 25px;
}
.duolegal_color{
    color: rgb(194, 60, 143);
}
.duolegal_color_hover:hover{
    color: rgb(121, 38, 89);

}
</style>
