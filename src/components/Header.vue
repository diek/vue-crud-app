<!-- HTML code -->
<template>
    <header>
      <h1>{{ title }}</h1>
    </header>
</template>
<!-- JavaScript (Vue) code -->
<script>
  export default {
    name: 'Header',
    date () {
      return {
        title: 'Vue CRUD Project'
      }
    }
  }
</script>

<!-- CSS code -->
!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  margin: auto;
}

header h1 {
  font-size: 2.5em;
}
</style>
