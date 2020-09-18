<template>
  <div class="nav-up">
    <div class="contain">  
      <div class="nav-text">
        <small>We are a Professional Consulting Agency</small>
        <small class="icons"><span uk-icon="icon: phone"></span>(+223) 456 0069</small>
        <small class="icons"><span uk-icon="icon: mail"></span>greywhaleconsulting@gmail.com</small>
      </div>
      <div class="nav-social">
        <a href='#' uk-icon="icon: facebook"></a>
        <a href='#' uk-icon="icon: twitter"></a>
        <a href='#' uk-icon="icon: linkedin"></a>
        <a href='#' uk-icon="icon: instagram"></a>
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
.nav-social {
  /* border: 1px solid red; */
  display: flex;
  flex: 1 1 40%;
  justify-content: flex-end;
}

.nav-social a {
  margin-left: 15px;
}

.nav-text {
  align-items: center;
  /* border: 1px solid red; */
  display: flex;
  flex: 1 1 60%;
  justify-content: space-between;
  font-family: 'Poppins', sans-serif;
}

.nav-text .icons {
  display: flex;
}

.nav-text .icons span {
  margin-right: 5px;
}

.nav-up {
  background: #212121;
  color: #fff;
  display: flex;
  justify-content: center;
  padding: 10px;
  width: 100%;
}

@media screen and (max-width: 1280px) {
  .nav-up {
    display: none;
  }
}
</style>