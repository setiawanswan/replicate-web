<template>
  <body>
    <b-container>
      <b-row>
        <b-col>
          <div class="content">Empowering <span class="title">People </span> <br>
              Through Programming
          </div>
          <div class="subcontent">
            Refactory adalah perusahaan edukasi dan teknologi yang menyediakan layanan lengkap berupa course maupun custom training yang materinya dapat disesuaikan dengan kebutuhan teknologi dan bisnis perusahaan Anda.
          </div>
        </b-col>
        <b-col></b-col>
      </b-row>
    </b-container>
  </body>
</template>

<script>
export default {
  name: 'Header',
  props: {
  }
}
</script>

<style scoped>
body{
  padding: 15% 10%;
  width: 100%;
  background-image: linear-gradient(110deg, #00256C 10%, #04ACA4 90%);
  /* background-image: url("https://refactory.id/wp-content/uploads/2020/01/hero-homepage.jpg"); */
  background-color: transparent;
  /* opacity: 0.75 */
}

.content{
  color: #FFFFFF;
    font-family: "Raleway", Sans-serif;
    font-size: 48px;
    font-weight: 600;
    font-style: normal;
    line-height: 50px;
}
.subcontent{
  color: #FFFFFF;
    font-family: "Montserrat", Sans-serif;
    font-size: 16px;
    font-weight: 400;
    font-style: normal
}
.title {
  color: #e48800
}
</style>
