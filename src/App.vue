<template>
  <div>
    <NavbarComponents></NavbarComponents>
    <hr>
    <br>
    <br>
    <HeadersComponents></HeadersComponents>
    <br>
    <br>
     <div class="flex flex-row mt-5" style="margin-left: 8%;">
    <span class="flex w-3 h-3 bg-gray-200 rounded-full"></span>
    <span class="flex w-3 h-3 bg-gray-900 rounded-full dark:bg-gray-700"></span>
    <span class="flex w-3 h-3 bg-blue-600 rounded-full"></span>
    <span class="flex w-3 h-3 bg-green-500 rounded-full"></span>
    <span class="flex w-3 h-3 bg-red-500 rounded-full"></span>
    <span class="flex w-3 h-3 bg-purple-500 rounded-full"></span>
    <span class="flex w-3 h-3 bg-indigo-500 rounded-full"></span>
    <span class="flex w-3 h-3 bg-yellow-300 rounded-full"></span>
    <span class="flex w-3 h-3 bg-teal-500 rounded-full"></span>
    </div>
  <br>
    <hr>
    <br>
    <br>
    <MainComponents></MainComponents>
    <br>
    <br>
    <About></About>
    <br>
    <br>
    <Project></Project>
    <br>    
    <br>
    <Contact></Contact>
    <br>
    <Footer></Footer>

  </div>
</template>
  <script>
    import NavbarComponents from './components/NavbarComponents.vue';
    import HeadersComponents from './components/HeadersComponents.vue';
    import MainComponents from './components/MainComponents.vue';
    import About from './components/About.vue';
    import Project from './components/Project.vue';
    import Contact from './components/Contact.vue';
    import Footer from './components/Footer.vue'
    
    export default {
      components:{
    NavbarComponents,
    HeadersComponents,
    MainComponents,
    About,
    Project,
    Contact,
    Footer
}
    }
     </script>