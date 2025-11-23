<script lang="ts">
import type ICategoria from '@/interfaces/ICategoria';
import type { PropType } from 'vue';

export default {
    props: {
        categoria: { type: Object as PropType<ICategoria>, required: true }
    }
}
</script>
<template>
    <article class="categoria">
        <header class="categoria__cabecalho">
            <img src="../assets/imagens/logo.svg" alt="" class="categoria__imagem">
        </header>
    </article>
</template>