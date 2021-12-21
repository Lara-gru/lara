<template>
  <div class="footer">
    <div class="footer__container">
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
      <div class="footer__social-list">
        <div class="footer__social-item">
          <a
            href="https://www.linkedin.com/in/kosichkina/"
            alt="Linkedin"
            target="_blank"
            ><span class="icon icon-linkedin"></span
          ></a>
        </div>
        <div class="footer__social-item">
          <a href="https://github.com/Lara-gru/" alt="Github" target="_blank"
            ><span class="icon icon-github"></span
          ></a>
        </div>
        <div class="footer__social-item">
          <a
            href="mailto:larisa.kosichkina@gmail.com"
            alt="Email"
            target="_blank"
            ><span class="icon icon-mail"></span
          ></a>
        </div>
      </div>
    </div>
  </div>
</template>
