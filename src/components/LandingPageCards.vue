<template>
  <section id="LandingPageCards"></section>
  <div class="container-fluid">
    <h1 class="display-4 text-center">En Argfunding nos ayudamos entre todos</h1>
    <div class="card-container">
      <div class="card">
        <div class="card-icon">
          <font-awesome-icon icon="rocket" />
        </div>
        <div class="card-title">Crece</div>
        <div class="card-text">
          <p>Tienes una idea y necesitas apoyo para llevarla a cabo? 
            En Argfunding te ayudamos a cumplir tus sueños. Fija un objetivo monetario y ofrece recompensas a cambio de donaciones</p>
        
        </div>
      </div>
      
      <div class="card">
        <div class="card-icon">
          <font-awesome-icon icon="magnifying-glass" />
        </div>
        <div class="card-title">Explora</div>
        <div class="card-text">
          <p>Descubre proyectos creativos hechos por gente innovadora como tú. Tienes cientos de categorias para explorar!</p>
        </div>
      </div>

      <div class="card">
        <div class="card-icon">
          <font-awesome-icon icon="hand-holding-heart" />
        </div>
        <div class="card-title">Apoya</div>
        <div class="card-text">
          <p>Un proyecto llamó tu atencion?
             Ayuda a gente a cumplir sus objetivos y obten un bien material a cambio. Todos salen ganando!</p>
        </div>
      </div>
      

    </div>
  </div>
</template>

<style scoped>
.container-fluid {
  display: flex;
  flex-direction: column;
  margin-top: 6vh;
  justify-content: center;
}

.container-fluid .card-container {
  display: flex;
  justify-content: space-around;
  margin-top: 5vh;
  flex-wrap: wrap;
}

.card-container .card {
  display: flex;
  flex-direction: column;
  text-align: center;
  align-items: center;
  justify-content: flex-start;
  font-size: 2rem;
  height: 55vh;
  width: 45vh;
  border:none;
}

.card-container .card .card-icon {
  color: #009FE3;
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: center;
  margin-top: 5vh;
  height: 5rem;
  width: 5rem;
  text-align: center;
  font-size: 5rem;
}

.card-container .card .card-title {
  display: flex;
  justify-content: center;
  margin-left: 2vh;
  margin-right: 2vh;
  margin-top: 2vh;
  font-size: 2rem;
  font-weight: 600;
}

.card-container .card .card-text {
  text-align:center;
  margin-top: 2vh;
  font-size: 1.3rem;
  font-weight: 300;
}
</style>
