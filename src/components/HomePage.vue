<template>
  <div class="box flex jc-sb">
    <div>Race2Win Logo</div>
    <div class="box flex">
      <div class="box">
        <router-link to="/calendar">Calenndar</router-link>
      </div>
      <div class="box">
        <router-link to="/loginRegister">Login / Register</router-link>
      </div>
    </div>
  </div>
  <div class="box" style="height: 300px">Banner</div>
  <div class="box" style="height: 100px">Ticker/Highlights/Live Feed</div>
  <div class="box" style="height: 300px">
    Calendar (https://betway.com/en/sports/rcg/horse-racing/today)
  </div>

  <div class="box" style="height: 100px">Branding Footer</div>
</template>

<script>
export default {
  name: "HomePage",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
