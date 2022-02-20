<template>
  <div class="book-hytte">
    <a href="#"><img src="../assets/Logos/logo.png" alt="" /></a>
    <div class="title">
      <h2>Book Hytte</h2>
      <span>Book a Hytte in Norway</span>
    </div>
    <div class="header3">
      <div class="task-bar">
          <div class="weather">
            <div class="local">
              <span><img src="../assets/Icons/pin-alt.png" /></span>
              <div class="info">
                <div class="location">Location</div>
                <div class="street">Norway</div>
              </div>
            </div>
            <span
              ><img
                src="../assets/Icons/delete-circled-outline.png"
                alt=""
                srcset=""
            /></span>
          </div>
          <div class="checkin">
              <img src="../assets/Icons/calendar.png" alt="">
              Check In
          </div>
          <div class="checkin">
              <img src="../assets/Icons/calendar.png" alt="">
              Check Out
          </div>
          <div class="guest">
              <img src="../assets/Icons/group.png" alt="">
              Guests
          </div>
          <div class="search">
              <img src="../assets/Icons/search.png" alt="" srcset="">
          </div>
      </div>
    </div>
    <div class="hytteapp">
      <h2>Hytte App</h2>
      <span>iOS & Android</span>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.book-hytte {
  display: flex;
  margin: 46px 81px 0 81px;
  position: relative;
  width: auto;
  flex-direction: column;
  align-items: center;
}

a {
  top: 0px;
  left: 0px;
  position: absolute;
}

.title {
  display: flex;
  width: 292.18px;
  height: 104.41px;
  flex-direction: column;
  align-items: center;
}

.title > h2 {
  font-family: "Steppe";
  font-weight: 400;
  font-style: normal;
  font-size: 53.42px;
  line-height: 98.02px;
  color: #3b505a;
  position: relative;
}

.title > span {
  font-family: "Steppe";
  font-weight: 400;
  font-style: normal;
  font-size: 11.33px;
  line-height: 13.6px;
  color: #3b505a;
  position: absolute;
  top: 90px;
}

.header3 {
  margin-top: 36px;
  position: relative;
  background-image: url("../assets/Images/Header3.png");
  height: 293px;
  width: 1003px;
}

.task-bar {
  display: flex;
  position: absolute;
  height: 80.94px;
  width: 100%;
  padding: 9.71px 12.95px;
  background: rgba(255, 255, 255, 0.8);
  box-shadow: 2.42805px 0px 16.187px rgba(66, 78, 96, 0.25);
  bottom: -1px;
  left: 1px;
  border-radius: 46.94px;
  justify-content: space-between;
}

.weather {
  display: flex;
  width: 259px;
  justify-content: space-between;
  align-items: center;
  padding: 0 23.47px;
  background: #FFFFFF;
box-shadow: 2.42805px 0px 16.187px rgba(66, 78, 96, 0.25);
border-radius: 58.2733px;
}

.local {
  display: flex;
  align-items: center;
}

.local > span {
  margin-right: 14.57px;
}

.location {
    font-family: Steppe;
font-style: normal;
font-weight: normal;
font-size: 11.3309px;
line-height: 14px;
color: #3B505A;
}

.street {
    font-family: Steppe;
font-style: normal;
font-weight: normal;
font-size: 14.5683px;
line-height: 17px;
color: #000000;
}

.checkin {
     display: flex;
  width: 203.96px;
  align-items: center;
  padding: 0 23.47px;
  box-shadow: 2.42805px 0px 16.187px rgba(66, 78, 96, 0.25);
border-radius: 58.2733px;
border: 1px solid #FFFFFF;
font-family: Steppe;
font-style: normal;
font-weight: normal;
font-size: 14.5683px;
line-height: 17px;
color: #3B505A;
}

.checkin img {
    margin-right: 13.76px;
}

.guest {
    display: flex;
  width: 147.3px;
  align-items: center;
  padding: 0 23.47px;
  box-shadow: 2.42805px 0px 16.187px rgba(66, 78, 96, 0.25);
border-radius: 58.2733px;
border: 1px solid #FFFFFF;
font-family: Steppe;
font-style: normal;
font-weight: normal;
font-size: 14.5683px;
line-height: 17px;
color: #3B505A;
}

.guest img {
    margin-right: 13.76px;
}

.search {
    display: flex;
    width: 139.21px;
    justify-content: center;
    align-items: center;
}

.search img {
    width: 30px;
    height: 30px;
}

.hytteapp {
    display: flex;
  width: 292.18px;
  height: 104.41px;
  flex-direction: column;
  align-items: center;
}

.hytteapp > span {
    font-family: "Steppe";
  font-weight: 400;
  font-style: normal;
  font-size: 11.33px;
  line-height: 13.6px;
  color: #3b505a;
  position: absolute;
  bottom: 0;
}

.hytteapp > h2 {
  font-family: "Steppe";
  font-weight: 400;
  font-style: normal;
  font-size: 53.42px;
  line-height: 98.02px;
  color: #3b505a;
  position: relative;
}

@media only screen and (max-width: 641px) {
  .book-hytte {
    display: none;
  }
}

@import url("../assets/steppe/Steppe/Web-PS/Steppe.css");
</style>