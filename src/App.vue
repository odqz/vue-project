<script setup>
  import Character from './components/Character.vue';

  const musashi = {
    imageUrl: 'src/assets/images/musashi.png',
    name: 'Miyamoto Musashi',
    age: '23',
    gender: 'Male',
    height: ' 6ft',
    bio: 'Miyamoto Musashi is one of the main protagonists in Vagabond, and a historical figure considered one of the greatest Samurai (swordsmen) in Japanese history. As a young man he embarks on a journey to become the strongest samurai after being exiled from his village.'
  }

  const kojiro = {
    imageUrl: 'src/assets/images/kojiro.jpg',
    name: 'Sasaki Kojiro',
    age: '22',
    gender: 'Male',
    height: ' 6ft 2in',
    bio: 'Sasaki Kojiro known as the "Crazy Tiger from Echizen" is one of the main protagonists of Vagabond. He is the legendary arch-rival of Musashi Miyamoto. In the series, he is portrayed as deaf-mute.'
  }

  const honiden = {
    imageUrl: 'src/assets/images/matahachi.webp',
    name: 'Matahachi Honiden',
    age: '21',
    gender: 'Male',
    height: '5ft 10in',
    bio: "Matahachi Hon'iden is one of the main characters in the series and a childhood friend of Musashi Miyamoto."
  }

  const takuan = {
    imageUrl: 'src/assets/images/takuan.jpg',
    name: 'Soho Takuan',
    age: '21',
    gender: 'Male',
    height: '5ft 10in',
    bio: "Soho Takuan is a fictional character from the Vagabond manga series. He serves as a mentor and a friend to Musashi and acts as a big brother to Otsu."
  }
</script>

<template>
  <div class="p-2 flex flex-wrap gap-8">
    <Character
      :image-url="musashi['imageUrl']"
      :name="musashi['name']"
      :age="musashi['age']"
      :gender="musashi['gender']"
      :height="musashi['height']"
      :bio="musashi['bio']"
    />

    <Character
      :image-url="kojiro['imageUrl']"
      :name="kojiro['name']"
      :age="kojiro['age']"
      :gender="kojiro['gender']"
      :height="kojiro['height']"
      :bio="kojiro['bio']"
    />

    <Character
      :image-url="honiden['imageUrl']"
      :name="honiden['name']"
      :age="honiden['age']"
      :gender="honiden['gender']"
      :height="honiden['height']"
      :bio="honiden['bio']"
    />

    <Character
      :image-url="takuan['imageUrl']"
      :name="takuan['name']"
      :age="takuan['age']"
      :gender="takuan['gender']"
      :height="takuan['height']"
      :bio="takuan['bio']"
    />
  </div>
</template>

<style scoped>
</style>
