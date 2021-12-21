<template>
  <div class="home">
    <div class="container">
      <div class="home__content">
        <div class="home__logo">
          <img alt="Lara" src="../assets/logo.jpg" />
        </div>
        <div class="home__text">
          <h1 class="home__title">Larisa Grushchenko</h1>
          <p class="home__subtitle">Web Developer</p>
          <p class="home__desc">
            Hi, I'm Lara. Originally from Ukraine, now I travel the world as a
            digital nomad with my family. Currently you can find in Cuenca,
            Ecuador. So far, I have been to and work in Estonia, Egypt, Bali
            (Indonesia), Colombia. I am an experienced and self-motivated web
            developer with ten years of industry experience.
          </p>
          <p class="home__skill-title">Skills</p>
          <div class="home__skill-list" v-for="skill in skills" :key="skill.id">
            <div class="home__skill">
              <span class="home__skill-name">{{ skill.name }}</span>
              <span class="home__skill-value">{{ skill.years }} years</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import skills from '@/data/skills.js'

export default {
  name: 'Home',
  data() {
    return {
      skills: skills,
    }
  },
}
</script>
