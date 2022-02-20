<template>
  <div class="screen2">
    <div class="title">
      <div class="title-top">Book Hytte</div>
      <div class="title-bottom">Book a Hytte in Norway</div>
    </div>
    <div class="content">
      <div class="cover">
        <div class="location">
          <div class="icon">
            <img width="22px" src="../assets/Icons/pin-alt.png" />
          </div>
          <div class="text">
            <div class="text-top">Location</div>
            <div class="text-bottom">Norway</div>
          </div>
        </div>
        <div class="location" id="location-plus">
          <div class="location-right">
            <div class="icon">
              <img width="22px" src="../assets/Icons/calendar.png" />
            </div>
            <div class="text">
              <div class="text-top">Checkin</div>
              <div class="text-bottom">Feb. 11</div>
            </div>
          </div>
          <div class="location-left">
            <img
              width="22px"
              src="../assets/Icons/delete-circled-outline.png"
            />
          </div>
        </div>
      </div>
    </div>
    <div class="calendar">
      <div class="calendar-top">
        <img src="../assets/Icons/nav-arrow-right.svg" />
        <span>11 Feb 2021</span>
        <img class="arrow-right" src="../assets/Icons/nav-arrow-right.svg" />
      </div>
      <div class="calendar-bottom">
        <table>
          <tr>
            <th>s</th>
            <th>m</th>
            <th>t</th>
            <th>w</th>
            <th>t</th>
            <th>f</th>
            <th>s</th>
          </tr>
          <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
          </tr>
          <tr>
            <td>8</td>
            <td>9</td>
            <td>10</td>
            <td class="day11">11</td>
            <td>12</td>
            <td>13</td>
            <td>14</td>
          </tr>
          <tr>
            <td>15</td>
            <td>16</td>
            <td>17</td>
            <td>18</td>
            <td>19</td>
            <td>20</td>
            <td>21</td>
          </tr>
          <tr>
            <td>22</td>
            <td>23</td>
            <td>24</td>
            <td>25</td>
            <td>26</td>
            <td>27</td>
            <td>28</td>
          </tr>
          <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
          </tr>
        </table>
      </div>
    </div>
    <div class="duong"></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.screen2 {
  margin: 155px 18.27px 0 18.27px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.title {
  display: flex;
  align-items: center;
  flex-direction: column;
}

.title-top {
  font-family: "Steppe";
  font-style: normal;
  font-weight: normal;
  font-size: 21.9236px;
  line-height: 26px;
  color: #3b505a;
}

.title-bottom {
  font-family: "Steppe";
  font-style: normal;
  font-weight: normal;
  font-size: 17.0517px;
  line-height: 20px;
  margin-top: 13px;
  color: #3b505a;
}

.content {
  background-image: url("../assets/Images/img.png");
  background-size: cover;
  width: 100%;
  height: 334px;
  margin-top: 14.62px;
  border-radius: 60.9px;
}

.cover {
  width: 100%;
  position: relative;
  display: flex;
  align-items: center;
  flex-direction: column;
  margin-top: 121.5px;
  padding: 0px 14.62px;
  background: rgba(255, 255, 255, 0.8);
  box-shadow: 3.65394px 0px 24.3596px rgba(66, 78, 96, 0.25);
  backdrop-filter: blur(113.272px);
  border-start-start-radius: 70.6429px;
  border-start-end-radius: 70.6429px;
  border-top: 1.22px solid #ffffff;
  border-left: 1.22px solid #ffffff;
  border-right: 1.22px solid #ffffff;
}

.location {
  padding-left: 52.37px;
  align-items: center;
  display: flex;
  justify-content: flex-start;
  width: 100%;
  height: 92.57px;
  margin-top: 14.62px;
  background: rgba(255, 255, 255, 0.2);
  box-shadow: 3.65394px 0px 24.3596px rgba(66, 78, 96, 0.25);
  border-radius: 87.6946px;
  border: 1.22px solid #ffffff;
}

#location-plus {
  margin-top: 12px;
  justify-content: space-between;
  background: #ffff;
  box-shadow: 3.65394px 0px 24.3596px rgba(66, 78, 96, 0.25);
  backdrop-filter: blur(36.5394px);
  border-radius: 37.7574px;
}

.icon {
  margin-right: 22px;
}

.text-top {
  font-family: "Steppe";
  font-style: normal;
  font-weight: normal;
  font-size: 17.0517px;
  line-height: 20px;
  color: #3b505a;
}

.text-bottom {
  font-family: "Steppe";
  font-style: normal;
  font-weight: normal;
  font-size: 21.9236px;
  line-height: 26px;
  color: #000000;
}

.location-right {
  display: flex;
  align-items: center;
}

.location-left {
  position: absolute;
  right: 36.54px;
}

.calendar {
  margin-top: 4.2px;
  width: 100%;
  height: 369px;
  background: rgba(255, 255, 255, 0.9);
  padding: 0 29.64px;
  /* background: black; */
  box-shadow: 0px 4.87192px 15.8337px rgba(125, 154, 171, 0.25);
  backdrop-filter: blur(113.272px);
  border-radius: 37.7574px;
}

.calendar-top {
  margin-top: 25.72px;
  display: flex;
  justify-content: space-between;
}

span {
  font-family: Steppe;
  font-style: normal;
  font-weight: normal;
  font-size: 21.9236px;
  line-height: 26px;
  color: #3b505a;
}

.arrow-right {
  transform: rotate(180deg);
}

.calendar-bottom {
  width: 100%;
  margin-top: 34px;
  height: 243.6px;
}

table {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

tr {
  display: flex;
  justify-content: space-between;
}

th {
  font-family: Steppe;
  font-style: normal;
  font-weight: normal;
  font-size: 14.6158px;
  line-height: 18px;
  color: #3b505a;
}

td {
  font-family: Steppe;
  font-style: normal;
  font-weight: normal;
  font-size: 17.0517px;
  line-height: 20px;
  color: #3b505a;
}

.day11 {
  position: relative;
  color: #ffffff;
}

.day11::after {
  content: "11";
  text-align: center;
  line-height: 42.63px;
  position: absolute;
  width: 42.63px;
  height: 42.63px;
  background: #34b7b7;
  border-radius: 50%;
  top: -50%;
  left: -110%;
}

.duong {
  width: 163.21px;
  height: 6.09px;
  left: calc(50% - 163.21px / 2 - 0.37px);
  bottom: 10.16px;
  background: #ececec;
  border-radius: 121.798px;
  z-index: 1;
  margin-top: 38.76px;
  margin-bottom: 10.15px;
}
@import url("../assets/steppe/Steppe/Web-PS/Steppe.css");
</style>