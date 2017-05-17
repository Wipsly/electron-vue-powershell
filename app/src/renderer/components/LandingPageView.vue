<template>
  <div>
    <navbar></navbar>
    <h1>Welcome.</h1>
    <current-page></current-page>
    <versions></versions>
    <links></links>
  </div>
</template>

<script>
  import Navbar from './LandingPageView/Navbar'
  import CurrentPage from './LandingPageView/CurrentPage'
  import Links from './LandingPageView/Links'
  import Versions from './LandingPageView/Versions'
  export default {
    components: {
      Navbar,
      CurrentPage,
      Links,
      Versions
    },
    name: 'landing-page'
  }
</script>

