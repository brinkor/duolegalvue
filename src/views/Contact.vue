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
                        <!-- <h2 class="display-3 text-white">Skontaktuj się</h2>
                        <p class="lead text-white"></p> -->
                    </div>
                </div>
                <!-- <div class="row row-grid mt-5">
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
                </div> -->
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Masz pytanie?</h4>
                            <p class="mt-0">Napisz do nas</p>
                            <form action="mailto:office@duolegal.com?subject=Pytanie duolegal.pl" method="post" enctype="text/plain">
                            <div class="form-group mt-5">
                                <div class="input-group">
                                    <div class="input-group-prepend">
                                        <span class="input-group-text" id="basic-addon1">
                                            <i class="ni ni-circle-08" aria-hidden="true"/>
                                        </span>
                                    </div>
                                    <input type="text" name="name" class="form-control" placeholder="Twoje imię" aria-label="Username" aria-describedby="basic-addon1">
                                </div>
                            </div>
                            <div class="form-group">
                                <div class="input-group">
                                    <div class="input-group-prepend">
                                        <span class="input-group-text" id="basic-addon2">
                                            <i class="ni ni-email-83" aria-hidden="true"/>
                                        </span>
                                    </div>
                                    <input type="text" name="mail" class="form-control" placeholder="Twój email" aria-label="mail" aria-describedby="basic-addon2">
                                </div>
                            </div>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="comment" rows="4"
                                              cols="80" placeholder="Napisz wiadomość..."></textarea>
                            </base-input>
                            <base-button nativeType="submit" type="Secoundary" class="duo_btn duo_grey_btn" value="Send" round block size="lg">
                                Wyślij wiadomość
                            </base-button>
                            
                            </form>
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
.duo_grey_btn{
    background-color: #ced4da;
}
</style>
