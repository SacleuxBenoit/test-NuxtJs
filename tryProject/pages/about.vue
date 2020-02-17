<template>
  <section class="container">
    <h1>This is an about page</h1>
    <p class="subheading">this is a test</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos sapiente eius temporibus, praesentium quae optio, autem deleniti quam dolorum qui hic</p>
  </section>
</template>
<script>


export default {
      head(){
          return{
              title:"About nuxt",
              meta:[
                  {name:'description', content:'this is my about description'},
                  {name:'keywords', content:'about nuxt, nuxt infos'},

              ]
          }
      }
}
</script>
