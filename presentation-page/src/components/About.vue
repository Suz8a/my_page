<template lang="html">
  <sui-grid class="about">
    <img class="background-image" src="https://cdn.pixabay.com/photo/2015/10/27/14/40/programming-1009134_960_720.jpg">
  <sui-grid-row v-for="n in 3" :key="n" />
  <sui-grid-row>
      <img class="profilePhoto in-left" src="../assets/profile.jpg" />
  </sui-grid-row>
  <sui-grid-row/>
  <sui-grid-row>
    <sui-grid-column :width="2" />
      <sui-grid-column  :width="8">
        <div class="title in-top">About Me</div>
      </sui-grid-column>
  </sui-grid-row>
    <sui-grid-row>
      <sui-grid-column :width="2" />
        <sui-grid-column  :width="6">
          <div class="information in-top-info">
         Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
        when an unknown printer took a galley of type and scrambled it to make a type 
        specimen book. It has survived not only five centuries, but also the leap into 
        electronic typesetting, remaining essentially unchanged. It was popularised 
        
          </div>
        </sui-grid-column>
      <sui-grid-column :width="8" />
    </sui-grid-row>
    <sui-grid-row v-for="n in 6" :key="n" />
  </sui-grid>
</template>

<script>
export default {
    name:'about'   
}

</script>

<style scope>
@keyframes fadeInRight {
    from {
        opacity:0;
        transform: translatex(100px);
    }
    to {
        opacity:1;
        transform: translatex(0);
    }
}
@keyframes fadeInTop {
    from {
        opacity:0;
        transform: translatey(100px);
    }
    to {
        opacity:1;
        transform: translatey(0);
    }
}
.in-top{
    animation-name: fadeInTop;
    animation-fill-mode: both;
    animation-duration: 0.6s;
    animation-delay: 0.2s;
}
.in-top-info{
    animation-name: fadeInTop;
    animation-fill-mode: both;
    animation-duration: 0.6s;
    animation-delay: 0.5s;
}
.in-left {
    animation-name: fadeInRight;
    animation-fill-mode: both;
    animation-duration: 0.6s;
    animation-delay: 0.8s;
}
.background-image{
  position: absolute;
  width: 100%;
  height:100%;
  opacity: 0.04;
  
}
.profilePhoto{
  position: absolute;
  left: 55%;
  top: 40%;
  bottom: 50%;
  filter: brightness(125%) grayscale(100%);
  border-radius: 20px;
  box-shadow: 10px 10px 10px #000000d6; 
  z-index: 1;
}
.title{
  font-size: 50px;
}
.about{
    height: 100vh;
    width: 100vw;
    text-align: justify;
    color: white;
    font-size: 20px;
    line-height: 30px;
    width:100vw;
    height: 100vh;
    background-color:#221f1e;
    float: left;
    z-index: 3;
}

</style>