<template>
    <footer class="footer has-cards">
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h4 class="text-primary font-weight-light mb-2">Kontakt</h4>
                    <div class="row row-grid">
                        <div class="col-md-1">
                            <i class="fa fa-map-marker" aria-hidden="true"/>
                            <i class="fa fa-phone" aria-hidden="true"/>
                            <i class="fa fa-envelope" aria-hidden="true"/>
                        </div>
                        <div class="col-md-15">
                            <h5 class="mb-0 font-weight-light">ul. Grzybowska 10</h5>
                            <h5 class="mb-0 font-weight-light">11 222 33 44, 512 345 356</h5>
                            <h5 class="mb-0 font-weight-light">biuro@duolegal.pl</h5>
                        </div>
                    </div>
                </div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a href="#/">Duolegal</a>
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a href="#/about" class="nav-link">O nas</a>
                        </li>
                        <li class="nav-item">
                            <a href="#/contact" class="nav-link">Kontakt</a>
                        </li>
                        <li class="nav-item">
                            <router-link to="/policy" class="nav-link">Polityka</router-link>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link nav-link-icon" href="https://www.facebook.com/duolegal" target="_blank" rel="noopener"
                            data-toggle="tooltip" title="Like us on Facebook">
                                <i class="fa fa-facebook-square"></i>
                                <span class="nav-link-inner--text d-lg-none">Facebook</span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link nav-link-icon" href="https://instagram.com/duolegal" target="_blank" rel="noopener"
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
</style>
