<template>
    <section class="section-hero section-shaped my-0">
        <div class="shape shape-style-1 shape-primary">
            <span class="span-150"></span>
            <span class="span-50"></span>
            <span class="span-50"></span>
            <span class="span-75"></span>
            <span class="span-100"></span>
            <span class="span-75"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
        </div>
        <div class="container shape-container d-flex align-items-center">
            <div class="col px-0">
                <div class="row justify-content-center align-items-center">
                    <img src="img/brand/duolegal_new_pink.svg" style="width: 30em;" class="img-fluid">
                </div>
                <div class="row justify-content-center align-items-center">
                    <p class="bigger_white_text">
                        <span id="slideText1" class="duolegal_color">d</span>okładność<br/>
                        <span id="slideText2" class="duolegal_color">u</span>miejętności<br/>
                        <span id="slideText3" class="duolegal_color">o</span>fensywa
                    </p>
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
    font-weight: bold;
    text-align: left;
}
.bigger_white_text{
    color: white;
    font-size: 150%;
    font-weight: 400;
    display: inline-block; 
    text-align: left;
}

#slideText1 {
  animation-duration: 1s;
  animation-name: slidein1;
}
#slideText2 {
  animation-duration: 1.5s;
  animation-name: slidein2;
}
#slideText3 {
  animation-duration: 2s;
  animation-name: slidein3;
}

@keyframes slidein1 {
  from {
    margin-left: 100%;
    width: 300%;
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
}

@keyframes slidein2 {
  from {
    margin-left: 150%;
    width: 300%;
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
}
@keyframes slidein3 {
  from {
    margin-left: 200%;
    width: 300%;
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
}
</style>
