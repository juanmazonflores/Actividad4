<template>
    <div class="card">
      <personal-info></personal-info>
    </div>
</template>
  
<script>
    import PersonalInfo from './PersonalInfo.vue'
  
    export default {
      name: 'App',
      components: {
        PersonalInfo,
      },
    }
</script>

<style>

.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  border-radius: 5px; /* 5px rounded corners */
  background-color: indigo;
  color: aqua;
  flex-wrap: wrap;
}


</style>
  