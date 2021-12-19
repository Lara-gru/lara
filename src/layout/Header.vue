<template>
  <div class="header">
    <div class="container">
      <div class="header__nav">
        <router-link class="header__nav-item" :to="{ name: 'Home' }"
          >Home</router-link
        >
        <router-link class="header__nav-item" :to="{ name: 'About' }"
          >About</router-link
        >
        <!-- <router-link class="header__nav-item" :to="{ name: 'TravelList' }"
          >My travel</router-link
        > -->
        <router-link class="header__nav-item" :to="{ name: 'Contact' }"
          >Contact</router-link
        >
      </div>
    </div>
  </div>
</template>
