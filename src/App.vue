<template>
    <m-header></m-header>
    <tab></tab>
    <router-view></router-view>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/header/header'
import Tab from '@/components/tab/tab'

export default {
  name: 'Home',
  components: {
    MHeader: Header,
    Tab
  }
}
</script>
