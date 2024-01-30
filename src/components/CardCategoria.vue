<template>

    {{ categoria.nome }}
  
</template>

<script lang="ts">

export default {
    props:{
        categoria: {type: Object, required: true }
    }

}
</script>

<style>

</style>