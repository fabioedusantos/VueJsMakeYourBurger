<template>
  <div id="footer">
    <p>Make Your Burger &copy; 2022.</p>
  </div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
#footer{
  clear: both;

  background-color: #222;
  border-top: 4px solid #111;
  color: #fcba03;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;

  bottom: 0;
  height: 200px;
}
</style>