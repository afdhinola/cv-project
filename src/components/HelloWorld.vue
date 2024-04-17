<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <img src="" alt="">
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Portfolio ini mungkin masih banyak kekurangan, tapi percaya lah saya sedang melakukan yang terbaik agar saya bisa lebih menguasainya dengan terus belajar walaupun perlahan. 

    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
