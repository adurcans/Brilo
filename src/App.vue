<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import WorkExam from './components/WorkExam.vue';
import PageHeader from './components/PageHeader.vue';
import Container from './components/Container.vue';
</script>

<template>
<PageHeader />

<Container />


<div class="container">
  <h2>WHAT I DID</h2>
  <div>
    <WorkExam msg="Company website refactoring" obr="4.jpeg" />
  </div>
  <div>
    <WorkExam msg="Custom single-page application" obr="1.jpeg"/>
  </div>
  <div>
    <WorkExam msg="Application Programming Interface" obr="2.jpeg" />
  </div>
 
</div>

</template>

<style scoped>
header {
  line-height: 1.5;
}

.container{
  overflow:auto;
  display:table;
  margin:25px;
  width:665px;
  height:300px;
  position: fixed;
  top: 75%;
  transform: translate(-50%, -50%);
}


.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
