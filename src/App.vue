<template>
  <div>
    <MainScreen />
    <DeepLearning />
    <Feature />
    <Reviews />
    <Footer />
  </div>
</template>

<script>
import MainScreen from './components/MainScreen.vue'
import DeepLearning from './components/DeepLearning.vue'
import Feature from './components/Feature.vue'
import Reviews from './components/Reviews.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    MainScreen,
    DeepLearning,
    Feature,
    Reviews,
    Footer,
  }
}
</script>

<style>
body{
background-color: #020A18;
}
/* open-sans-300 - latin_cyrillic */
@font-face {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 300;
  src: url('./assets/css/open-sans-v20-latin_cyrillic-300.eot'); /* IE9 Compat Modes */
  src: local(''),
       url('./assets/css/open-sans-v20-latin_cyrillic-300.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('./assets/css/open-sans-v20-latin_cyrillic-300.woff2') format('woff2'), /* Super Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-300.woff') format('woff'), /* Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-300.ttf') format('truetype'), /* Safari, Android, iOS */
       url('./assets/css/open-sans-v20-latin_cyrillic-300.svg#OpenSans') format('svg'); /* Legacy iOS */
}
/* open-sans-regular - latin_cyrillic */
@font-face {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 400;
  src: url('./assets/css/open-sans-v20-latin_cyrillic-regular.eot'); /* IE9 Compat Modes */
  src: local(''),
       url('./assets/css/open-sans-v20-latin_cyrillic-regular.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('./assets/css/open-sans-v20-latin_cyrillic-regular.woff2') format('woff2'), /* Super Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-regular.woff') format('woff'), /* Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-regular.ttf') format('truetype'), /* Safari, Android, iOS */
       url('./assets/css/open-sans-v20-latin_cyrillic-regular.svg#OpenSans') format('svg'); /* Legacy iOS */
}
/* open-sans-600 - latin_cyrillic */
@font-face {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 600;
  src: url('./assets/css/open-sans-v20-latin_cyrillic-600.eot'); /* IE9 Compat Modes */
  src: local(''),
       url('./assets/css/open-sans-v20-latin_cyrillic-600.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('./assets/css/open-sans-v20-latin_cyrillic-600.woff2') format('woff2'), /* Super Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-600.woff') format('woff'), /* Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-600.ttf') format('truetype'), /* Safari, Android, iOS */
       url('./assets/css/open-sans-v20-latin_cyrillic-600.svg#OpenSans') format('svg'); /* Legacy iOS */
}
/* open-sans-700 - latin_cyrillic */
@font-face {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 700;
  src: url('./assets/css/open-sans-v20-latin_cyrillic-700.eot'); /* IE9 Compat Modes */
  src: local(''),
       url('./assets/css/open-sans-v20-latin_cyrillic-700.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('./assets/css/open-sans-v20-latin_cyrillic-700.woff2') format('woff2'), /* Super Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-700.woff') format('woff'), /* Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-700.ttf') format('truetype'), /* Safari, Android, iOS */
       url('./assets/css/open-sans-v20-latin_cyrillic-700.svg#OpenSans') format('svg'); /* Legacy iOS */
}
/* open-sans-800 - latin_cyrillic */
@font-face {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 800;
  src: url('./assets/css/open-sans-v20-latin_cyrillic-800.eot'); /* IE9 Compat Modes */
  src: local(''),
       url('./assets/css/open-sans-v20-latin_cyrillic-800.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('./assets/css/open-sans-v20-latin_cyrillic-800.woff2') format('woff2'), /* Super Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-800.woff') format('woff'), /* Modern Browsers */
       url('./assets/css/open-sans-v20-latin_cyrillic-800.ttf') format('truetype'), /* Safari, Android, iOS */
       url('./assets/css/open-sans-v20-latin_cyrillic-800.svg#OpenSans') format('svg'); /* Legacy iOS */
}
</style>
