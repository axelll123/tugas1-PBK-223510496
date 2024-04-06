<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>
    Saat ini, saya tengah menempuh pendidikan sebagai mahasiswa di Universitas Islam Riau, yang berlokasi di Jalan Kaharuddin Nst, Pekanbaru. Sedang berada di semester 4, saya mengambil jurusan Teknik Informatika di institusi tersebut.
    Saya Berasal dari Kabupaten Pelalawan ,Kecamatan Pangkalan Kerinci Provinsi Riau
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    Sekarang, saya sedang menempuh pendidikan tinggi di salah satu perguruan tinggi swasta di Riau, yakni
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    .
    Sebelumnya, saya bersekolah di Sekolah Menengah Atas
    <a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/8BC3B4AC-368A-4D79-996D-E79A76028114" target="_blank" rel="noopener">SMAN 1 Pangkalan Kerinci</a>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi saya</template>
    Hobi saya adalah sumber kebahagiaan bagi saya. Melalui hobi ini, saya merasa hidup lebih berarti dan menyenangkan. Saya menemukan diri saya sendiri dan menikmati setiap momen yang saya habiskan untuk hobi saya. Itulah yang membuat hidup saya lebih berwarna dan menyenangkan.
    <ul>
      <li>Futsal</li>
      <li>Renang</li>
      <li>Jogging</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    Skill adalah kekuatan yang membuka peluang tak terbatas. Dengan keterampilan ini, saya dapat membentuk masa depan saya sendiri, skill yang saya kuasai yaitu:
    <ul>
      <li>Javascript</li>
      <li>MySql</li>
      <li>Java</li>
      <li>C++</li>
      <li>PHP</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
untuk menghubungi saya kalian dapat mengontak di bawah ini
   sosmed Instagram :<a href="https://www.instagram.com/adhanrazaq" target="_blank">adhanrazaq </a
    ><br />
    Email : adhanrazaq@gmail.com<br />
    No HP : +6282268660669
  </WelcomeItem>
</template>