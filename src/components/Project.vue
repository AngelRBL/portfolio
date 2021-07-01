<template>
  <section id="projects">
    <h2>PROYECTOS</h2>
    <b-container>
      <b-row>
        <b-col xs="12" sm="6" md="6" lg="6">
          <div class="project coding">
            <div class="awax">
              <h3>Coding Bootcamp</h3>
              <p>
                <a
                  href="https://coding-bootcamp-slider-nine.vercel.app/"
                  target="_blank"
                >
                  <img src="../assets/icons/link-2.png" alt="clip" />
                  - Demo
                </a>
                <a
                  href="https://github.com/AngelRBL/CodingBootcamp"
                  target="_blank"
                >
                  <img src="../assets/icons/github.svg" alt="git icon" />
                  Codigo
                </a>
              </p>
            </div>
          </div>
        </b-col>
        <b-col xs="12" sm="6" md="6" lg="6">
          <div class="project chat">
            <div class="awax">
              <h3>Chat illustrator</h3>
              <p>
                <a
                  href="https://chat-app-illustration-seven.vercel.app/"
                  target="_blank"
                >
                  <img src="../assets/icons/link-2.png" alt="clip" />
                  - Demo
                </a>
                <a
                  href="https://github.com/AngelRBL/Chat-app-illustration"
                  target="_blank"
                >
                  <img src="../assets/icons/github.svg" alt="git icon" />
                  Codigo
                </a>
              </p>
            </div>
          </div>
        </b-col>
        <b-col xs="12" sm="6" md="6" lg="6">
          <div class="project single">
            <div class="awax">
              <h3>Single price grid</h3>
              <p>
                <a
                  href="https://single-price-grid-component-master-vert-theta.vercel.app/"
                  target="_blank"
                >
                  <img src="../assets/icons/link-2.png" alt="clip" />
                  - Demo
                </a>
                <a
                  href="https://github.com/AngelRBL/single-price-grid-component-master"
                  target="_blank"
                >
                  <img src="../assets/icons/github.svg" alt="git icon" />
                  Codigo
                </a>
              </p>
            </div>
          </div>
        </b-col>
        <b-col xs="12" sm="6" md="6" lg="6">
          <div class="project launch">
            <div class="awax">
              <h3>Launch count down</h3>
              <p>
                <a
                  href="https://launchcountdowntimer.vercel.app/"
                  target="_blank"
                >
                  <img src="../assets/icons/link-2.png" alt="clip" />
                  - Demo
                </a>
                <a
                  href="https://github.com/AngelRBL/launchcountdowntimer"
                  target="_blank"
                >
                  <img src="../assets/icons/github.svg" alt="git icon" />
                  Codigo
                </a>
              </p>
            </div>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {};
</script>

<style>
#projects {
  background-color: black;
  padding: 20px 15px;
}

#projects h2 {
  color: #fff;
  text-align: center;
  margin-top: 15px;
  margin-bottom: 50px;
  letter-spacing: 4px;
  font-size: 33px;
  font-weight: bold;
}

.project {
  color: #fff;
  height: 280px;
  background-position: center;
  background-size: cover;
  transition: 0.4s;
  margin-top: 40px;
}

.project:hover {
  padding: 10px;
}

.coding {
  background-image: url("../assets/images/projects/Coding-Bootcamp.png");
}

.project div {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100%;
  opacity: 0;
  transition: 0.4s;
}

.project p {
  font-size: 14px;
}

.project a {
  display: inline-flex;
  align-items: center;
  margin-right: 10px;
  text-decoration: none;
  color: #fff;
  letter-spacing: 2px;
  position: relative;
  padding: 5px;
}

.project a::after {
  content: "";
  position: absolute;
  width: 0;
  height: 2px;
  bottom: -5px;
  left: 5px;
  background-color: #fff;
  transition: 0.3s;
}

.project img {
  height: 20px;
  margin-right: 3px;
}

.project a:hover::after {
  width: 90%;
}

.awax:hover {
  background-color: rgba(180, 51, 51, 0.8);
  opacity: 1;
}

.awax h3 {
  font-weight: bold;
  font-size: 30px;
  letter-spacing: 2px;
  margin-bottom: 20px;
}

.chat {
  background-image: url("../assets/images/projects/Chat-illustrator.png");
}

.single {
  background-image: url("../assets/images/projects/Single-price.png");
}

.launch {
  background-image: url("../assets/images/projects/Launch-countdown.png");
}
</style>
