<template>
    <div id="personal-info">
      <comp-personal
        :user="user.username"
        :name="user.name"
        :age="user.age"
        :status="user.status"
      />
    </div>
  </template>
  
  <script>
    import CompPersonal from './CompPersonal.vue'
  
    export default {
      components: {
        CompPersonal,
      },
      data() {
        return {
          user: {
            username: 'matt',
            name: 'Matt Ramos',
            age: 22,
            status: true,
          },
        }
      },
    }
  </script>
  