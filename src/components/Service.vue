<template>
  <section id="services">
    <h2>SERVICIOS</h2>
    <b-container>
      <b-row>
        <b-col class="service">
          <div class="iconHolder">
            <img
              src="../assets/icons/responsivity.png"
              alt="Many windows, represanting responsive design"
            />
          </div>
          <div class="services-text">
            <h4>{{ web }}</h4>
            <p>{{ responsive }}</p>
          </div>
        </b-col>
        <b-col class="service">
          <div class="iconHolder">
            <img src="../assets/icons/engines.png" alt="Engines Icon" />
          </div>
          <div class="services-text">
            <h4>{{ features }}</h4>
            <p>{{ feature }}</p>
          </div>
        </b-col>
        <b-col class="service">
          <div class="iconHolder">
            <img
              src="../assets/icons/design.png"
              alt="Many windows, represanting responsive design"
            />
          </div>
          <div class="services-text">
            <h4>{{ redesign }}</h4>
            <p>{{ design }}</p>
          </div>
        </b-col>
        <b-col class="service">
          <div class="iconHolder">
            <img src="../assets/icons/apis.png" alt="design software" />
          </div>
          <div class="services-text">
            <h4>{{ designsoft }}</h4>
            <p>{{ software }}</p>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {
  data: () => ({
    web: "Website Responsivo",
    redesign: "Rediseño de sitio web",
    features: "Nuevas características",
    designsoft: "Rediseño de software",
    software:
      "Utilización de nuevas bases de datos y incorporación a cliente / servidor.",
    responsive:
      "Creación de sitios web compatibles con diferentes dispositivos.",
    feature: "Agregar nuevas funciones a su sitio web.",
    design: "Reimaginando su sitio web y mejorando la experiencia del usuario.",
  }),
};
</script>

<style scoped>
/* Media */

#services {
  background-color: black;
  padding: 50px 20px;
}

#services h2 {
  text-align: center;
  color: #fff;
  margin-bottom: 50px;
  letter-spacing: 4px;
  font-size: 33px;
  font-weight: bold;
}

.service {
  display: flex;
  color: #999;
}

.iconHolder {
  height: 70px;
  width: 70px;
  margin-right: 32px;
  padding: 10px 15px;
  border: 1px solid #fff;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background-color: #d43f52;
}

.iconHolder img {
  height: 40px;
  width: 40px;
}

.service h4 {
  color: #fff;
  margin-bottom: 12px;
}

.service p {
  font-size: 14px;
}

.services-text {
  text-align: left;
}
</style>
