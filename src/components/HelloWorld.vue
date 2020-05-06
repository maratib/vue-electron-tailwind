<template>
  <div class="hello">
    <div class="bg-purple-500 sm:bg-green md:bg-blue md:text-yellow lg:bg-red xl:bg-orange">
      <h1>{{ msg }}</h1>
    </div>

    <div style="height: 300px: width=300px">
      <div class="bg-white rounded-lg p-6">
        <img class="h-16 w-16 rounded-full" src="https://randomuser.me/api/portraits/women/17.jpg" />
        <div>
          <h2>Erin Lindford</h2>
          <div>Customer Support</div>
          <div>erinlindford@example.com</div>
          <div>(555) 765-4321</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
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
