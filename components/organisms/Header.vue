<template>
  <header class="header">
    <Logo/>
    <NavBar/>
    <SearchForm/>

  </header>
</template>


<style lang="scss" scoped>
.header {
  width: 100%;
  display: grid;
  grid-template-columns: 160px repeat(2, auto);
  align-items: center;
  justify-content: space-between;
  
}
</style>