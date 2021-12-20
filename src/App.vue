<template>
  <div class="layout">
    <Header />
    <router-view v-slot="{ Component }">
      <transition name="slide-fade" mode="out-in" appear>
        <component :is="Component" />
      </transition>
    </router-view>
    <Footer />
  </div>
</template>

<script>
import Header from '@/layout/Header.vue'
import Footer from '@/layout/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
  },
}
</script>
