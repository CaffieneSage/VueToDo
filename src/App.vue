<template>
  <div>
    <div>
      <RouterLink :to="{name: 'home'}">HomePage</RouterLink>
    </div>

    <div>
      <RouterLink :to="{name: 'about'}">AboutPage</RouterLink>
    </div>

    <div>
      <RouterLink :to="{name: 'articles', params: {id: 1} }">Article1</RouterLink>
    </div>
  </div>
 <RouterView />
</template>

<script>


export default {
  name: 'App',
  
}
</script>
