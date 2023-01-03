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

      <p class="text-3xl font-semibold">Visi & Misi Desa Mekarsari</p>
      <p class="text-3xl font-semibold">Visi</p>
      <p>Terciptanya penataan Desa yang maju, mandiri, teratur, bersih, indah, nyaman, aman dan sehat.
          Pelaksanaan pemerintahan yang baik, transparan dan peningkatan pelayanan kepada masyarakat dengan 
          lebih baik.</p>
      <br>
      <p class="text-3xl font-semibold">Misi</p>
      <p>1. Meningkatkan kesadaran masyarakat untuk hidup bersih, sehat dan produktif 
          melalui peningkatan kapasitas, kemitraan perencanaan pembangunan.</p>
      <p>2. Penataan Lingkungan pemukiman miskin.</p>
      <p>3. Peningkatan Sarana prasarana dan pelayanan pemukiman masyarakat miskin.</p>
      <p>4. Menyelenggarakan pemerintah yang bersih dan berwibawa.</p>
      <p>5. Mendorong kreatifitas serta pemberdayaan masyarakat bersama pemerintah desa dalam merencanakan
          dalam merencanakan pembangunan sosial, ekonomi dan lingkungan berdasarkan visi yang dibangun bersama.</p>
      <p>6. Meningkatkan persatuan dan kesatuan masyarakat dan umat beragama untuk menciptakan kedamaian, ketentraman,
        kenyamanan, serta kebersihan dalam kehidupan bermasyarakat berbangsa dan beragama.</p>
      <p>7. Mengutamakan pembangunan pada skala prioritas yang mendesak parah dalam jangka pendek, menengah maupun panjang.</p>
      <p>8. Meningkatkan pemberdayaan peran wanita dan generasi muda untuk mewujudkan cita-cita dalam pembangunan dan mewujudkan keadilan dan penegakan hukum bagi masyarakat.</p>

      <p class="text-3xl font-semibold my-4">Struktur Desa Mekarsari</p>
      <img src="@/assets/struktur-desa.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
