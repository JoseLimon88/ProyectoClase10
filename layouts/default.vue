<template>
    <div>
        <header class="DHeader">
            Materia: Aplicaciones y Videojuegos
        </header>
        
        <div class="VarNav">
            <NuxtLink to="/">Home</NuxtLink>
            <b> | </b>
            <NuxtLink to="contacto">Contacto</NuxtLink>
        </div>
        <main class="DMain">
            <slot>

            </slot>
        </main>
        <footer class="DFooter">
            Derechos Reservados 2024 <br>
            Jose Luis Limon | UNARE
        </footer>
    </div>
</template>

<style>
.DHeader{
    background-color: dimgray;
    text-align: center;
    padding-left: -1%;
    margin-top: -1%;
    padding-bottom: 1%;
    padding-top: 1%;
    color: white;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: xx-large;
}
.DFooter{
    background-color: dimgray;
    text-align: center;
    color: white;
    font-size: 80%;
    padding: 1%;
}
.DMain{
    background-color: white;
    height: 550px;
    padding-top: 10px;
}.VarNav{
    text-align: right;
}

</style>