<template>
  <div class="layout">
    <div class="container-main">
      <Navbar />
      <Nuxt />
    </div>
    <div>
      <Footer />
    </div>
  </div>
</template>

<style lang="css" scoped>
.layout{
  display: flex;
  flex-direction: column;
}
.container-main{
  display: flex;
  flex-direction: row-reverse;
}
</style>
<style>
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
</style>