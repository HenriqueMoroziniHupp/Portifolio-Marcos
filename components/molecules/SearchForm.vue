<template>
  <form class="search-form">
    <input type="search" placeholder="Buscar" />

    <button type="submit">
      <img src="@/assets/images/icons/search.svg" alt="Buscar">
    </button>
  </form>
</template>



<style lang="scss" scoped>

.search-form {
  position: relative;
  width: max-content;

  input {
    border: none;
    border-radius: 1rem;
    padding: 0.5rem 1rem;
    box-shadow: 0px 5px 5px rgba($color: black, $alpha: 0.1);
    &::placeholder {
      color: #a9b0be;
    }
  }
  button {
    position: absolute;
    right: 3px;
    top: 50%;
    transform: translateY(-50%);
    width: 30px;
    height: 30px;
    border: none;
    border-radius: 50%;
    background: #ff895f;
    display: grid;
    justify-items: center;
    align-items: center;
  }
}

</style>
