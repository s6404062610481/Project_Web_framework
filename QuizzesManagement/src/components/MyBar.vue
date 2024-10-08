<template lang="">
    <div class="w3-bar w3-black">
        <ul>
            <li class="w3-bar-item w3-hover-red"><a href="#home">Home</a></li>
            <li class="w3-bar-item w3-hover-green"><a href="#about">About</a></li>
        </ul>
    </div>
</template>

<script>
export default {
    
}
</script>
<style scoped>
    ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
</style>