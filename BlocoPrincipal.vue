<script>
export default {
  data() {
    return {
      imagens: [new URL("./Fotos_Jogadores/Cristiano-Ronaldo.jpg",import.meta.url).href,
                new URL("./Fotos_Jogadores/philippe-coutinho.jpg",import.meta.url).href,
                new URL("./Fotos_Jogadores/haaland-city.jpg",import.meta.url).href,
                new URL("./Fotos_Jogadores/bruno-gui.jpeg",import.meta.url).href
              ]
    };
  },
};
</script>

<template>  
  <main id="content">
    <img class="block" :src="imagens[0]" alt="">
    <img class="block" :src="imagens[1]" alt="">
    <img class="block" :src="imagens[2]" alt="">
    <img class="block" :src="imagens[3]" alt="">

  </main>
</template>

<style></style>
