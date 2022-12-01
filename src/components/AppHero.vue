<script>
    export default {
        data() {
            return {
                description: "Next Generation Frontend Tooling",
                comfort:[
                    "Scaffolding",
                    "Aggiornabile",
                    "Veloce",
                    "Configurabile da file config",
                    "Espandibile grazie al plugin",
                    "Interfaccia Grafica"
                ]
            }
        }
    }
</script>

<template>
    <div>
        <h4>{{description}}</h4>

        <div class="py-4">
            <img src="/public/vite.svg" alt="">
        </div>

        <div class="fw-bold">Perchè è comodo Vite?</div>
        <div class="row gx-3 py-3">
            <div class="col-4 border p-3 bg-light" v-for="element in comfort"> {{element}}</div>
        </div>
    </div>
</template>