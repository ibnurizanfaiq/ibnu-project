<script setup>
  import navbar from './components/navbar.vue';
</script>

<template>
  <div>
    <navbar />
  </div>
  <div style="position: relative" class="main">
      <h1>Hello,</h1>
      <h1>I'M Ibnu Rizan Faiq</h1>
      <span>AI and IOT</span><br />
      <h4>I Am a Student in Universitas Islam Riau</h4><br>
      <h4>Biodata</h4>
      <p>
        Nama : Ibnu Rizan Faiq<br>
        Tempat Tanggal Lahir : Dayo 09-12-2003<br>
        Status : Mahasiswa
      </p>
    <br />
    <h4>Skill & Pengalaman</h4>
    <div >
      Konfigurasi Mikrotik
      <br>Analisis Kerusakan Komputer
      <br>Instalasi OS
      <br>Pemasangan LAN<br>
    </div>
  </div>
</template>

<style >
body{
  background-image: url('web.jpeg');
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
.main{
  color: rgb(211, 208, 13);
  text-transform: uppercases;
}
</style>
