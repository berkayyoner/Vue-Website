<template>
  <div class="bg-image">
    <nav-bar class="navbar"/>
    <div class="content">
      <div class="first-block">
        <h1 class="logo" style="font-size: 90px">Haymana Turizm</h1>
        <br/><br/><br/><br/><br/><br/>
      </div>
      <div class="second-block">
        <span class="black-box">
          <span>
            <img src="../assets/home-page/1.png" alt="first-photo" class="first-photo" width="400" height="400"/>
            <h1>
              <a>Geniş Servis Alanı</a>
            </h1>
            <a class="first-text">
              AlphaHealthyLife.ga , we are committed to helping<br/>
              live more healthily by providing quality, science-<br/>
              based health and nutrition advice, and over 4000<br/>
              nutritionist-approved recipes you can trust are good<br/>
              for you.<br/>
            </a>
          </span>
        </span>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from '../components/NavBar.vue'

export default {
  name: 'HomeView',
  props: {
  },
  components: {
    NavBar,
}
}
</script>

<style scoped>
.bg-image {
  background-image: url("../assets/home-page/HaymanaTurizm-home-background-photo.png");
  background-color: black;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: 100% 100%;
  margin: -8px;
  width: 101%;
  height: 100%;
}
.first-block {
  background-image: linear-gradient(to top, rgb(75, 75, 75), transparent);
}
.second-block {
  background-color: rgb(75, 75, 75);
  text-align: left;
  padding-top: 1px;
}
.black-box {
  background-color: rgb(54, 54, 54);
  margin: 100px;
  margin-right: 130px;
  margin-top: 200px;
}
.first-photo {
  margin: 5%;
  margin-left: 100px;
  float: left;
  margin-right: 250px;
  border-radius: 50%;
}
.first-text {
  margin-bottom: 500px;
  float: right;
}
h1 {
  padding: 40px;
  padding-top: 150px;
}
.btn-border {
  color: white;
  border-style: solid;
  border-color: white;
  border-width: 2px;
  padding: 15px;
  white-space: pre-wrap;
  text-decoration: none;
}
.btn-border:hover {
  background-color: white;
  color: black;
  transition: 1s;
}

.logo {
  font-family: "Great Vibes";
  margin-top: 15%;
}
</style>
