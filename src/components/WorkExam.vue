<script setup>
import { stringify } from 'postcss';

defineProps({
  msg: {
    type: String,
    required: true
  },
  obr:{
    type: String,
    required: true
  }

})
</script>
    
<template>
<div class="examp">
    <a href="https://github.com/adurcans/Brilo">
    <img alt="Image" :src="'images/' + obr" width="200" height="150">
    </a>

    <h1>{{ msg }}</h1>
</div>
</template>
    
    <style scoped>
    h1 {
      font-weight: 500;
      font-size: 1rem;
      top: -10px;
      text-align: center;
    }
    
    h3 {
      font-size: 1.2rem;
    }
    

    .examp{
        float:left;
        margin:10px;
        text-align: center;
        color: white;
        font-style: initial;
        background-color: orange;
        width: 200px;
        height:210px;
    }
    .examp:hover {
        transform: translate3d(0px, -10px, 0px);
        background-color: grey;
}
   
    
    .greetings h1,
    .greetings h3 {
      text-align: center;
    }
    
    @media (min-width: 1024px) {
      .greetings h1,
      .greetings h3 {
        text-align: left;
      }
    }
    </style>
    