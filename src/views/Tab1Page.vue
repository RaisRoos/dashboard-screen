<template>
  <ion-page class="container">
    
    <MainHeader />

    <ion-content :fullscreen="true">
      
      <MainDashboard />

    </ion-content>
  </ion-page>
</template>

<script setup>
import { IonContent,IonPage } from '@ionic/vue';
import MainHeader from '@/components/MainHeader.vue';
import MainDashboard from '@/components/MainDashboard.vue';
</script>

<style scoped>
</style>
