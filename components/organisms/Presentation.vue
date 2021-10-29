<template>
  <div class="presentation">
    <SocialNetworks />

    <img
      class="presentation-img"
      src="@/assets/images/presentation.svg"
      alt="Apresentação"
    />
  </div>
</template>

<style lang="scss" scoped>
.presentation {
  display: grid;
  position: relative;
  justify-content: center;
  .presentation-img {
    width: 80%;
    justify-self: center;
  }
  .social-networks {
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
  }
}
</style>
