<template>
  <div class="presentation">
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officiis saepe blanditiis nihil labore neque sequi distinctio aut itaque maiores dicta laboriosam impedit dolores in ducimus exercitationem, libero ab eligendi perspiciatis?
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis atque nesciunt ipsam doloremque aperiam! Eligendi iusto, beatae quos dolorum doloribus, saepe sed maxime at commodi inventore libero, officia quis nostrum!
    </p>
    <img src="@/assets/img/presentation.svg" alt="Apresentação do iBook">
  </div>
</template>



<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}


</style>
