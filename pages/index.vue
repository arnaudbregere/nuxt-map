<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
    Hello World Leaflet
    </v-col>
    <TestMap/>
  </v-row>
</template>

<script>
import TestMap from "~/components/TestMap";
export default {
  name: 'IndexPage',
  components: {
    TestMap
  }
}
</script>
