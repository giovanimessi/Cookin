<template>

    {{ categoria.nome }}
    {{ categoria.imagem }}
  
</template>

<script lang="ts">
import { PropType } from 'vue';
import type ICategoria from '../Interfaces/ICategoria';

export default {
    props:{
        categoria: {type: Object as PropType<ICategoria>, required: true }
    }

}
</script>

<style>

</style>