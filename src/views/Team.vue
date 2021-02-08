<template>
    <div class="position-relative">
        <!-- shape Hero -->
        <section class="section-shaped my-0">
            <div class="shape shape-style-1 shape-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container shape-container d-flex">
                <div class="col px-0">
                    <div class="row">
                        <div class="col-lg-6">
                            <h1 class="display-3  text-white">Partnerzy
                                <span>Text</span>
                            </h1>
                            <p class="lead  text-white">Cosby sweater eu banh mi, qui irure terry richardson ex
                            squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan
                            american apparel, butcher voluptate nisi qui.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- 1st Hero Variation -->
        
        <section class="section section-lg pt-lg-0 mt--200">

            <div class="container">
                <tabs fill class="flex-column flex-md-row">
                    <card shadow>
                        <tab-pane title="Aleksandra Hajdasz">
                            
                            <div class="row row-grid align-items-center">
                                <div class="col-md-4">
                                    <img v-lazy="'img/theme/ola_tall.jpg'" class="img-fluid rounded shadow-lg">
                                </div>
                                <div class="col-md-8">
                                    <div class="pl-md-5">
                                        <div class="text-center mt-5">
                                            <h3>Aleksandra Hajdasz
                                                <span class="font-weight-light">, 27</span>
                                            </h3>
                                            <div class="h6 font-weight-300"><i class="ni location_pin mr-2"></i>Bucharest, Romania</div>
                                            <div class="h6 mt-4"><i class="ni business_briefcase-24 mr-2"></i>Solution Manager - Creative Tim Officer</div>
                                            <div><i class="ni education_hat mr-2"></i>University of Computer Science</div>
                                        </div>
                                        <div class="mt-5 py-5 border-top text-center">
                                            <div class="row justify-content-center">
                                                <div class="col-lg-9">
                                                    <p>An artist of considerable range, Ryan — the name taken by Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and records all of his own music, giving it a warm, intimate feel with a solid groove structure. An artist of considerable range.</p>
                                                    <p class="text-right">ahajdasz@duolegal.pl <br/>525 123 222 </p>
                                                </div>
                                            </div>
                                        </div>
                                        <base-button type="default" tag="a" href="mailto:ahajdasz@duolegal.pl" size="sm" class="float-right">Skontaktuj się</base-button>
                                    </div>
                                </div>
                            </div>
                        </tab-pane>

                        <tab-pane title="Adrianna Grzybowska">
                            <div class="row row-grid align-items-center">
                                <div class="col-md-4">
                                    <img v-lazy="'img/theme/adrianna_tall.jpg'" class="img-fluid rounded shadow-lg">
                                </div>
                                <div class="col-md-8">
                                    <div class="pl-md-5">
                                        <div class="text-center mt-5">
                                            <h3>Adrianna Grzybowska
                                                <span class="font-weight-light">, 27</span>
                                            </h3>
                                            <div class="h6 font-weight-300"><i class="ni location_pin mr-2"></i>Bucharest, Romania</div>
                                            <div class="h6 mt-4"><i class="ni business_briefcase-24 mr-2"></i>Solution Manager - Creative Tim Officer</div>
                                            <div><i class="ni education_hat mr-2"></i>University of Computer Science</div>
                                        </div>
                                        <div class="mt-5 py-5 border-top text-center">
                                            <div class="row justify-content-center">
                                                <div class="col-lg-9">
                                                    <p>An artist of considerable range, Ryan — the name taken by Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and records all of his own music, giving it a warm, intimate feel with a solid groove structure. An artist of considerable range.</p>
                                                    <p class="text-right">agrzybowska@duolegal.pl <br/>525 321 333 </p>
                                                </div>
                                            </div>
                                        </div>
                                        <base-button type="default" tag="a" href="mailto:agrzybowska@duolegal.pl" size="sm" class="float-right">Skontaktuj się</base-button>
                                    </div>
                                </div>
                            </div>
                        </tab-pane>
                    </card>
                </tabs>
            </div>
        </section>
        
    </div>
</template>
<script>
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
export default {
  components: {
    Tabs,
    TabPane
  }
};
</script>
<style>
</style>
