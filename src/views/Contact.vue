<template>
    <div>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">Skontaktuj się</h2>
                        <p class="lead text-white">According to the National Oceanic and Atmospheric Administration,
                            Ted, Scambos, NSIDClead scentist, puts the potentially record low maximum sea ice extent
                            tihs year down to low ice.</p>
                    </div>
                </div>
                <div class="row row-grid mt-5">
                    <div class="col-lg-4">
                        <h5 class="text-white mt-3">Chciałbyś powierzyć nam sprawę?</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                    <div class="col-lg-4">
                        <h5 class="text-white mt-3">Chcesz o coś zapytać?</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                    <div class="col-lg-4">
                        <h5 class="text-white mt-3">Launch time</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Masz pytanie?</h4>
                            <p class="mt-0">Pomożemy Ci w każdej sprawie.</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Twoje imię"
                                        addon-left-icon="ni ni-circle-08">
                            </base-input>
                            <base-input alternative
                                        placeholder="Twój email"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Napisz wiadomość..."></textarea>
                            </base-input>
                            <base-button type="default" round block size="lg">
                                Wyślij wiadomość
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
export default {};
</script>
<style>
</style>
