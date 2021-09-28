<template>
  <div class="contador">
    <h1>Contador: {{ contador }}</h1>
    <div>
      <input @click="mudarContador(-1)" type="button" value="-" />
      <input @click="mudarContador(+1)" type="button" value="+" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Contador",
  data() {
    return {
      contador: 0,
    };
  },
  methods: {
    mudarContador(qtde) {
      this.contador = this.contador + qtde;
    },
  },
};
</script>