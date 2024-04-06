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
    <template #heading>About Me</template>
    Saya adalah mahasiswa Teknik Informatika Universitas Islam Riau, umur saya 19 tahun dan saya lahir di Pekanbaru pada tanggal 21 Juli 2004
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>

    Bicara tentang hobi, sebenarnya hobi saya banyak cuma tergantung mood saya maunya apa. Tapi yang paling saya sukai yaitu rebahan.<code>README.md</code>.
  </WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Keahlian</template>

  Coming Soon
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact Me</template>

   Instagram: inolafe_
  </WelcomeItem>
</template>
