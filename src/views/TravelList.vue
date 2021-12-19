<template>
  <div class="travel-list">
    <div class="container">
      <h1>Travel page</h1>
      <TravelCard v-for="travel in travels" :key="travel.id" :travel="travel" />
    </div>
  </div>
</template>

<script>
import TravelCard from '@/components/TravelCard.vue'

export default {
  name: 'TravelList',
  components: {
    TravelCard,
  },
  data: function () {
    return {
      events: null,
      travels: [
        {
          id: 1,
          name: 'Bali',
        },
        {
          id: 2,
          name: 'Egypt',
        },
        {
          id: 3,
          name: 'Colombia',
        },
        {
          id: 4,
          name: 'Ecuador',
        },
      ],
    }
  },
}
</script>
