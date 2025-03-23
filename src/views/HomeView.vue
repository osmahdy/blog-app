<template>
  <div class="home">
    <pageHeader name='Home Page' desc='the home page in the blog'/>
    <div class="container">
      <CardEl 
      style="background-color: #4e596f80"
       :showMedia="true"
       :showHeader='true'
       :showText='true'
       :showBtns='true'
       >
          <template v-slot:media>
            <img src="@/assets/features-03.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>See Our Magic Work</h3>
          </template>
          <template v-slot:text>
            <p>we provide lots of services</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Check our services"
                style="color: white;
                    background-color: #1F2937"/>
            <btn
              url="https://www.google.com"
              content="Our Hot Sales"
                style="color: white;
                    background-color: #b22222"/>
          </template>
      </CardEl>
      <CardEl 
      style="background-color: #4e596f80"
       :showMedia="false"
       :showHeader='true'
       :showText='true'
       :showBtns='false'
       >
          <template v-slot:media>
          </template>
          <template v-slot:header>
            <h3>who We Are?</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos praesentium cum aliquam dolor est corporis ipsum? Tempore possimus magnam minima accusamus sint vitae vero deleniti, hic quia nostrum nam rerum?</p>
          </template>
          <template v-slot:btns>
          </template>
      </CardEl>
      <CardEl 
      style="background-color: #4e596f80"
       :showMedia="false"
       :showHeader='true'
       :showText='false'
       :showBtns='true'
       >
          <template v-slot:media>
          </template>
          <template v-slot:header>
            <h3>Visit Our Store</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos praesentium cum aliquam dolor est corporis ipsum? Tempore possimus magnam minima accusamus sint vitae vero deleniti, hic quia nostrum nam rerum?</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="The Store Website"
                style="color: white;
                    background-color: #27AE60"/>
          </template>
      </CardEl>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import btn from '@/components/btn'
import CardEl from '@/components/CardEl'
import pageHeader from '@/components/pageHeader'
export default {
  name: 'HomeView',
  components: {
    CardEl,
    pageHeader,
    btn
  }
}
</script>

<style scoped>
.home .container {
  width: calc(100vw - 200px);
  margin: auto;
}
img {
  width: 100%;
}
</style>
