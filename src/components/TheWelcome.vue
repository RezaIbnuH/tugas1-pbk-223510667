<script setup>
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
    <template #heading>intermezo</template>

    my name's gustavo.panggilan saya
    <a href="https://vuejs.org/" target="_blank" rel="noopener">adunc</a>
    anjay.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>hobi</template>

    hobi saya adalah
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">gowes 70 km sehari</a>. The
    kalo mau gowes sama saya,
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">cpm gan</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">dm wa</a>. If
    kalo butuh bantuan restore sepeda
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">cpm lagi gan</a> 


    <br />

    More instructions are available in <code>README.md</code>.
  </WelcomeItem>
  <hr>
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>prestasi</template>

    ketika melihat ke belakang, saya merasa hidup saya penuh penyesalan.saya sering kali berpikir tentang kesempatan yg terlewat,keputusan yg salah,dan kata-kata yg seharusnya tidak saya ucapkan.
    rasanaya seperti banyak hal yg bisa saya ubah jika saya punya kesempatan untuk berubah.
    (sebenarnya saya ga ingat punya prestasi),mungkin ga ada hehe.
  </WelcomeItem>
  <hr>
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>cita-cita</template>

    Berikut ini adalah beberapa  daftar cita-cita yang saya miliki: <br>

1. Menjadi dokter dan menyelamatkan nyawa. <br>
2. Menjadi ilmuwan terkemuka dan membuat penemuan-penemuan penting.<br>
3. Menjadi pengusaha sukses dan menciptakan perusahaan yang inovatif.<br>
4. Menjadi guru dan memberikan pengaruh positif pada generasi muda.<br>
5. Menjadi seniman terkenal dan menginspirasi orang dengan karya seni mereka.<br>
6. Menjadi atlet profesional dan meraih prestasi di bidang olahraga.<br>
7. Menjadi aktivis sosial dan berjuang untuk keadilan dan perubahan sosial.<br>
8. Menjadi penulis terkenal dan menyampaikan pesan-pesan yang memotivasi dan menginspirasi.<br>
9. Menjadi ahli dalam bidang lingkungan dan berkontribusi dalam pelestarian alam.<br>
10. Menjadi pemimpin politik dan membawa perubahan positif bagi masyarakat.<br>
11. menjadi kapal laut agar dapat menjadi raja bajak  laut.
  </WelcomeItem>
  <hr>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>contact person</template>

    +62 821 8090 7959
    <hr>
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>
</template>
