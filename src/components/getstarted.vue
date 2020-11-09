<template>
  <div class="sayfa">
    <div class="card">
      <img class="logo" src="../assets/blizzlogo.png" alt="" />
      <h1>Get starded</h1>
      <p>
        Let us verify some information about you to help set up your
        account.<router-link to="/">Learn why we need this. </router-link>
      </p>
      <select v-model="selected">
        <option>Turkey</option>
        <option>USA</option>
        <option>England</option>
      </select>
      <div>
        <input
          class="tarih"
          v-model="message"
          placeholder="Date of Birth(dd/mm/yyyy)"
        />
      </div>
      <button v-on:click="greet">Continue</button>
      <p class="yazi">OR SING UP WITH</p>
      <div class="emailout">
        <button class="sosyal" type="submit">
          <img src="../assets/facebookimg.png" alt />
        </button>
        <button class="sosyal" type="submit">
          <img src="../assets/googleimg.png" alt />
        </button>
        <button class="sosyal" type="submit">
          <img class="img" src="../assets/applelogo.png" alt />
        </button>
        <p>Already have an account? <router-link to="/">Login</router-link></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      selected: "Turkey"
    };
  }
};
</script>

<style lang="scss" scoped>
.sayfa {
  display: grid;
  background-color: rgb(9, 69, 119);
  grid-template-columns: 2fr 2fr 2fr;
}
.card {
  max-width: 500px;
  margin: 50px;
  grid-column: 2/3;
}
.logo {
  height: 60px;
  width: 120px;
}
select {
  width: 400px;
  height: 40px;
  color: white;
  background-color: black;
}
p {
  color: white;
}
.tarih {
  width: 395px;
  height: 40px;
  color: white;
  background-color: black;
  border: none;
  margin-top: 10px;
}
button {
  background-color: #00649c;
  color: white;
  width: 400px;
  margin-top: 10px;
  height: 40px;

  font-size: 17px;
  text-align: center;
  background-color: #0e86ca;
  color: #fff;
  border: 1px solid #10a1de;
  box-shadow: 0 0 rgba(0, 0, 0, 0);
  border-radius: 0;
  transition: background-color 0.2s, box-shadow 0.2s, background-color 0.2s,
    border-color 0.2s, color 0.2s;
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.3),
    0 0 0 1px rgba(255, 255, 255, 0.15) inset;
}
.sosyal {
  margin-left: 10px;
  background: white;
  line-height: 20px;
  width: 44px;
  height: 44px;
}
.sosyal:first-child {
  background-color: #165dee;
}
.img {
  width: 20px;
  align-self: center;
}
a {
  color: #139cff;
}
</style>
