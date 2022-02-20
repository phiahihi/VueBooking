<template>
        <div class="option">
    <a href="#"><img src="../assets/Logos/logo.png" alt="" /></a>
    <div class="title">
      <h2>Options</h2>
      <span>217 perfect options</span>
    </div>
    <div class="list">
      <div class="option-style">
        <img src="../assets/Images/Header2-1.png" />
        <div class="info">
          <div class="content">
            <div class="location1">
              NEST Bunnefjorden - Mirrored Glass Cabin
            </div>
            <div class="location2">Frogn, Viken, Norway</div>
          </div>
          <div class="price"><span>$424</span>/night</div>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/Icons/group.png" width="8.09px" />
            4 guests
          </span>
          <span>
            <img src="../assets/Icons/home.png" width="8.09px" />
            2 bedrooms
          </span>
        </div>
      </div>
      <div class="option-style">
        <img src="../assets/Images/Header2-2.png" />
        <div class="info">
          <div class="content">
            <div class="location1">Sjulstad, Numedalslågen</div>
            <div class="location2">Larvik, Vestfold, Norway</div>
          </div>
          <div class="price"><span>$367</span>/night</div>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/Icons/group.png" width="8.09px" />
            2 guests
          </span>
          <span>
            <img src="../assets/Icons/home.png" width="8.09px" />
            1 bedrooms
          </span>
        </div>
      </div>
      <div class="option-style">
        <img src="../assets/Images/Header2-3.png" />
        <div class="info">
          <div class="content">
            <div class="location1">
              Relax, rejuvenate and unplug in Birdbox Tokke
            </div>
            <div class="location2">Tokke, Vestfold og Telemark, Norway</div>
          </div>
          <div class="price"><span>$344</span>/night</div>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/Icons/group.png" width="8.09px" />
            2 guests
          </span>
          <span>
            <img src="../assets/Icons/home.png" width="8.09px" />
            1 bedrooms
          </span>
        </div>
      </div>
      <div class="option-style">
        <img src="../assets/Images/Header2-4.png" />
        <div class="info">
          <div class="content">
            <div class="location1">
              The WonderInn Riverside Retreat - Cabin Koti
            </div>
            <div class="location2">Nes, Viken, Norway</div>
          </div>
          <div class="price"><span>$388</span>/night</div>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/Icons/group.png" width="8.09px" />
            2 guests
          </span>
          <span>
            <img src="../assets/Icons/home.png" width="8.09px" />
            1 bedrooms
          </span>
        </div>
      </div>
      <div class="option-style">
        <img src="../assets/Images/Header2-5.png" />
        <div class="info">
          <div class="content">
            <div class="location1">
              Breathtaking Mountain views in cozy Birdbox
            </div>
            <div class="location2">Gaular, Sogn og Fjordane, Norway</div>
          </div>
          <div class="price"><span>$391</span>/night</div>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/Icons/group.png" width="8.09px" />
            2 guests
          </span>
          <span>
            <img src="../assets/Icons/home.png" width="8.09px" />
            1 bedrooms
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    components: {
    }
};
</script>

<style scoped>
.option {
  display: flex;
  margin: 46px 81px 0 81px;
  justify-content: center;
  position: relative;
  width: auto;
  height: 680px;
}

a {
  top: 0px;
  left: 0px;
  position: absolute;
}

.title {
  display: flex;
  width: 205.58px;
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

.list {
  display: flex;
  position: absolute;
  top: 183.72px;
  justify-content: space-between;
}

.option-style {
  width: 20%;
}

.info {
  display: flex;
  margin: 2px 10px 0 0;
  height: 72.62px;
}

.location1 {
  font-family: "Steppe";
  font-weight: 400;
  font-style: normal;
  font-size: 13px;
  line-height: 16px;
  color: #000000;
}

.location2 {
  font-family: "Steppe";
  font-style: normal;
  font-weight: normal;
  font-size: 10px;
  line-height: 14px;
  color: #3b505a;
}

.price {
  font-family: Steppe;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 14px;
  color: #3b505a;
  border: 1px solid #34b7b7;
  padding: 5px;
  height: 28px;
  border-radius: 3px;
}

.price > span {
  font-family: Steppe;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 17px;
  color: #000000;
}

.icon {
  display: flex;
  justify-content: flex-start;
  margin-top: 5px;
}

.icon > span {
  font-family: Steppe;
  font-style: normal;
  font-weight: normal;
  font-size: 9px;
  line-height: 10px;
  background-color: #34b7b7;
  color: #ffffff;
  border-radius: 6px;
  padding: 0px 7px;
}

.icon > span:last-child {
  margin-left: 3px;
}

@media only screen and (max-width: 641px) {
  .option {
    display: none;
  }
}

@import url("../assets/steppe/Steppe/Web-PS/Steppe.css");
</style>