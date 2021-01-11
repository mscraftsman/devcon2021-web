<template>
  <div class="container__fw page">
    <h1>Community</h1>
    <div class="content">
      <p>
        All attendees, speakers, sponsors and volunteers at our conference are
        required to agree with the following code of conduct. Organisers will
        enforce this code throughout the event. We expect cooperation from all
        participants to help ensure a safe environment for everybody.
      </p>

      <h2>Mauritius Software Craftsmanship Community</h2>
      <img
        src="https://www.mscc.mu/content/images/2018/12/be-excellent-to-each-other.jpg"
        alt="Be excellent to each other"
      />
      <p>You have our contact details in the emails we've sent.</p>

      <h2>Front-end Coders - Mauritius</h2>
      <p>
        Our conference is dedicated to providing a harassment-free conference
        experience for everyone, regardless of gender, gender identity and
        expression, age, sexual orientation, disability, physical appearance,
        body size, race, ethnicity, religion (or lack thereof), or technology
        choices. We do not tolerate harassment of conference participants in any
        form. Sexual language and imagery is not appropriate for any conference
        venue, including talks, workshops, parties, Twitter and other online
        media. Conference participants violating these rules may be sanctioned
        or expelled from the conference at the discretion of the conference
        organisers.
      </p>

      <h2>Linux User Group of Mauritius</h2>
      <p>
        The Linux User of Mauritius or as commonly called <a href="https://lugm.org">
        LUGM</a>, is perhaps the oldest user group of the island. It re-groups Linux
        users from different corners of the island. Their main activities are 
        organising Linux installation festivals and helping users with common *nix 
        troubleshooting. LUGM members often speak at local events about open source 
        software.
      </p>

      <h2>openSUSE Mauritius</h2>
      <p>
        A group of openSUSE users that manage the <a href="https://opensuse.mu">
        opensuse.mu</a> blog. They mainly write about tweaks and fixes for the 
        different versions of openSUSE. They also bring news from the openSUSE 
        community. Feel free to wave at the green geekos during the conference, 
        you may identify them with their chameleon t-shirts or with gecko plushes
        hanging around the conference venue.
      </p>

      <h2>Ubuntu Mauritius</h2>
      <p>
        The Ubuntu LoCo team is undergoing a revival after being dormant for some
        years. Ubuntu users are welcomed to <a href="https://loco.ubuntu.com/teams/ubuntu-mu/">
        join the group</a> on the Ubuntu loco team portal.
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.page {
  padding: 40px 10px;

  h1 {
    text-align: center;
    font-family: var(--font-bangers);
    font-size: 60px;
    letter-spacing: 2px;
  }

  h2 {
    font-family: var(--font-bangers);
    letter-spacing: 1px;
    font-size: 40px;
  }

  img {
    margin: 0 auto;
    max-width: 600px;
    width: 100%;
    display: block;
  }

  p {
    font-weight: 300;
    line-height: 28px;
    font-size: 18px;

    a {
      color: var(--titanium);
    }
  }
}
</style>
