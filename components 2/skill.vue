<template>
  <div>
  	<h3 class="Skill_title">{{ title }}</h3>
  	<div class="background">
  		<div class="active" :style="{ width: level + '%' }">{{ level }} %</div>
  	</div>
  </div>
</template>

<script>
  export default {
  	props: ['title', 'level']
  }
</script>

<style>
 .background {
 	background-color: gray;
 }
 .active {
 	background-color: green;
 }
 .Skill_title {
 	margin-top: 3rem;
 }
</style>