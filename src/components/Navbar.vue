<style scoped>
@font-face {
  font-family: "Quantum";
  src: url("../assets/font/Quantum.otf");
}

.name {
  text-decoration: none !important;
  color: black;
  font-family: "Quantum", sans-serif;
  font-size: 32px;
  letter-spacing: 3px;
  margin: 15px 15px;
}

.routers {
  text-decoration: none;
  color: #fff;
  padding: 10px 5px;
  font-weight: 600;
}

#nav-collapse {
  justify-content: flex-end;
}

</style>

<template>
  <div>
    <b-navbar toggleable="lg" variant="danger">
      <b-navbar-brand>
        <router-link class="name" to="/">
          {{ name }}
        </router-link>
      </b-navbar-brand>

      <b-navbar-toggle style="margin-right: 1rem;" target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <!-- About -->
          <b-nav-item>
            <router-link class="routers" to="/">
              SOBRE MI
            </router-link>
          </b-nav-item>
          <!-- Services -->
          <b-nav-item>
            <router-link class="routers" to="/services">
              SERVICIOS Y HABILIDADES
            </router-link>
          </b-nav-item>
          <!-- Projects -->
          <b-nav-item>
            <router-link class="routers" to="/projects">
              PROYECTOS Y CONTACTO
            </router-link>
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  data: () => ({
    name: "ROBLES"
  })
};
</script>
