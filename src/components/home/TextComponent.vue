<template>
  <div class="text__container">
    <div class="container__fw">
      <div class="title__section">
        <div class="sub-text">Innovation. Technology. Community.</div>
        <h2 class="title">The Developers Conference 2022</h2>
        <div class="content">
          <p>
           Text coming up
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.text__container {
  padding: 60px 0 200px;
  text-align: left;
  // background: url("/cloud-right.svg");
  // background-position: bottom right;
  // background-repeat: no-repeat;

  // .sub-text {
  //   text-align: center;
  // }

  // .title {
  //   text-align: center;
  //   font-size: 45px;
  // }

  .content {
    text-align: center;

    p {
      font-weight: 300;
      line-height: 32px;
      font-size: 18px;
    }
  }
}

@media (max-width: 1024px) {
  .text__container {
    padding: 60px 0 100px;
  }
}

@media (max-width: 768px) {
  .text__container {
    background-size: 200px;
  }

  .title__section {
    .sub-text {
      font-size: 16px;
    }
    .title {
      font-size: 40px;
    }
  }
}
</style>
