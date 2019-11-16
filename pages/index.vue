<template>
  <div class="container">
    <h1>Hallo</h1>
    <Skill title="Design" level="90"/>
    <Skill title="Technik" level="60"/>
    <Skill title="Konzept" level="80"/>
  </div>
</template>

<script>
import Skill from '~/components/skill.vue'

export default {
  components: {
    Skill
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  max-width: 38rem;
}
</style>
