<template lang="html">
  <sui-grid class="about">
  <sui-grid-row/>
  <sui-grid-row/>
  <sui-grid-row/>
    <sui-grid-row>
      <img class="profilePhoto fade-in" src="../assets/profile.jpg" />
  </sui-grid-row>
  <sui-grid-row/>
  <sui-grid-row>
    <sui-grid-column :width="2" />
      <sui-grid-column  :width="8">
        <div class="title">About Me</div>
      </sui-grid-column>
  </sui-grid-row>
    <sui-grid-row>
    <sui-grid-column :width="2" />
      <sui-grid-column  :width="6">
      <div class="information">
         Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
        when an unknown printer took a galley of type and scrambled it to make a type 
        specimen book. It has survived not only five centuries, but also the leap into 
        electronic typesetting, remaining essentially unchanged. It was popularised 
        
      </div>
      
      </sui-grid-column>
      <sui-grid-column :width="8" />
    </sui-grid-row>
    <sui-grid-row/>
    <sui-grid-row/>
    <sui-grid-row/>
    <sui-grid-row/>
    <sui-grid-row/>
    <sui-grid-row/>
    
  </sui-grid>
</template>

<script>
export default {
    name:'about'   
}
</script>

<style>
.fade-in {
  animation: fadeIn ease 2.5s;
  -webkit-animation: fadeIn ease 2.5s;
  -moz-animation: fadeIn ease 2.5s;
  -o-animation: fadeIn ease 2.5s;
  -ms-animation: fadeIn ease 2.5s;
}


@keyframes fadeIn{
  0% {
    opacity:0;
  }
  100% {
    opacity:1;
  }
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