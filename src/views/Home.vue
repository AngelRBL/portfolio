<template>
  <div class="home">
    <section class="first-home">
      <div class="img-home">
        <h1 class="animate-up">{{ name }}</h1>
        <p class="animate-up">{{ job }}</p>
        <span class="animate-up">
          <a
            href="http://github.com/AngelRBL"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="../assets/icons/PngItem_1280311.png" alt="github" />
          </a>
          <a
            href="https://api.whatsapp.com/send?1=pt_BR&phone=+526142509616&text="
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="../assets/icons/whatsapp.svg" alt="whatsapp" />
          </a>
          <a
            href="https://www.linkedin.com/in/%C3%A1ngel-robles-0b309b80/"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="../assets/icons/linkedin.svg" alt="whatsapp" />
          </a>
        </span>
      </div>
    </section>
    <section class="about">
      <h2>{{ about }}</h2>
      <div class="container">
        <div class="info">
          <h3>¡Hola Mundo!</h3>
          <p>
            Mi nombre es <strong>{{ name }}</strong> y soy un desarrollador web.
            <br />
            {{ info }}
            <br />
            {{ pasion }}
          </p>
          <a class="pulse" href="https://my.indeed.com/p/ngelrobertor-saijb5e" target="_blank">
            VER CURRICULUM
          </a>
        </div>
        <div class="image">
          <img
            src="../assets/images/web-dev.png"
            alt="dWeb developer working"
          />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home",
  data: () => ({
    name: "Angel Robles",
    job: "Desarrollador Web",
    about: "SOBRE MI",
    info:
      "Trabajo en el área de tecnología desde 2020, realizando proyectos personales y trabajando como freelancer.",
    pasion:
      "Mis pasiones son de aprendizaje, cómics y tecnología. Siempre trato de estar atento a las nuevas tendencias del mercado y mi objetivo es siempre llevar las mejores y mas innovadoras soluciones para mis clientes, con código limpio y que agrega valor a su producto en cada etapa completada.",
  }),
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,700;1,400&display=swap");

.first-home {
  height: calc(100vh - 84px);
  max-width: 100vw;
  padding: 0;
  text-align: center;

  background-image: url("../assets/images/banner_bg2.png");
  background-position-x: center;
  background-position-y: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.img-home {
  height: 100%;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.6);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: #fff;
  padding: 10px;
}

h1 {
  text-align: center;
}

.first-home h1 {
  color: #d43f52;
  font-size: 60px;
  animation-delay: 0.4s;
  line-height: 55px;
  font-weight: 600;
}

.first-home p {
  margin-top: 15px;
  font-size: 30px;
  animation-delay: 0.7s;
}

p {
  display: block;
  margin-block-start: 1em;
  margin-inline-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
  font-weight: 400;
}

.animate-up {
  animation-name: up;
  animation-duration: 0.5s;
  animation-fill-mode: backwards;
  animation-timing-function: ease-out;
}

.animate-up a {
  display: inline-block;
  padding: 15px 5px;
}

img {
  width: 30px;
  height: 30px;
}

.about {
  background-color: #1a1a1a;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: center;
  flex-wrap: wrap;
  color: #ddd;
  margin: auto;
}

.about .container {
  display: grid;
  align-items: center;
  justify-content: center;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
}

h2 {
  text-transform: uppercase;
  text-align: center;
  margin-top: 3rem;
  margin-bottom: 3.2rem;
  letter-spacing: 4px;
  font-size: 33px;
  font-weight: 600;
}

h3 {
  color: #d43f52;
  font-size: 31px;
  letter-spacing: 2px;
  margin-bottom: 20px;
  font-weight: bold;
}

strong {
  color: #d43f52;
}

.info p {
  line-height: 22px;
}

.info {
  text-align: start;
}

.info a {
  display: inline-block;
  text-decoration: none;
  font-weight: bold;
  color: #d43f52;
  border: 2px solid #d43f52;

  margin: auto;
  margin-top: 30px;
  letter-spacing: 2px;
  font-size: 19px;
  padding: 15px 20px;
  transition: 0.2s;
  max-height: 80vh;
  text-align: center;
  cursor: pointer;
}

.pulse:hover,
.pulse:focus {
  -webkit-animation: pulse 1s;
          animation: pulse 1s;
  box-shadow: 0 0 0 2em rgba(255, 255, 255, 0);
}

@-webkit-keyframes pulse {
  0% {
    box-shadow: 0 0 0 0 var(--hover);
  }
}

@keyframes pulse {
  0% {
    box-shadow: 0 0 0 0 var(--hover);
  }
}

.pulse {
  --hover: #D43F52;
}

.image img {
  width: 100%;
  min-width: 320px;
  max-width: 700px;
  height: auto;
}
</style>
