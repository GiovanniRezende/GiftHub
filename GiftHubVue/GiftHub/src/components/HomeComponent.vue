<script>
import CarouselOfertas from "@/components/contents/CarouselOfertas.vue";
export default {
  components: { CarouselOfertas },
};
</script>
<template>
  <CarouselOfertas />
  <div class="container cardcontainer">
    <div class="row">
      <div class="col">
        <div class="card cardLojas">
          <img
            src="@/imgs/16x9-Ratio-Image.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Loja-1</h5>
            <p class="card-text">Descrição da loja.</p>
            <a href="#" class="btn btn-primary">Acessar</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card cardLojas">
          <img
            src="@/imgs/16x9-Ratio-Image.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Loja-1</h5>
            <p class="card-text">Descrição da loja.</p>
            <a href="#" class="btn btn-primary">Acessar</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card cardLojas">
          <img
            src="@/imgs/16x9-Ratio-Image.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Loja-1</h5>
            <p class="card-text">Descrição da loja.</p>
            <a href="#" class="btn btn-primary">Acessar</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card cardLojas">
          <img
            src="@/imgs/16x9-Ratio-Image.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Loja-1</h5>
            <p class="card-text">Descrição da loja.</p>
            <a href="#" class="btn btn-primary">Acessar</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
