<template>
  <div class="nav-down">
    <div class="contain">
      <div class="nav-brand">
        <p>Greywhale</p>
      </div>
      <div class="nav-links">
        <nuxt-link class="item" to='/about'>About</nuxt-link>
        <nuxt-link class="item" to='#packages'>Packages</nuxt-link>
        <nuxt-link class="item" to='#contact'>Contact</nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
/* font-family: 'Berkshire Swash', cursive; */
/* font-family: 'Poppins', sans-serif; */
.nav-links {
  /* border: 1px solid red; */
  display: flex;
  flex: 1 1 40%;
  justify-content: flex-end;
  margin-top: 5px;
}

.nav-links .item {
  color: #212121;
  font-size: 14px;
  margin-left: 15px;
  text-decoration: none;
  transition: color 0.5s;
}

.nav-links .item:hover {
  color: #b804ff;
}

.nav-social a {
  margin-left: 15px;
}

.nav-brand {
  color: #8703bb;
  display: flex;
  flex: 1 1 60%;
  font-size: 22px;
  height: 30px;
  justify-content: space-between;
  margin-bottom: 5px !important;
}

.nav-down {
  align-items: center;
  background: #fff;
  color: #212121;
  display: flex;
  font-family: 'Poppins', sans-serif;
  height: 70px;
  justify-content: center;
  padding: 15px 0;
  width: 100% !important;
}

@media screen and (max-width: 1280px) {

}
</style>