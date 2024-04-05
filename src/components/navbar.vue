<script setup>
    
</script>

<template>

<nav class="navtop">
        <div>
            <h1><i class="bi bi-cpu">Ibnu Rizan</i> </h1>
            <v-btn text @click="scroll('home')"><i class="bi bi-house-door-fill"></i>Home</v-btn>
            <v-btn text @click="scroll('about')" ><i class="bi bi-file-person"></i>About</v-btn>
            <v-btn text @click="scroll('contact')"><i class="bi bi-telephone-fill"></i>Contact</v-btn>
            <v-btn text @click="scroll('portfolio')"><i class="bi bi-person-standing"></i>Portfolio</v-btn>
        </div>
  </nav>

</template>

<style >
  .navtop {
    background-color: #000000;
    height: 60px;
    width: 100%;
    border: 0;
    position: sticky;
}
.navtop div {
    display: flex;
    margin: 0 auto;
    width: 1000px;
    height: 100%;
}
.navtop div h1, .navtop div v-btn {
    display: inline-flex;
    align-items: center;
}
.navtop div h1 {
    flex: 1;
    font-size: 24px;
    padding: 0;
    margin: 0;
    color: #ecf0f6;
    font-weight: normal;
}
.navtop div v-btn {
    padding: 0 20px;
    text-decoration: none;
    color: #c5d2e5;
    font-weight: bold;
}
.navtop div v-btn i {
    padding: 2px 8px 0 0;
}
.navtop div v-btn:hover {
    color: #040553;
}
</style>