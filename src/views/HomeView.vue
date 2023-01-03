<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold mt-4">VISI</p>
      <p>Desa Cibinong memiliki visi,<strong>“ Menuju Desa Cibinong Lebih Maju dan Berpotensi “</strong> diintegrasikan dengan keinginan bersama masyarakat desa 
        dimana proses penyusunannya dilakukan secara partisipatif mulai dari tingkat Dusun/RW sampai 
        tingkat Desa</p>

      <p class="text-lg font-semibold mt-4">MISI</p>
      <ul>
        <li>1. Menyelenggarakan Pemerintahan Desa yang Transparan dan Berkwalitas dengan Pelayanan yang 
          maximal kepada Warga Masyarakat</li>
        <li>2.	Menciptakan Desa Cibinong yang lebih Nyaman dengan peningkatan Transfortasi melalui Pembangunan
           Infrastruktur yang berkesinambungan </li>
        <li>3.	Menghadirkan keamanan dan ketertiban Masyarakat dengan melibatkan seluruh warga masyarakat
           dan instansi terkait</li>
        <li>4.	Bekerjasama dengan seluruh Stekholder berkompeten dalam Permberdayaan Perekonomian dan
           Kesehatan Masyarakat</li>
        <li>5.	Menjalin Kerukunan antar umat beragama dalam menciptakan Desa Cibinong yang berkeberadaban
           dan berketuhanan</li>
        <li>6.	Mendukung dan menjalankan Program Panca Karsa sebagai Visi dan Misi Bupati Bogor</li>
      </ul>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desa1.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
