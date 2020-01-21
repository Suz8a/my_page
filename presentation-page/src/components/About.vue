<template lang="html">
  <sui-grid class="about">
    <sui-grid-row>
    <sui-grid-column/>
      <sui-grid-column  :width="10">
      <div class="information">
         Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
        when an unknown printer took a galley of type and scrambled it to make a type 
        specimen book. It has survived not only five centuries, but also the leap into 
        electronic typesetting, remaining essentially unchanged. It was popularised 
      </div>
      </sui-grid-column>
      <sui-grid-column/>
    </sui-grid-row>
  </sui-grid>
</template>

<script>
export default {
    name:'about'   
}
</script>

<style>
.about{
    color: white;
    font-size: 20px;
    line-height: 36px;
    width:100vw;
    height: 100vh;
    background-color:#221f1e;
}

.information{
    margin: 25% 0 25% 0;
}

</style>