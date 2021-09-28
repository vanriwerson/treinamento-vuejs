<template>
  <div class="teste-evento">
    <h2>Teste Evento</h2>
    <p>{{ mensagem }}</p>
    <button @click="deixarMaiuscula">Texto em maiúsculo</button>
  </div>
</template>

<script>
export default {
  name: 'TesteEvento',
  data() {
    return {
      mensagem: 'O rato roeu a roupa do rei de Roma'
    }
  },
  methods: {
    deixarMaiuscula() {
      this.mensagem = this.mensagem.toUpperCase();
    }
  }
}
</script>