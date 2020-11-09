<template>
  <div class="home">
    <navbar />
  <menus /> 
  </div>
  
</template>

<script>
import navbar from "@/components/navbar";
import menus from "@/components/menu";
export default {
   components: { navbar, menus, }
};
</script>
