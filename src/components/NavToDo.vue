<template>

  <div class="nav-to-do">
    <h1>{{title}}</h1>
       <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Features</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Pricing</a>
      </li>
      
    </ul>
  </div>
</nav>
      </div>
</template>

  <script>
export default {
  name: 'navToDo',
  props: {
    title: String
  }
}
</script> 


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-to-do {
    margin-top: 50px;
    background-color: aqua;
}
</style>
