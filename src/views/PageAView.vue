<template>
  <div >
      <h1>PageA</h1>

      <p>{{ $route.params.id }}</p>
  </div>
</template>

<script>

export default {
  name: 'pageA',
}
</script>
