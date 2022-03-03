<template>
    <div class = "center">
        <div class = "row"> 
            <div class = "left-column"> <h1> CEEIND </h1> </div>
            <div class= "right-column"> <ColorModePicker /></div>
        </div>
        <br>
        
        <h2> Horrible intento de generar un menu</h2>

        <p> ¿En qué podemos ayudarte? Escribir texto... </p>
        <p> Si te interesa saber acerca de las opciones de intercambio que ofrece la universidad puedes enterarte en la sección intercambios </p>
    <div class = "footer"> 
        <p> © Diseñado por Pablo Reyes, todos los derechos reservados. </p>
    </div>
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
    text-align: right;
    }
.column {
    float: left;
    width: 50%;
    }
    
.center {
    margin: auto;
    width: 90%;
    border: 3px solid rgb(31, 31, 121);
    padding: 10px;
    text-align:center
}
/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

.left-column {
    float:left ;
    text-align: left;
}

.right-column {
    float: right;
    text-align: right;
}
.footer {
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    text-align: center;
}
</style>
