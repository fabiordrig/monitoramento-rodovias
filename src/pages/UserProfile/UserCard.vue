<template>
  <md-card class="md-card-profile">
    <div class="md-card-avatar">
      <img class="img" src="https://www.ab2l.org.br/wp-content/uploads/2019/03/inteligencia-artificial.jpg" />
    </div>

    <md-card-content>
      <h6 class="category text-gray"></h6>
      <h4 class="card-title">Insira uma imagem para realizarmos o processamento</h4>
      <p class="card-description">
      </p>
      <input type="file">
    </md-card-content>
      <md-button class="md-round md-success" @click="teste">Enviar</md-button>
  </md-card>
</template>
<script>
export default {
  data() {
    return {};
  },
  methods: {
    teste() {
      alert('oi');
    }
  }
};
</script>
<style></style>
