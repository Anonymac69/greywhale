<template>
  <div>
    <nav-up/>
    <nav-down/>
    <banner/>
    <packages/>
  </div>
</template>

<script>
export default {}

</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.contain {
  margin: 0 auto !important;
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  text-align: center;
  width: 1280px;
}

.contain-alt {
  align-items: center;
  display: flex;
  flex-direction: column;
  height: 100%;
  justify-content: center;
  margin: 0 auto;
  text-align: center;
  max-width: 1280px;
}
</style>
