<template>
  <div>
    <!-- note about nav ... is  -->
    <!-- 1 home head section   -->
    <!-- CORGWYN REHABILITATION SANCTUARY -->
    <!-- A LIFELINE FOR LAST-CHANCE CORGIS -->
    <!-- DONATE NOW MEET THE DOGS -->
    <!-- home head section   -->

    <!-- 2 learn more section  -->
    <!-- Corgwyn Rehabilitation Sanctuary -->
    <!-- Our Mission -->
    <!-- To assist rescued corgis with rehabilitation and retraining to enable them, when possible, to find forever adoptive homes, and provide sanctuary for those who need long term care. -->
    <!-- learn more -->

    <!-- 3 SANCTUARY MEMBERS/HELP SUPPORT CRS cards -->
    <section class="w-screen dog_image 	">
      <div class="grad_box center_box">
        <h1 class="header_text">CORGWYN REHABILITATION SANCTUARY</h1>
        <p class="sub_header_text">A LIFELINE FOR LAST-CHANCE CORGIS</p>
      </div>
    </section>
    <h1 class="grid_intro">Learn More</h1>

    <div class="home_grid" >

      <div class="child_grid">
        <div class="first_grid_container">
          <p class="first_grid_container_intro">Corgwyn Rehabilitaion Sancturary</p>
          <div class="our_mission_container">
            <h1 class="our_mission_text">Our Mission</h1>
            <div class="home_divider"></div>
          </div>
          <div class="first_grid_last_item">
            <p>
              To assist rescued corgis with rehabilitation and retraining to enable them, when possible,
              to find forever adoptive homes, and provide sanctuary for those who need long term care.
            </p>
          </div>
        </div>
      </div>

       <div class="second_content_container">
        <div>
          <img class="grid_image" src="../static/corgis-home.jpeg" alt="">
        </div>
        <div>
          <h2 class="second_content_header">SANCTUARY MEMBERS</h2>
          <p>Meet our current CRS sanctuary members, read their stories and history, and sponsor a corgi!</p>
        </div>
        <div class="button_container">
          <button class="meet_button">Meet the Corgis </button>
          <img src="../static/right-arrow.png" alt="arrow">
        </div>
      </div>
<!-- ============================================ -->
    <div class="second_content_container">
        <div>
          <img class="grid_image" src="../static/corgis-home.jpeg" alt="">
        </div>
        <div>
          <h2 class="second_content_header">HELP SUPPORT CRS</h2>
          <p>Meet our current CRS sanctuary members, read their stories and history, and sponsor a corgi!</p>
        </div>
        <div class="button_container">
          <button class="meet_button">Donate Now</button>
          <img src="../static/right-arrow.png" alt="arrow">
        </div>
      </div>
    </div>

    <!-- end of home page hero image and inro columns -->
    <!-- ============================================= -->
    <HomeCta />
    <MeetCorgis />
    <!-- SANCTUARY MEMBERS/HELP SUPPORT CRS cards -->

    <!-- 4 SUPPORT CRS/HOW YOU CAN HELP section  -->
    <!-- NOTE: use flex not grid -->
    <!-- donate -->
    <!-- sponsor -->
    <!-- support -->
    <!-- SUPPORT CRS  -->

    <!-- 5 meet the corgis  40 mont bold -->
    <!-- carosel of current corgis -->
    <!-- meet the corgis -->
  </div>
</template>

<script>
export default {}
</script>
<style scoped>
h1,h2,h3,h4 {
  font-family: 'Montserrat', sans-serif;
}
p {
   font-family: 'Open Sans', sans-serif;
   font-weight: 100;
}
.button_container {

}
.meet_button {
  font-family: 'Montserrat', sans-serif;
  color: black;
  font-weight: bold;
  font-size: 13px;
  margin-top: 1em;
  margin-bottom: 1em;
}
.para_text {
  font-weight: 100;
}
.second_content_header {
  font-weight: bold;
  margin-top: 1em;
  margin-bottom: 1em;
}
.second_content_container {
  display : flex;
  flex-direction: column;
}
.grid_image {
  max-height: 150px;
  width: 100%;
  object-fit:  cover;
}
.our_mission_text {
  font-family: 'Montserrat', sans-serif;
  font-size: 40px;
  font-weight: bold;
  margin-top: .3em;
  margin-bottom: .3em;

}
.home_divider {
  width: 50px;
  height: 3px;
  border-radius: 10%;
  background:#a5a3a3;
  margin-bottom: 1.2em;
}
.grid_intro {
  text-align: center;
  padding-top: 2em;
  padding-bottom: 2em;
  color: #6EC1E4;
  font-size: 27px;
  font-weight: bold;
  text-transform: uppercase;
}
.home_grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 50px;
  height: 400px;
  margin-left: 10%;
  margin-right: 10%;
}
.child_grid {
  display: flex;
  justify-content: center;
}
.header_text {
  color: white;
  font-size: 70px;
  font-family: 'Open Sans', sans-serif;
  font-weight: bold;
}
.sub_header_text {
  font-family: 'Montserrat', sans-serif;
  font-size: 42px;
  color: #a5a3a3;
  font-weight: normal;
}
  .grad_box {
    position: absolute;
    background: #00000057;
    height: 560px;
    width: 100%;
    padding-left: 10%;
    padding-right: 10%;
  }
  .center_box {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  .dog_image {
    position: static;
    height: 560px;
    background-image: url('../static/corgis-home.jpeg');
    -o-object-fit: cover;
    object-fit: fill;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
  }
  .grad {
    background: -webkit-linear-gradient(to right, #414345, #232526);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to right, #414345, #232526); 
  }
  
  /* media query  */
  /* first one is dog image class 360 by 640 */
  @media screen and (max-width: 1100px) {
    .sub_header_text {
      font-weight: normal;
      color: white;
    }
  }
  @media only screen and (max-width: 600px) {
    .home_grid {
      padding-bottom: 4em;
    }
  .dog_image {
    max-height: 250px;
  }
  .grad_box {
    max-height: 250px;
  }

  .header_text {
    font-size: 24px;
  }
  .sub_header_text {
    font-size: 16px;
    font-weight: normal;
    padding-top: 1em;
    color: white;
  }

  .grad_box {
     padding-left: 2%;
     padding-right: 2%;
  }
  /* home grid */
  .home_grid {
   display: flex;
   flex-direction: column;
   height: auto;
  }
}

</style>

