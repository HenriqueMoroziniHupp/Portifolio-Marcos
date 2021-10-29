<template>
  <nav class="nav-bar">
    <NavItem text="Serviço" to="services" />
    <NavItem text="Sobre Mim" to="about" />
    <NavItem text="Trabalhos" to="works" />
    <NavItem text="Contato" to="contact" />
  </nav>
</template>

<style lang="scss" scoped>
.nav-bar {
  width: max-content;
  display: grid;
  grid-auto-flow: column;
  gap: 2rem;
}
</style>