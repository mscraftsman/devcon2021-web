<template>
  <div class="text__container">
    <div class="container__fw">
      <div class="title__section">
        <div class="sub-text">Innovation. Technology. Community.</div>
        <h2 class="title">The Developers Conference 2021</h2>
        <div class="content">
          <p>
           It is with great regret that we announce that despite being a COVID free island 
           we have no choice but to postpone the Developers Conference 2021 following 
           recent updates regarding the COVID-19 situation.
          </p>
          <p>
           The media recently announced that under the Quarantine Act 2020 only approved 
           aircrafts and ships would be able to enter the Mauritian territories and the
           imposed quarantine period for all travellers would be extended to the 31st 
           March 2021. The travel restrictions and quarantine procedures imposed by the 
           Government make it difficult for our international sponsors & speakers to be 
           present.
          </p>
          <p>
           Unfortunately, we do not yet have set dates for when the Developers Conference 
           will take place, but rest reassured that the event is in no way cancelled just 
           reported to an unknown date for now. Our team is following the situation 
           closely and as soon as an agreed date is set, we will be informing you of our 
           decision.
          </p>
          <p>
           We would like to thank our partners once again for bearing with us and 
           supporting us during these difficult times.
          </p>
          <p>
           However, do stay tuned because we have some interesting news coming up soon! 😉
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
