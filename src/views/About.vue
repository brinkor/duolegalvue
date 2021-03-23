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
                            <div class="col-lg-8">
                                <blockquote class="blockquote text-white">
                                    <p class="h5 mb-0 text-white">&bdquo;Jeśli priorytety klientów nie są naszymi priorytetami, nie mamy żadnych priorytetów.&ldquo;</p>
                                    <footer class="blockquote-footer">Roger Dow</footer>
                                </blockquote>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
            <section class="section section-lg pt-lg-0 mt--200">
                <h1 class="display-3 text-white text-center pb-md-5">Obsługiwane sektory</h1>
                <div class="container">
                    <div class="row justify-content-center">
                        <div class="col-lg-12">
                            <div class="row row-grid">
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Spory sądowe/mediacje</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_sad = true">więcej</base-button>
                                    </card>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Spory konsumentów z podmiotami rynku finansowego</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_konsument = true">więcej</base-button>
                                    </card>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Prawo karne</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_karne = true">więcej</base-button>
                                    </card>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
                        <!-- 2nd Hero Variation -->
            <section class="section section-lg pt-lg-0">
                <div class="container">
                    <div class="row justify-content-center">
                        <div class="col-lg-12">
                            <div class="row row-grid">
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Obsługa korporacyjna przedsiębiorstw</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_korp = true">więcej</base-button>
                                    </card>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Prawo gospodarcze</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_gosp = true">więcej</base-button>
                                    </card>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Prawo upadłościowe i restrukturyzacyjne</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_upad = true">więcej</base-button>
                                    </card>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
                        <!-- 3rd Hero Variation -->
            <section class="section section-lg pt-lg-0">
                <div class="container">
                    <div class="row justify-content-center">
                        <div class="col-lg-12">
                            <div class="row row-grid">
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Ochrona dóbr osobistych</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_dobr = true">więcej</base-button>
                                    </card>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Prawo pracy</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_pracy = true">więcej</base-button>
                                    </card>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <card class="border-0" hover shadow body-classes="py-5" >
                                        <icon name="ni ni-books" type="duo" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-duo text-uppercase">Prawo budowlane</h6>
                                        <div>
                                            <badge type="duo" rounded>marketing</badge>
                                            <badge type="duo" rounded>product</badge>
                                            <badge type="duo" rounded>launch</badge>
                                        </div>
                                        <base-button type="duo" size="sm" class="mt-md-4" @click="modals.modal_bud = true">więcej</base-button>
                                    </card>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- <section class="section section-lg">
                <div class="container">
                    <div class="row row-grid align-items-center">
                        <div class="col-md-6 order-md-2">
                            <h3>Jakieś informacje</h3>
                            <p class="lead">Prowadzimy sprway od A do Z...
                                Just make sure you enable them first via JavaScript.</p>
                            <p>Najpiękniejszej Siadł Najpiękniejszego Kazał szafie jezior Rzeczypospolitej. Lasy Bogu razu Białopiotrowiczem owad. Jedni kąty Białopiotrowiczowi Ślad wybor osoby domie Spór.</p>
                            <p>Najpiękniejszej Siadł Najpiękniejszego Kazał szafie jezior Rzeczypospolitej. Lasy Bogu razu Białopiotrowiczem owad. Jedni kąty Białopiotrowiczowi Ślad wybor osoby domie Spór.</p>
                        </div>
                        <div class="col-md-6 order-md-1">
                            <div class="pr-md-5">
                                <h3>Obsługiwane sektory</h3>
                                <p>Najpiękniejszej Siadł Najpiękniejszego Kazał szafie jezior Rzeczypospolitej. Lasy Bogu razu Białopiotrowiczem owad. Jedni kąty Białopiotrowiczowi Ślad wybor osoby domie Spór.</p>
                                <ul class="list-unstyled mt-5">
                                    <li class="py-2">
                                        <div class="d-flex align-items-center">
                                            <badge type="primary" circle class="mr-3" icon="ni ni-check-bold"></badge>
                                            <h6 class="mb-0">Infrastruktura i transport</h6>
                                        </div>
                                    </li>
                                    <li class="py-2">
                                        <div class="d-flex align-items-center">
                                            <badge type="primary" circle class="mr-3" icon="ni ni-check-bold"></badge>
                                            <h6 class="mb-0">Budownictwo</h6>
                                        </div>
                                    </li>
                                    <li class="py-2">
                                        <div class="d-flex align-items-center">
                                            <badge type="primary" circle class="mr-3" icon="ni ni-check-bold"></badge>
                                            <h6 class="mb-0">Nieruchomości</h6>
                                        </div>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </section> -->
            
            <modal :show.sync="modals.modal_karne">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo karne</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_karne = false">Close
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_sad">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo sad</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_sad = false">Close
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_konsument">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo konsument</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_konsument = false">Close
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_korp">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo korpo</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_korp = false">Close
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_gosp">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo gosp</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_gosp = false">Close
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_upad">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo upad</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_upad = false">Close
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_dobr">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo dobr</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_dobr = false">Close
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_pracy">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo pracy</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_pracy = false">Close
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_bud">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo bud</h6>
                <ul>
                    <li>kompleksowa reprezentacja w postępowaniach karnych przed sądami wszystkich instancji i organami ścigania w charakterze obrońcy, jak i pełnomocnika pokrzywdzonego</li>
                    <li>sporządzanie wszelkich pism na etapie postępowania przygotowawczego oraz na etapie postępowania sądowego</li>
                    <li>doradztwo prawne w sprawach karnych, karnych gospodarczych i o wykroczenia</li>
                    <li>doradztwo w zakresie compliance</li>
                </ul>

                <template slot="footer">
                    <base-button type="duo" class="ml-auto" @click="modals.modal_bud = false">Close
                    </base-button>
                </template>
            </modal>
        </div>
        
</template>
<script>
import Modal from "@/components/Modal.vue";
export default {
  components: {
    Modal
  },
  data() {
    return {
      modals: {
        modal_karne: false,
        modal_dobr: false,
        modal_bud: false,
        modal_pracy: false,
        modal_upad: false,
        modal_gosp: false,
        modal_korp: false,
        modal_konsument: false,
        modal_sad: false
      }
    };
  }
};
</script>
<style>
</style>