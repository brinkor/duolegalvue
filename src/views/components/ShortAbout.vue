<template>
        <section class="section">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card shadow border-0">
                            <img v-lazy="'img/theme/law.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote duolegal_grey_bgcolor">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                     class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="duolegal_grey_fillcolor"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="duolegal_grey_fillcolor"></polygon>
                                </svg>
                                <blockquote class="blockquote text-white">
                                    <p class="mb-0">&bdquo;Jeśli jest w ogóle jakiś sekret sukcesu, leży on w umiejętności przyjęcia punktu widzenia innych i patrzeniu na rzeczy zarówno z pozycji rozmówcy, jak i własnej.&ldquo;</p>
                                    <footer class="blockquote-footer">Henry Ford</footer>
                                </blockquote>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <span>
                                <icon type="duo" name="ni ni-briefcase-24" class="mb-5" size="lg" shadow rounded></icon>
                            </span>
                            <ul class="list-unstyled">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <icon circle type="duo" name="ni ni-check-bold" class="mr-3" size="sm"></icon>
                                        <h6 class="mb-0">Dokładność</h6> <br/>
                                    </div>
                                    <p>Cechuje nas skrupulatność i precyzja w działaniu, a każdy krok podejmowany na rzecz klienta poprzedzony jest dogłębną analizą konkretnego przypadku.</p>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <icon circle type="duo" name="ni ni-check-bold" class="mr-3" size="sm"></icon>
                                        <h6 class="mb-0">Umiejętności</h6> <br/>
                                    </div>
                                    <p>Kancelarię tworzy zespół profesjonalistów – prawników, posiadających gruntowną wiedzę i doświadczenie, w szczególności z zakresu prawa cywilnego, w tym gospodarczego, handlowego oraz karnego.</p>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <icon circle type="duo" name="ni ni-check-bold" class="mr-3" size="sm"></icon>
                                        <h6 class="mb-0">Ofensywa</h6> <br/>
                                    </div>
                                    <p>Działania prowadzone na rzecz klientów kancelarii prowadzone są z największą  determinacją, z uwzględnieniem indywidualnych interesów klienta.</p>
                                </li>
                            </ul>
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
.duolegal_color{
    color: rgb(194, 60, 143);
}

.duolegal_bgcolor{
    background-color: rgb(194, 60, 143);
}

.duolegal_grey_bgcolor{
    background-color: #8898aa;
}

.duolegal_fillcolor{
    fill: rgb(194, 60, 143);
} 
.duolegal_grey_fillcolor{
    fill: #8898aa;
} 
</style>