<script setup>
  import CharacterImage from './character-components/CharacterImage.vue';
  import CharacterName from './character-components/CharacterName.vue';
  import CharacterDetail from './character-components/CharacterDetail.vue';

  defineProps({
    imageUrl: String,
    name: String,
    age: Number,
    gender: String,
    height: String,
    bio: String,
  })
</script>

<template>
  <div class="flex border border-2 p-4 w-fit gap-2">
    <div class="flex-1">
      <CharacterImage :image-url="imageUrl"></CharacterImage>
    </div>
    <div class="flex-1 w-96">
      <div>
        <CharacterName :name></CharacterName>
      </div>
      <div>
        <CharacterDetail label="Age" :value="age"></CharacterDetail>
        <CharacterDetail label="Gender" :value="gender"></CharacterDetail>
        <CharacterDetail label="Height" :value="height"></CharacterDetail>
        <CharacterDetail label="Bio" :value="bio"></CharacterDetail>
      </div>
    </div>
  </div>
</template>