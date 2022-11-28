<template>
  <div class="about">
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
    <img src="src/assets/placeholder.png" alt="" />
  </div>
</template>

<style lang="scss">
.about {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  border: solid 1px lightgreen;
  border-radius: 4px;
  padding: 1rem;

  grid-gap: 15px;
  img {
    border: solid 1px red;
    width: 100%;
  }
}
</style>
