<template>
  <div class="text__container">
    <div class="container__fw">
      <div class="title__section">
        <div class="sub-text">Innovation. Technology. Community.</div>
        <h2 class="title">The Developers Conference 2021</h2>
        <div class="content">
          <p>
            As you are aware, the Developers Conference 2020 was revamped 
            to a Virtual Developers Conference 2020 due to the COVID-19 pandemic 
            that hit the whole world. We are blessed that the pandemic did not 
            have as much of an impact on the IT industry as compared to other work 
            sectors. Due to various lock downs, travel bans or quarantine periods,
            we had no choice than to postpone the annual Developers Conference 2020 
            to March 2021.
          </p>
          <p>
            Being the largest IT Community in Mauritius, we are so passionate about 
            the tech world that doing the Developers Conference is a must. With the 
            Virtual Conference, we missed the human touch behind the whole event 
            where people exchange and interact with each other. Nonetheless your 
            safety being our main concern and depending on the latest updates 
            precautionary measures will be put in practice.
          </p>
          <p>
            Mark your calendar, save the dates and join us for the Developers Conference 
            2021 with multiple sessions over 3 whole days of technical geekery as well 
            as evening entertainments. Come and meet our Partners for recruitment and 
            internship at their different booths. And let's have fun!
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
    text-align: left;

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
