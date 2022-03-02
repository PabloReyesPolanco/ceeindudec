<template>
    <div>
        <div class="container">
            <h1> CEEIND </h1>
            <ColorModePicker />
        </div>
        <h2> Horrible intento de generar un menu</h2>

        <p> ¿En qué podemos ayudarte? Escribir texto... </p>
        <p> Si te interesa saber acerca de las opciones de intercambio que ofrece la universidad puedes enterarte en la sección intercambios </p>
    </div>
</template>


<script>
import ColorModePicker from "@/components/ColorModePicker.vue"
import MainHeader from  "@/components/MainHeader.vue"  

export default {
    components: {
        ColorModePicker
    },
    name: 'IndexPage'
    };

</script>

<style scoped>
  .container {
    text-align: center;
  }
</style>
