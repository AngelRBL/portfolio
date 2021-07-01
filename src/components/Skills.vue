<template>
  <section id="skills">
    <h2>HABILIDADES</h2>
    <b-container>
      <b-row>
        <b-col xs="12" sm="6" md="6" lg="3">
          <img src="../assets/icons/html.svg" alt="logo html" />
          <h5>HTML</h5>
          <h6>avanzado</h6>
        </b-col>
        <b-col xs="12" sm="6" md="6" lg="3">
          <img src="../assets/icons/css.svg" alt="logo css" />
          <h5>CSS</h5>
          <h6>Intermedio - avanzado</h6>
        </b-col>
        <b-col xs="12" sm="6" md="6" lg="3">
          <img src="../assets/icons/js.svg" alt="logo de javascript" />
          <h5>JavaScript</h5>
          <h6>Intermedio</h6>
        </b-col>
        <b-col xs="12" sm="6" md="6" lg="3">
          <img src="../assets/icons/react.svg" alt="logo react" />
          <h5>React</h5>
          <h6>Intermedio</h6>
        </b-col>
        <b-col xs="12" sm="6" md="6" lg="3">
          <img
            src="../assets/icons/1200px-Vue.js_Logo_2.svg.png"
            alt="logo vue"
          />
          <h5>Vue</h5>
          <h6>Intermedio</h6>
        </b-col>
        <b-col xs="12" sm="6" md="6" lg="3">
          <img src="../assets/icons/svelte.svg" alt="logo svelte" />
          <h5>Svelte</h5>
          <h6>Basico</h6>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {};
</script>

<style>
/* SKILLS */
#skills {
  background-color: #1a1a1a;
  padding: 50px 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

#skills h2 {
  text-align: center;
  color: #fff;
  margin-bottom: 50px;
  letter-spacing: 4px;
  font-size: 33px;
  font-weight: bold;
}

#skills img {
  height: 120px;
  margin-bottom: 10px;
  margin-top: 15px;
}

#skills h5 {
  font-weight: bold;
  color: white;
  font-size: 20px;
  margin-bottom: 10px;
}

#skills h6 {
  font-size: 12px;
  color: #999;
}
</style>
