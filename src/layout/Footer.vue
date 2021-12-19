<template>
  <div class="footer">
    <div class="container">
      <div class="footer__nav">
        <router-link class="footer__nav-item" :to="{ name: 'Home' }"
          >Home</router-link
        >
        <router-link class="footer__nav-item" :to="{ name: 'About' }"
          >About</router-link
        >
        <!-- <router-link class="footer__nav-item" :to="{ name: 'TravelList' }"
          >My travel</router-link
        > -->
        <router-link class="footer__nav-item" :to="{ name: 'Contact' }"
          >Contact</router-link
        >
      </div>
    </div>
  </div>
</template>
