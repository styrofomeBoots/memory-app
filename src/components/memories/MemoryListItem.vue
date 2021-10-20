<template>
  <ion-item :router-link="`/memories/${memory.id}`">
    <!-- eslint-disable-next-line vue/no-deprecated-slot-attribute-->
    <ion-thumbnail slot="start">
      <ion-img :src="memory.image" :alt="memory.title"></ion-img
    ></ion-thumbnail>
    <ion-label>{{ memory.title }}</ion-label>
  </ion-item>
</template>

<script>
  import { IonItem, IonThumbnail, IonImg, IonLabel } from '@ionic/vue';

  export default {
    props: ['memory'],
    components: {
      IonItem,
      IonThumbnail,
      IonImg,
      IonLabel,
    },
  };
</script>

<style></style>
