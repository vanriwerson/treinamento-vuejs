<template>
  <div class="teste-if">
    <h2 v-if="podeVer">Agora você me Vue!</h2>
    <h2 v-else>Agora você não me Vue :(</h2>
  </div>
</template>

<script>
export default {
  name: 'TesteIf',
  data() {
    return {
      podeVer: true
    }
  }
}
</script>