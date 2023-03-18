<script>
import NavComp from './NavComp.vue'

export default {
  name: 'App',
  components: {
    NavComp
  }
}
</script>

<template>
  <div class="container-fluid-main">
    <NavComp/>
    <div class="main-text">
      <p class="hidden-mobile">Alimentemos grandes ideas</p>
    </div>
    <div class="light-bulb">
      <a href="#LandingPageCards"><font-awesome-icon icon="fa-solid fa-lightbulb" /></a>
    </div>
  </div>
</template>

<style scoped>
.container-fluid-main {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-image: url('https://images.unsplash.com/photo-1521583871906-b3177c649805?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2019&q=80');
  background-size: cover;
  min-height: 90vh;
  width: auto;
  margin-left: 0;
  margin-right: 0;
  padding: 0px;
}

.container-fluid-main .main-text {
  display: flex;
  justify-content: center;
  margin-left: 25vh;
  margin-right: 25vh;
  width: 18.5rem;
  text-align: center;
  line-height: 1.1;
  font-size: 3.75rem;
  font-weight: 600;
  color: #F2F7A1;

  -webkit-animation: fadein 2s; /* Safari, Chrome and Opera > 12.1 */
  -moz-animation: fadein 2s; /* Firefox < 16 */
  -ms-animation: fadein 2s; /* Internet Explorer */
  -o-animation: fadein 2s; /* Opera < 12.1 */
  animation: fadein 2s;
}

@keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Firefox < 16 */
@-moz-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Safari, Chrome and Opera > 12.1 */
@-webkit-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Internet Explorer */
@-ms-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Opera < 12.1 */
@-o-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

@media (max-width: 767px) {
  .hidden-mobile {
    display: none;
  }
}

.container-fluid-main .light-bulb {
  display: flex;
  width: 9rem;
  height: 9rem;
  justify-content: center;
  align-items: center;
  margin-top: 0px;
  text-align: center;
  font-size: 6rem;
  color: #009FE3;
  background-color: aliceblue;
  border-radius: 100%;
  box-shadow: 0px 15px 15px 0px rgba(0, 0, 0, 0.5);

  -webkit-animation: fadein 4s; /* Safari, Chrome and Opera > 12.1 */
  -moz-animation: fadein 4s; /* Firefox < 16 */
  -ms-animation: fadein 4s; /* Internet Explorer */
  -o-animation: fadein 4s; /* Opera < 12.1 */
  animation: fadein 4s;
}

.light-bulb a:link{
  color:#2c74f6;
  
}
.light-bulb a:hover{

  color: #009FE3;
}

</style>
