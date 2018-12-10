<template>
  <app-records></app-records>
</template>
<script>
import addRecords from "./components/addRecord";

export default {
  name: "App",
  components: {
    "app-records": addRecords
  }
};
</script>
