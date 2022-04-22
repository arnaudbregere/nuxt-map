<template>
  <div id="map-wrap" style="height: 100vh; width: 100vh">
    <client-only>
      <l-map :zoom=13 :center="[48.864716,2.349014]">
        <l-tile-layer url="http://{s}.tile.localhost:8080/tile/{z}/{x}/{y}.png"></l-tile-layer>
        <l-marker :lat-lng="[48.864716,2.349014]"></l-marker>
      </l-map>
    </client-only>
  </div>
</template>

<script>
export default {
  name: "TestMap"
}
</script>

<style scoped>

</style>
