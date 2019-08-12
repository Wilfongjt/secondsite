<template>
  <div id="search" class="band">
    <h1 class="title">
      {{ page.title }}
    </h1>
    <h1 class="subtitle">
      {{ page.subtitle }}
    </h1>
  </div>
</template>

<script>

export default {

  data () {
    return {
      page: {
        title: 'SecondSite',
        subtitle: 'ESP.'
      }
    }
  }
}
</script>

<style scoped>
.band {
  width: 100%;
}

</style>
