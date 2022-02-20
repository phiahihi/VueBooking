<template>
    <div class="main-app">
        <Header1 />
        <Header2 />
        <Header3 />
    </div>
</template>

<script>
import Header1 from "./Header1.vue"
import Header2 from "./Header2.vue"
import Header3 from "./Header3.vue"

export default {
    components: {
        Header1,
        Header2,
        Header3
    }
}
</script>

<style>
 * {
  padding: 0px auto;
  margin: 0;
  box-sizing: border-box;
}

.main-app {
    width: 1170px;
    margin: auto;
}
</style>