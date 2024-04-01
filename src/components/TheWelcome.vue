<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Pendidikan</template>

    Saat ini saya kuliah di salah satu Kampus swasta di Riau yaitu
    <a href="https://uir.ac.id/" target="_blank" rel="noopener"
      >Universitas Islam Riau</a
    >
    .Sebelumnya saya bersekolah di SMA NEGRI
    <a href="https://smanegeri3tapung.sch.id/" target="_blank" rel="noopener"
      >SMAN 3 TAPUNG</a
    >
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tempat, Tanggal Lahir</template>

    Saya Lahir di Provinsi
    <a
      href="https://www.bpkp.go.id/sumut/konten/236/"
      target="_blank"
      rel="noopener"
      >Sumatera Utara</a
    >yaitu
    <a
      href="https://sawitseberang.langkatkab.go.id/sekilas/"
      target="_blank"
      rel="noopener"
      >kota Medan</a
    >
    .pada tanggal 15 november 2004
    <a
      href="https://github.com/johnsoncodehk/volar"
      target="_blank"
      rel="noopener"
    ></a>
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a>

    <a
      href="https://on.cypress.io/component"
      target="_blank"
      rel="noopener"
    ></a>

    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>

    Prodi atau Jurusan Kuliah Saya mengambil Program didik Teknik Informatika
    atau biasa disebut IT , sekarang saya berada di semester 4 dan berada di
    kelas paling wibu yaitu
    <a
      href="https://www.instagram.com/b1universe_?igsh=bHgzd2gwN2s1OHUw"
      target="_blank"
      rel="noopener"
      >b1universe_</a
    >
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a
      href="https://github.com/vuejs/devtools"
      target="_blank"
      rel="noopener"
    ></a>
    <a
      href="https://github.com/vuejs/awesome-vue"
      target="_blank"
      rel="noopener"
    ></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya Adalah sebagai berikut :
    <br />

    <a
      href="https://id.wikipedia.org/wiki/Bola_voli"
      target="_blank"
      rel="noopener"
      >1. volly</a
    >
    <br />
    <a
      href="https://kumparan.com/pengertian-dan-istilah/pengertian-permainan-bulu-tangkis-dan-sejarahnya-di-indonesia-215E4wCJURX"
      target="_blank"
      rel="noopener"
      >2. bola raket</a
    ><br />
    <a
      href="https://biz.kompas.com/read/2021/02/05/161000028/agar-ngegame-jadi-lebih-seru-gamers-wajib-punya-5-perlengkapan-ini"
      target="_blank"
      rel="noopener"
      >3. nge-game
    </a>
    <br />
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>

    Saya kurang aktif di sosial media karna media sosial tidak berpengaruh
    penting bagi kehidupan saya.
    <a
      href="https://www.instagram.com/00zzyy__?igsh=MWFxdGhvc2w5aHQxdA=="
      target="_blank"
      rel="noopener"
      >click to my instagram</a
    >
  </WelcomeItem>
</template>
