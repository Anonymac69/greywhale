<template>
  <div class="card-wrap">
    
    <div id="card">
      <img class="card-img" src="../assets/images/meet.jpg" alt="">
      <p class="card-title">Financial Advisors</p>
      <small class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Animi, deleniti.</small>
    </div>
    
    <div id="card">
      <img class="card-img" src="../assets/images/agree.jpg" alt="">
      <p class="card-title">Marketing Strategists</p>
      <small class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Animi, deleniti.</small>
    </div>
    
    <div id="card">
      <img class="card-img" src="../assets/images/meet.jpg" alt="">
      <p class="card-title">Financial Consultancy</p>
      <small class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Animi, deleniti.</small>
    </div>

  </div>
</template>

<script>
export default {
  data() {
    return {
      title: [
        'Financial Consultancy',
        'Marketing & Advertising',
        'Sales Conversion'
      ],
      images: [
        '@assets/images/snow.jpg',
        '@assets/images/white01.jpg',
        '@assets/images/white02.jpg'
      ],
      text: [
        'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Animi, deleniti.',
        'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Animi, deleniti.',
        'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Animi, deleniti.'
      ]
    }
  }
}
</script>

<style>
/* font-family: 'Berkshire Swash', cursive; */
/* font-family: 'Poppins', sans-serif; */

#card {
  border: 5px solid #fff;
  box-shadow: 0 3px 6px #e0e0e0;
  height: 100%;
  margin: 50px 10px;
  width: 250px;
}

.card-img {
  border-radius: 3px;
}

.card-title {
  color: #8703bb;
  font-size: 18px;
  font-weight: 500;
  margin: 7px auto 3px auto;
}

.card-text {
font-family: 'Poppins', sans-serif;
font-size: 12px;
}

.card-wrap {
  display: flex;
  justify-content: space-between;
}
</style>