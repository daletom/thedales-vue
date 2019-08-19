<template>
  <div class="topnav">
    <a class="active" href="https://thedales.me/">Home</a>
    <a href="https://thedales.me/tom">Tom</a>
    <a href="https://thedales.me/heather">Heather</a>
    <a href="https://thedales.me/zeek">Zeek</a>
    <a href="https://thedales.me/video">Video</a>
  </div>
</template>

<script>
export default {
  name: "topnavhome",
  props: {
    msg: String
  }
};
</script>

<style>
body {
  color: dark-gray;
  font-family: Rancho, sans-serif;
  text-align: center;
}

h1,
h2 {
  font-family: Rancho, cursive;
  margin: 0.125em;
}

h1 {
  font-size: 6em;
  margin: 0.5em;
  text-align: center;
}

h2 {
  font-size: 1.7em;
}

.topnav {
  background-color: #333;
  overflow: hidden;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 2em;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #4caf50;
  color: white;
}
</style>
