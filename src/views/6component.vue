<template>
  <div class="home">
    <h1>Recommended</h1>
    <kutular />
  
  </div>
  
</template>

<script>
import kutular from "@/components/kutular";

export default {
   components: { kutular,  }
};
</script>
<style  scoped>
* {
  display: block;
    background-color :#002650;
}
h1{
 text-align: start;
margin:auto;
margin-left: 3rem;
    
    font-weight: 500;
    line-height: 1.2;
    
}
</style>
