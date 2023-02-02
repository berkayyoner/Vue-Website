<template>
    <div class="topnav">
      <a href="/"><img src="../assets/HaymanaTurizm-Logo.png" class="logo" alt="Logo" height="70" width="350" href="/"/></a>
      <div class="mid-buttons">
        <a class="mid-button" href="/contact">İLETİŞİM</a>
        <a class="mid-button" href="/menu">HİZMETLER</a>
        <a class="mid-button" href="/about">KURUMSAL</a>
        <a class="mid-button" href="/">ANASAYFA</a>
      </div>
    </div>
</template>

<script>
export default {
    name: 'NavBar',
    data() {
        return {
        }
    }
}
</script>

<style scoped>
body {
  position: relative;
  left: 0;
  right: 0;
  z-index: 2;
}
.topnav {
  overflow: hidden;
  margin: -8px;
  margin-right: -1%;
  background: rgba(75, 75, 75, 0.356);
}

.logo {
  float: left;
  margin-left: 20px;
  margin-top: 10px;
}

.mid-button {
  color: #f2f2f2;
  text-align: center;
  padding: 2% 1.2%;
  text-decoration: none;
  font-size: 16px;
  float: right;
}
.mid-buttons {
  margin-right: 10%;

}

.topnav .mid-button:hover {
  color: black;
  background-color: white;
  transition: 1s;
}
</style>