<template>
  <div>
    <Header />
    <router-view />
  </div>
</template>
<script>
import Header from './components/header/header'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>
