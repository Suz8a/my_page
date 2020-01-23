<template lang="html">
  <sui-grid class="skill">
  <img class="background-image-skills" src="../assets/blackWallpaper.jpg">
  <sui-grid-row/>
    <sui-grid-column>
      <sui-grid-row>
        <h1 class="skill-title">Skills</h1>
      </sui-grid-row>
    </sui-grid-column>
    <sui-grid-row :columns="4">
      <sui-grid-column>
        <div class="image-container">
          <img class="image" src="../assets/js.png">
        </div>
      </sui-grid-column>
      <sui-grid-column>
        <div class="image-container">
          <img class="image" src="../assets/html5.png">
        </div>
      </sui-grid-column>
      <sui-grid-column>
        <div class="image-container">
          <img class="image" src="../assets/css.jpg">
        </div>
      </sui-grid-column>
      <sui-grid-column>
        <div class="image-container">
          <img class="image" src="../assets/react.jpg">
        </div>
      </sui-grid-column>
    </sui-grid-row>
    <sui-grid-row />
    <sui-grid-row :columns="4">
      <sui-grid-column/>
      <sui-grid-column>
        <div class="image-container">
          <img class="image" src="../assets/vue.png">
        </div>
      </sui-grid-column>
      <sui-grid-column>
        <div class="image-container">
          <img class="image" src="../assets/mongoDB.png">
        </div>
      </sui-grid-column>
      <sui-grid-column/>
    </sui-grid-row>
    <sui-grid-row/>
  </sui-grid>
</template>

<script>
export default {
    name:'skill'   
}
</script>

<style scope>
.background-image-skills{
  opacity: 0.2;
  position: absolute;
  width: 100%;
  height: 100%;
}
.skill-title{
  padding-left: 20px;
}
.skill{
    color: white;
    width: 100vw;
    height: 100vh;
    background-color: #292625;
}
.image{
  width: 150px;
  height: 150px;
}
.image-container{
  margin: 0 auto;
  padding: 50px;
  width: 240px;
  height: 240px;
  border-radius: 50%;
  background-color: white;
}

</style>