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
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="fa fa-handshake-o" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">Spory sądowe/mediacje</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>reprezentacja</badge>
                                                <badge type="duo" rounded>doradztwo</badge>
                                                <badge type="duo" rounded>negocjacje</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_sad = true">więcej</base-button>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="fa fa-money" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">spory frankowe</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>analiza</badge>
                                                <badge type="duo" rounded>wsparcie</badge>
                                                <badge type="duo" rounded>reprezentacja</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_konsument = true">więcej</base-button>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="fa fa-exclamation-triangle" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">Prawo karne</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>reprezentacja</badge>
                                                <badge type="duo" rounded>doradztwo</badge>
                                                <badge type="duo" rounded>natychmiastowe działanie</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_karne = true">więcej</base-button>
                                        </div>
                                    </div>
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
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="fa fa-building" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">Obsługa korporacyjna przedsiębiorstw</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>rejestracja</badge>
                                                <badge type="duo" rounded>dokumentacja wewnętrzna</badge>
                                                <badge type="duo" rounded>reprezentacja</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_korp = true">więcej</base-button>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="fa fa-line-chart" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">Prawo gospodarcze</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>reprezentacja</badge>
                                                <badge type="duo" rounded>umowy</badge>
                                                <badge type="duo" rounded>opinie prawne</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_gosp = true">więcej</base-button>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="ni ni-books" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">Prawo upadłościowe i restrukturyzacyjne</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>wnioski</badge>
                                                <badge type="duo" rounded>zgłoszenia</badge>
                                                <badge type="duo" rounded>reprezentacja</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_upad = true">więcej</base-button>
                                        </div>
                                    </div>
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
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="fa fa-male" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">Ochrona dóbr osobistych</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>doradztwo</badge>
                                                <badge type="duo" rounded>reprezentacja</badge>
                                                <badge type="duo" rounded>analiza</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_dobr = true">więcej</base-button>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="fa fa-file-text" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">Prawo pracy</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>reprezentacja</badge>
                                                <badge type="duo" rounded>umowy</badge>
                                                <badge type="duo" rounded>doradztwo</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_pracy = true">więcej</base-button>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-lg-4 text-center">
                                    <div class="card border-0 whole-block-height card-lift--hover shadow">
                                        <div class="card-body py-5 d-flex flex-column justify-content-center">
                                            <icon name="fa fa-university" type="duo" size="lg" rounded class="mb-4 align-self-center">
                                            </icon>
                                            <h6 class="text-uppercase">Prawo budowlane</h6>
                                            <div class="mb-4">
                                                <badge type="duo" rounded>doradztwo</badge>
                                                <badge type="duo" rounded>umowy</badge>
                                                <badge type="duo" rounded>rozliczenia</badge>
                                            </div>
                                            <base-button type="Secoundary" size="sm" class="duo_btn mt-auto" @click="modals.modal_bud = true">więcej</base-button>
                                        </div>
                                    </div>
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
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_karne = false">Zamknij
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_sad">
                <h6 slot="header" class="modal-title" id="modal-title-default">Spory sądowe/mediacje</h6>
                <ul>
                    <li>reprezentacja w postępowaniach sądowych przed sądami wszystkich instancji oraz w postępowaniach przed sądami arbitrażowymi</li>
                    <li>kompleksowe doradztwo procesowe</li>
                    <li>udział w przedsądowych negocjacjach i mediacjach</li>
                    <li>reprezentacja w postępowaniach egzekucyjnych</li>
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_sad = false">Zamknij
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_konsument">
                <h6 slot="header" class="modal-title" id="modal-title-default">Tzw. "spory frankowe"</h6>
                <ul>
                    <li>reprezentacja w postępowaniach sądowych o roszczenia wynikające z umów kredytów powiązanych z kursem waluty obcej, w tym w szczególności tzw. kredyty frankowe</li>
                    <li>analiza dokumentacji kredytowej</li>
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_konsument = false">Zamknij
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_korp">
                <h6 slot="header" class="modal-title" id="modal-title-default">Obsługa korporacyjna przedsiębiorstw</h6>
                <ul>
                    <li>reprezentacja przedsiębiorców przed sądami rejestrowymi a także w postępowaniach administracyjnych przed organami administracji, a w tym wsparcie w wyborze formy prowadzonej działalności</li>
                    <li>opracowywanie umów, statutów oraz regulacji wewnętrznych spółek</li>
                    <li>pełna obsługa start-upów, w tym bieżące doradztwo przy rozpoczynaniu działalności, opiniowanie projektów biznesowych</li>
                    <li>opracowywanie, weryfikacja i dostosowywanie dokumentacji wewnętrznej w sprawach korporacyjnych i regulacyjnych</li>
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_korp = false">Zamknij
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_gosp">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo gospodarcze</h6>
                <ul>
                    <li>kompleksowa reprezentacja w sprawach gospodarczych przed sądami wszystkich instancji</li>
                    <li>opracowywanie wszelkiego rodzaju umów w obrocie gospodarczym i sporządzanie opinii prawnych</li>
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_gosp = false">Zamknij
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_upad">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo upadłościowe i restrukturyzacyjne</h6>
                <ul>
                    <li>przygotowywanie wniosków o otwarcie postępowania restrukturyzacyjnego</li>
                    <li>przygotowywanie propozycji układowych i wstępnych planów restrukturyzacyjnych</li>
                    <li>reprezentacja dłużników oraz wierzycieli w toku postępowania restrukturyzacyjnego</li>
                    <li>obsługa dłużnika ubiegającego się o otwarcie postępowania upadłościowego, w tym również upadłość konsumencką</li>
                    <li>obsługa upadłego w postępowaniu upadłościowym</li>
                    <li>obsługa wierzyciela składającego wniosek o ogłoszenie upadłości dłużnika</li>
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_upad = false">Zamknij
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_dobr">
                <h6 slot="header" class="modal-title" id="modal-title-default">Ochrona dóbr osobistych</h6>
                <ul>
                    <li>kompleksowa reprezentacja przed sądami wszystkich instancji</li>
                    <li>doradztwo prawne w zakresie dóbr osobistych</li>
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_dobr = false">Zamknij
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_pracy">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo pracy</h6>
                <ul>
                    <li>reprezentacja w toku całego postępowania sądowego przed sądami wszystkich instancji w sporach dotyczących stosunku pracy</li>
                    <li>przygotowywanie umów o pracę, przygotowywanie umów o zakazie konkurencji, umów o zachowaniu poufności</li>
                    <li>przygotowywanie kontraktów menadżerskich i innych umów cywilnoprawnych</li>
                    <li>przygotowywanie regulaminów pracy, wynagrodzenia, zakładowego funduszu świadczeń socjalnych; - przygotowywanie dokumentacji związanej ze zmianą lub rozwiązaniem stosunku pracy</li>
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_pracy = false">Zamknij
                    </base-button>
                </template>
            </modal>
            <modal :show.sync="modals.modal_bud">
                <h6 slot="header" class="modal-title" id="modal-title-default">Prawo budowlane</h6>
                <ul>
                    <li>przygotowywanie umów konsorcjalnych</li>
                    <li>przygotowywanie umów z podwykonawcami</li>
                    <li>przygotowywanie projektów zabezpieczeń należytego wykonania umów</li>
                    <li>bieżące doradztwo w toku realizowania umów</li>
                    <li>przygotowywanie i analiza roszczeń terminowych i finansowych</li>
                    <li>rozliczenia z zamawiającym, partnerami konsorcjum oraz podwykonawcami</li>
                </ul>

                <template slot="footer">
                    <base-button type="Secoundary" class="duo_btn ml-auto" @click="modals.modal_bud = false">Zamknij
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
.whole-block-height{
    min-height: 100%;
}
</style>