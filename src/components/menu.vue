<template>
 <div class="sayfa">
    <div class="menu">
      <ul>
        <li id="birinci">
          <router-link to="/" class="active" href="#home">
            <svg
              _ngcontent-c12
              class="svg"
              aria-hidden="true"
              data-prefix="blz"
              data-icon="home"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 358.7"
              data-fa-i2svg
            >
              <path
                fill="currentColor"
                d="M494.9,161.8L267.4,9.1c-6.9-4.6-15.9-4.6-22.8,0L17.1,161.8c-9.4,6.3-11.9,19-5.6,28.5 	c6.3,9.4,19,11.9,28.5,5.6L75.5,172v131.9c0,27.2,21.5,49.2,47.9,49.2h265.2c26.4,0,47.9-22.1,47.9-49.2V172l35.5,23.8 	c3.5,2.3,7.5,3.5,11.4,3.5c6.6,0,13.1-3.2,17-9.1C506.8,180.9,504.3,168.1,494.9,161.8z M395.6,144.7v159.2c0,4.5-3.1,8.2-6.9,8.2 	H123.4c-3.8,0-6.9-3.7-6.9-8.2V145.7c0-0.4-0.1-0.8-0.1-1.1L256,50.7l139.6,93.7C395.6,144.6,395.6,144.6,395.6,144.7z"
              />
            </svg>Home
          </router-link>
        </li>

        <li>
          <router-link v-on:click="kapa" to="/" class="dropbtn">
            Games
            <svg _ngcontent-c12="" aria-hidden="true" class="svgkucuk" data-prefix="fa" data-icon="chevron-down" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" data-fa-i2svg=""><path fill="currentColor" d="M207.029 381.476L12.686 187.132c-9.373-9.373-9.373-24.569 0-33.941l22.667-22.667c9.357-9.357 24.522-9.375 33.901-.04L224 284.505l154.745-154.021c9.379-9.335 24.544-9.317 33.901.04l22.667 22.667c9.373 9.373 9.373 24.569 0 33.941L240.971 381.476c-9.373 9.372-24.569 9.372-33.942 0z"></path></svg>
          </router-link>
          
      
        
        </li>
        <li>
          <router-link to="/" href="#about">Blizzard Gear</router-link>
        </li>
    

        <li>
          <div class="arama">
            <svg
              _ngcontent-c21
              class="svgarama"
              aria-hidden="true"
              data-prefix="fas"
              data-icon="search"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
              data-fa-i2svg
            >
              <path
                fill="currentColor"
                d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"
              />
            </svg>
            <input class="input"  type=" text" placeholder="Search Shop" />      </div>
        </li>
          <div id="whish">
        <li >
          <router-link to="/" class="whislist" href="#about">
            <svg _ngcontent-c12="" aria-hidden="true" class="svgkalp" data-prefix="blz" data-icon="heart-empty" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-fa-i2svg=""><path fill="currentColor" d="M14.4374656,1.96877868 C15.0832975,2.5104439 15.531213,3.1771093 15.7812124,3.96877392 C16.0312118,4.76043854 16.0676702,5.55731164 15.8905871,6.35939322 C15.713504,7.1614748 15.3332969,7.85418116 14.7499648,8.43751326 L8.71872921,14.6874984 C8.51039622,14.8958314 8.27081377,14.9999976 7.99998093,14.9999976 C7.72914808,14.9999976 7.48956564,14.8958314 7.28123264,14.6874984 L1.24999702,8.46876319 C0.666664918,7.86459812 0.286457809,7.1614748 0.109374739,6.35939322 C-0.0677083308,5.55731164 -0.0312499255,4.76043854 0.218749478,3.96877392 C0.468748882,3.1771093 0.911456319,2.5104439 1.54687131,1.96877868 C2.1822863,1.42711347 2.88540963,1.11461421 3.65624128,1.03128092 C4.34373964,0.947947626 5.04165449,1.0416974 5.74998629,1.31253025 C6.39581824,1.56252965 6.93748346,1.91669532 7.37498242,2.37502772 L7.99998093,3.03127615 L8.62497944,2.37502772 C9.14581169,1.8333625 9.75518523,1.44794643 10.4531001,1.21878047 C11.1510149,0.989614512 11.8541382,0.937531143 12.56247,1.06253085 C13.2708019,1.18753055 13.8958004,1.48961332 14.4374656,1.96877868 Z M14.0312165,7.7500149 C14.4478821,7.33334939 14.7343399,6.81772562 14.8905895,6.20314359 C15.0468391,5.58856156 15.0416306,4.98960497 14.8749645,4.40627287 C14.687465,3.73960796 14.3280908,3.1823173 13.7968421,2.73440186 C13.2655934,2.28648642 12.6770533,2.04169502 12.0312213,2.00002861 C11.5103891,1.97919517 10.9791403,2.09377839 10.4374751,2.34377779 C9.97914272,2.53127734 9.61456057,2.78127675 9.34372772,3.093776 L7.99998093,4.46877272 L6.65623413,3.093776 C6.36456832,2.78127675 5.99998569,2.52086086 5.56248674,2.31252787 C5.02082152,2.06252846 4.48957279,1.9583622 3.96874054,2.00002861 C3.32290859,2.04169502 2.73436848,2.28648642 2.20311975,2.73440186 C1.67187101,3.1823173 1.31249687,3.73960796 1.12499732,4.40627287 C0.958331207,4.98960497 0.953122728,5.58856156 1.10937236,6.20314359 C1.26562198,6.81772562 1.55207979,7.33334939 1.96874531,7.7500149 L7.99998093,14 L14.0312165,7.7500149 Z"></path></svg>
            Whish List
          </router-link>
        </li></div>
        <li >
          <router-link to="/" class="dropbtn">
            Blizard Balance
           <svg _ngcontent-c12="" aria-hidden="true" class="svgkucuk" data-prefix="fa" data-icon="chevron-down" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" data-fa-i2svg=""><path fill="currentColor" d="M207.029 381.476L12.686 187.132c-9.373-9.373-9.373-24.569 0-33.941l22.667-22.667c9.357-9.357 24.522-9.375 33.901-.04L224 284.505l154.745-154.021c9.379-9.335 24.544-9.317 33.901.04l22.667 22.667c9.373 9.373 9.373 24.569 0 33.941L240.971 381.476c-9.373 9.372-24.569 9.372-33.942 0z"></path></svg>
          </router-link>
         
        </li>
      </ul>
    </div>
    </div>
  
</template>

<script>
export default {
  data() {
    return {
      show: true
    };
  },
  methods: {
    kapa: function() {
      if (this.show == true) {
        this.show = false;
      } else {
        this.show = true;
      }
    }
  }
};
</script>

<style  scoped>
.sayfa{
   background-color: #002650; 
   margin:0;
}
div{
  margin:0;
}
.menu{
   border-bottom: 1px solid rgba(255,255,255,.15);
    border-top: 1px solid rgba(255,255,255,.15);
   margin:0;
    width: 80%;
    display: flex;
    flex-wrap:   wrap;
    margin-left: 10%;




}
a{
    color: #ffffffcc;
}
ul{
    list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
  align-items: baseline;
  
  

}
li{
  margin:10px;
  font-size: 1rem;
}
.svg{
  margin-right: 1rem;
    width: 25px;
    height: 25px;
    color:#0e86ca
}
.arama{
  margin-left: 28rem;
  width: 30rem;
  border:1px solid rgba(255,255,255,.15);
  height:2rem ;
  display: flex;
  padding:auto;
  background-color: #001732;
}
input{
  height: 100%;
  width: 100%;
   outline: none;
  border: none;
  color: white;
 
}
.arama:focus{
  height: 3rem;
}
.svgkucuk{
width: 10px;
height: 10px;
}
.svgkalp{
  width: 20px;
  height: 20px;
  
}
#whish{
border:1px solid rgba(255,255,255,.15);

}
.svgarama{
  margin-right: 1rem;
    width: 20px;
    height: 20px;
    color:#0e86ca
}

</style>