<template>
  <div class="screen1">
    <div class="header">
      <div class="flex">
        <div class="menu">
          <img src="../assets/Icons/menu.png" />
        </div>
        <div class="social">
          <div class="instagram"><img width="25px" src="../assets/Icons/instagram.png" /></div>
          <div class="youtube"><img width="25px" src="../assets/Icons/youtube.png" /></div>
          <div class="tiktok"><img width="25px" src="../assets/Icons/tiktok.png" /></div>
        </div>
      </div>
    </div>
    <div class="logo">
        <img src="../assets/Logos/main-logo.png" />
    </div>
    <div class="content">
        <div class="text">
            Originally, a hytte was a very basic log cabin with no running water or electricity. Plenty of these still exist especially up in the mountains and along cross-country skiing trails. But today, hytte also refers to a wooden holiday cottage.
        </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.screen1 {
  background-image: url("../assets/Images/header1.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  height: 898px;
}

.header {
  z-index: 1;
  position: fixed;
  width: 100%;
  padding: 44px 40px 0 40px;
}

.flex {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.menu {
    cursor: pointer;
}

.social {
    display: flex;
    justify-content: space-around;
    width: 40%;
}

.logo {
    padding-top: 116px;
    padding-left: 40px;
}

.content {
    position: absolute;
    width: 239px;
    height: 352px;
    top: 367.6px;
    left: 40px;
    background: rgba(255, 255, 255, 0.09);
    backdrop-filter: blur(113.272px);
    border-radius: 60.9px;
    padding: 38px 32px 19px 28px;
}

.text {
    position: relative;
    font-family: 'Steppe';
font-style: normal;
font-weight: normal;
font-size: 14.5px;
line-height: 27px;
color: #FFFFFF;
width: 100%;
height: 100%;
}

.text::after {
    position: absolute;
    width: 116px;
    content: '';
    border-top: 2px solid #fff;
    top: -20px;
    transform: rotate(150deg);

}

.text::before {
    position: absolute;
    width: 8px;
    height: 8px;
    content: '';
    background-color: #fff;
    border-radius: 50%;
    top: -54px;
    right: -110px;
}
@import url("../assets/steppe/Steppe/Web-PS/Steppe.css");
</style>