<template>
  <footer>
    <p class="copyright">Copyright &copy; {{ year }} - Angel Robles</p>
  </footer>
</template>

<script>
export default {
  data: () => ({
    date: null,
  }),
  computed: {
    year() {
      return new Date().getFullYear();
    },
  },
};
</script>

<style>
footer {
  text-align: center;
  background-color: #000;
  color: #999;
  padding: 50px 20px;
  font-family: 'Raleway', sans-serif;
}

.copyright {
  margin-top: 25px;
}

.copyright h4 {
  font-size: 16px;
}

</style>
