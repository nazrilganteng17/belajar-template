<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://s3.amazonaws.com/busites_www/poison/gallery-media/vip-banner-5911-1575920188.jpg',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://s3.amazonaws.com/busites_www/poison/gallery-media/tour-banner-5912-1575920188.jpg',
    'alt': 'Picture 2',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>