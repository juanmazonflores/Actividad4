<template>
    <div id="personal-info">
      User: {{user}}<br />
      Name: {{name}} <br />
      Age: {{age}} <br />
      Status: {{status}}
    </div>
  </template>
  
  <script>
    export default {
      props: ['user', 'name', 'age', 'status'],
    }
  </script>
  
  <style>
    #personal-info > div{
      padding: 50px;
      font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
      width: 500;
    }
  </style>
  