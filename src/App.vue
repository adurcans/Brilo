<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import WorkExam from './components/WorkExam.vue';
</script>

<template>
<div class="container">
  <div>
    <WorkExam msg="První příklad práce" />
  </div>
  <div>
    <WorkExam msg="Druhý příklad práce" />
  </div>
  <div>
    <WorkExam msg="Třetí příklad práce" />
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
  border:1px solid white;
  width:665px;
  height:300px;
  position: fixed;
  left: 50%;
  top: 70%;
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
