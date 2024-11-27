<script setup >

import Hero from '@/components/Hero.vue'
import HomeCards from '@/components/HomeCards.vue'
import JobListings from '@/components/JobListings.vue'
</script>

<template>

<Hero title="Become a Vue Dev" subtitle="Official Vue job developer site" />
  <HomeCards/>
  <JobListings  :limit="4" :showButton="true" />

</template>