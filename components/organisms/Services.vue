<template>
  <div class="services">
    <Service
      title="Front-End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque beatae tenetur blanditiis maiores. Consequatur quisquam nobis suscipit praesentium hic illo possimus quasi, at sequi cumque officia itaque aliquam est nam!"
    />
    <Service
      title="Back-End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque beatae tenetur blanditiis maiores. Consequatur quisquam nobis suscipit praesentium hic illo possimus quasi, at sequi cumque officia itaque aliquam est nam!"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque beatae tenetur blanditiis maiores. Consequatur quisquam nobis suscipit praesentium hic illo possimus quasi, at sequi cumque officia itaque aliquam est nam!"
    />
  </div>
</template>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 5rem;
}

</style>
