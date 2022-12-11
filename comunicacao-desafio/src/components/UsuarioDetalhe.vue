<template>
    <div class="usuario-detalhe">
        <h2>Nome: {{ this.nome }}</h2>
        <h2>Id: {{ this.id }}</h2>     
    </div>
</template>

<script>
export default {
      props : {
        id: Number,
        nome: String
      }
}
</script>
<style>
    .usuario-detalhe {
        flex: 1;
        border: 1px solid #CCC;
    }
</style>
