<template>
    <div class="blog">
        <pageHeader name='Blog Page' desc='the Blog page in the blog'/>
        <div class="container">
        <CardEl 
            style="background-color: #4e596f80"
            :showMedia="true"
            :showHeader='true'
            :showText='true'
            :showBtns='true'
            >
          <template v-slot:media>
            <img src="@/assets/cat-01.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>Blog Post 1</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem maiores corrupti consequatur. Rem exercitationem vero facere mollitia aperiam assumenda</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Read More"
                style="color: #1F2937;
                    background-color: #ffd428;
                    width: 90%"/>
          </template>
      </CardEl>
        <CardEl 
            style="background-color: #4e596f80"
            :showMedia="true"
            :showHeader='true'
            :showText='true'
            :showBtns='true'
            >
          <template v-slot:media>
            <img src="@/assets/cat-02.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>Blog Post 2</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem maiores corrupti consequatur. Rem exercitationem vero facere mollitia aperiam assumenda</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Read More"
                style="color: #1F2937;
                    background-color: #ffd428;
                    width: 90%"/>
          </template>
      </CardEl>
        <CardEl 
            style="background-color: #4e596f80"
            :showMedia="true"
            :showHeader='true'
            :showText='true'
            :showBtns='true'
            >
          <template v-slot:media>
            <img src="@/assets/cat-03.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>Blog Post 3</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem maiores corrupti consequatur. Rem exercitationem vero facere mollitia aperiam assumenda</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Read More"
                style="color: #1F2937;
                    background-color: #ffd428;
                    width: 90%"/>
          </template>
      </CardEl>
        <CardEl 
            style="background-color: #4e596f80"
            :showMedia="true"
            :showHeader='true'
            :showText='true'
            :showBtns='true'
            >
          <template v-slot:media>
            <img src="@/assets/cat-04.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>Blog Post 4</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem maiores corrupti consequatur. Rem exercitationem vero facere mollitia aperiam assumenda</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Read More"
                style="color: #1F2937;
                    background-color: #ffd428;
                    width: 90%"/>
          </template>
      </CardEl>
        <CardEl 
            style="background-color: #4e596f80"
            :showMedia="true"
            :showHeader='true'
            :showText='true'
            :showBtns='true'
            >
          <template v-slot:media>
            <img src="@/assets/cat-05.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>Blog Post 5</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem maiores corrupti consequatur. Rem exercitationem vero facere mollitia aperiam assumenda</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Read More"
                style="color: #1F2937;
                    background-color: #ffd428;
                    width: 90%"/>
          </template>
      </CardEl>
        <CardEl 
            style="background-color: #4e596f80"
            :showMedia="true"
            :showHeader='true'
            :showText='true'
            :showBtns='true'
            >
          <template v-slot:media>
            <img src="@/assets/cat-06.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>Blog Post 6</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem maiores corrupti consequatur. Rem exercitationem vero facere mollitia aperiam assumenda</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Read More"
                style="color: #1F2937;
                    background-color: #ffd428;
                    width: 90%"/>
          </template>
      </CardEl>
        <CardEl 
            style="background-color: #4e596f80"
            :showMedia="true"
            :showHeader='true'
            :showText='true'
            :showBtns='true'
            >
          <template v-slot:media>
            <img src="@/assets/cat-07.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>Blog Post 7</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem maiores corrupti consequatur. Rem exercitationem vero facere mollitia aperiam assumenda</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Read More"
                style="color: #1F2937;
                    background-color: #ffd428;
                    width: 90%"/>
          </template>
      </CardEl>
        <CardEl 
            style="background-color: #4e596f80"
            :showMedia="true"
            :showHeader='true'
            :showText='true'
            :showBtns='true'
            >
          <template v-slot:media>
            <img src="@/assets/cat-08.jpg" alt="">
          </template>
          <template v-slot:header>
            <h3>Blog Post 8</h3>
          </template>
          <template v-slot:text>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem maiores corrupti consequatur. Rem exercitationem vero facere mollitia aperiam assumenda</p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://www.google.com"
              content="Read More"
                style="color: #1F2937;
                    background-color: #ffd428;
                    width: 90%"/>
          </template>
      </CardEl>
    </div>
    </div>
</template>

<script>
import btn from '@/components/btn'
import CardEl from '@/components/CardEl'
import pageHeader from '@/components/pageHeader'
export default {
    name: 'BlogView',
    components: {
        btn,
        CardEl,
        pageHeader,
    }
}
</script>


<style scoped>
.container {
  width: calc(100vw - 200px);
  margin: auto;
}
img {
  width: 100%;
}
</style>