<template>
        <section class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">Zespół</h2>
                        <p class="lead text-muted">According to the National Oceanic and Atmospheric Administration,
                            Ted, Scambos, NSIDClead scentist, puts the potentially record maximum.</p>
                            <a href="#/team" class="font-weight-bold text-primary mt-5">Więcej</a>
                    </div>
                </div>
                <div class="row justify-content-center text-center">
                    <div class="col-md-2 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/ola.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Aleksandra Hajdasz</span>
                                    <small class="h6 text-muted">Aplikant adwokacki</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="https://facebook.com/aleksandrahajdasz" type="primary" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="mailto:ahajdasz@duolegal.pl" type="primary" icon="ni ni-email-83" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/adrianna.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Adrianna Grzybowska</span>
                                    <small class="h6 text-muted">Aplikant adwokacki</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="https://facebook.com/adriannagrzybowska" type="primary" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="mailto:agrzybowska@duolegal.pl" type="primary" icon="ni ni-email-83" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
</template>
<script>
export default {};
</script>
<style>
</style>