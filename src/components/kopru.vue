<template>
<div class="kutu">
<ul>
  <li>
    Great for New Players
  </li>
  <li>
  Games
  </li>
  <li>
  Games
  </li>
  <li>
    Subscriptions
  </li>
  <li>
    Mounts
  </li>
  <li>
    Pets
  </li>
  <li>
    Toys
  </li>
  <li>
    Transmogs
  </li>
  <li>
    Bundles
  </li>
  <li>
    Game Services
  </li>
  <li>
    Gear
  </li>
  <li>
    Group by <Select v-model="selection" >
      <Option value="Categories" key="Categories">Categories</Option>
    </Select>
  </li>
  <li>
    Sort by <Select v-model="selection" >
      <Option value="Categories" key="Categories">Categories</Option>
    </Select>
  </li>
  </ul>
</div>


</template>

<script>
export default {

}
</script>

<style  scoped>


.kutu{
   background-image: url("../assets/top.png");
   background-color: #01234A;
  display: flex;
  
}
ul{
  color:#FFFFFF;
  margin:auto;
  display: flex;
  list-style-type: none; /* Remove bullets */
    justify-content: space-between;
}
ul li{
  font-size: 1.3rem;
  margin: 0.8rem;
  float: left;
}
ul li:last-child{
  flex :2;
}

</style>