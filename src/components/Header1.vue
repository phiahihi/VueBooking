<template>
  <div class="image">
    <div class="header">
      <div class="header-left">
        <ul>
          <li>Hytte</li>
          <li>Options</li>
          <li>Book</li>
          <li>App</li>
        </ul>
      </div>
      <div class="header-right">
        <ul class="social">
          <li><img src="../assets/Icons/instagram.png" /></li>
          <li><img src="../assets/Icons/youtube.png" /></li>
          <li><img src="../assets/Icons/tiktok.png" /></li>
        </ul>
      </div>
    </div>
    <h1>
      <a href="#"
        ><img
          src="../assets/Logos/main-logo.png"
          alt=""
          width="170.77px"
          height="107.52px"
      /></a>
    </h1>
    <div class="logo">
      Originally, a hytte was a very basic log cabin with no running water or
      electricity. Plenty of these still exist especially up in the mountains
      and along cross-country skiing trails. But today, hytte also refers to a
      wooden holiday cottage.
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.image {
  background-image: url("../assets/Images/header1.png");
  background-position: center;
  width: 100%;
  height: 727px;
  margin: auto;
  border-start-start-radius: 40.47px;
  border-start-end-radius: 40.47px;
  position: relative;
}

.header {
  z-index: 1;
  display: flex;
  align-items: center;
  width: 391.73px;
  height: 36.42px;
  right: 20px;
  margin: auto;
  justify-content: space-between;
  padding-top: 25.9px;
  margin-right: 80.47px;
}

.header-left {
  display: block;
  width: 275.18px;
}

.header-left > ul {
  display: flex;
  justify-content: space-between;
}

.header-left > ul > li {
  padding: 11px 16px;
  border-radius: 48.56px;
  background: rgba(255, 255, 255, 0.1);
  font-family: "Steppe";
  font-style: normal;
  font-weight: normal;
  font-size: 11.3309px;
  line-height: 14px;
  color: #3b505a;
}

.header-right {
  width: 84.17px;
}

.header-right > ul {
  align-items: center;
  justify-content: space-between;
}

.social > img {
  width: 19.42px;
}

h1 {
  top: 80.94px;
  left: 80.9px;
  position: absolute;
}

.logo {
  font-family: "Steppe";
  font-weight: 400;
  font-style: normal;
  font-size: 9.71px;
  line-height: 17.92px;
  color: #ffffff;
  width: 158.63px;
  height: 245.23px;
  position: absolute;
  left: 140.83px;
  top: 397.39px;
  border-radius: 40.47px;
  background: rgba(255, 255, 255, 0.09);
  padding: 25px 14.5px 25px 25px;
}

@import url("../assets/steppe/Steppe/Web-PS/Steppe.css");
</style>