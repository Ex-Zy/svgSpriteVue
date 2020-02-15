<template>
  <div id="app">
    <svg-icon name="kik" title="Example title kik" />
    <svg-icon name="twitter" title="Title twitter" />
    <svg-icon name="instagram" title="Title instagram" />
    <svg-icon name="groupme" title="Group Me"/>
  </div>
</template>

<script>


export default {
  name: 'App',
}
</script>

<style scoped>
#app {
  text-align: center;
  padding: 50px;
}
.svg-icon {
  width: 50px;
  height: 50px;
  transition: fill 0.3s;
}
.icon-kik {
  fill: blueviolet;
}
.icon-kik:hover {
  fill: orangered;
}

.icon-twitter {
  fill: orange;
}
.icon-twitter:hover {
  fill: orangered;
}
</style>
