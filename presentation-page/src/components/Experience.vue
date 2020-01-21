<template lang="html">
  <sui-grid class="experience">
    <sui-grid-row>
    <sui-grid-column/>
      <sui-grid-column :width="10">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
        when an unknown printer took a galley of type and scrambled it to make a type 
        specimen book. It has survived not only five centuries, but also the leap into 
        electronic typesetting, remaining essentially unchanged. It was popularised in 
        the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, 
        and more recently with desktop publishing software like Aldus PageMaker including
         versions of Lorem Ipsum.
      </sui-grid-column>
      <sui-grid-column/>
    </sui-grid-row>
  </sui-grid>
</template>

<script>
export default {
    name:'experience'   
}
</script>

<style>
.experience{
    color: white;
    width: 100vw;
    height: 100vh;
    background-color: #221f1e;
}

</style>