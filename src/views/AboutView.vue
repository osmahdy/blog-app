<template>
  <div class="about">
    <pageHeader name='About Page' desc='the About page in the blog'/>
    <div class="container">
      <CardEl 
      style="background-color: #4e596f80"
       :showMedia="false"
       :showHeader='false'
       :showText='true'
       :showBtns='true'
       >
          <template v-slot:media>
          </template>
          <template v-slot:header>
          </template>
          <template v-slot:text>
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis dicta, consectetur officia accusantium voluptates eligendi enim corporis praesentium repudiandae, illum quam modi eaque est. Qui consectetur aspernatur quod magnam. Eos?
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis dicta, consectetur officia accusantium voluptates eligendi enim corporis praesentium repudiandae, illum quam modi eaque est. Qui consectetur aspernatur quod magnam. Eos?
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis dicta, consectetur officia accusantium voluptates eligendi enim corporis praesentium repudiandae, illum quam modi eaque est. Qui consectetur aspernatur quod magnam. Eos?
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis dicta, consectetur officia accusantium voluptates eligendi enim corporis praesentium repudiandae, illum quam modi eaque est. Qui consectetur aspernatur quod magnam. Eos?
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis dicta, consectetur officia accusantium voluptates eligendi enim corporis praesentium repudiandae, illum quam modi eaque est. Qui consectetur aspernatur quod magnam. Eos?
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis dicta, consectetur officia accusantium voluptates eligendi enim corporis praesentium repudiandae, illum quam modi eaque est. Qui consectetur aspernatur quod magnam. Eos?
            </p>
          </template>
          <template v-slot:btns>
            <btn
              url="https://mail.google.com/mail/?view=cm&fs=1&to=os6sooma@gmail.com&su=Inquiry&body=Hello,%20I%20have%20a%20question%20about..."
              content="Contact Us"
                style="color: white;
                    background-color: #27AE60"/>
            <btn
              url="https://www.X.com"
              content="Twitter"
                style="color: white;
                    background-color: #27AE60"/>
            <btn
              url="https://www.instagram.com"
              content="Instagram"
                style="color: white;
                    background-color: #27AE60"/>
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
    name: 'AboutView',
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
 p {
  text-align: start;
}
</style>