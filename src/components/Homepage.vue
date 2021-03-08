<template>
  <div class="homepage-section">
    <b-container>
      <b-row>
        <b-col>
          <div class="content">
            <p> 
              {{title}} <br> <strong style="color: #e48800"> {{subTitle}} </strong>
            </p>
          </div>
          <div class="subcontent">
            <p>{{content}}</p>
          </div>
          <div>
            <a href="#" class="link">Pelajari Lebih Lanjut <b-icon icon="chevron-right"></b-icon> </a>
          </div>
        </b-col>
        <b-col></b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'Header',
  
  data(){
    return {
      title: 'Pekerjaan anda terdampak pandemi?',
      subTitle: 'Kami Bisa Membantu!',
      content: 'Lebih dari 3.5 juta orang di Indonesia kehilangan pekerjaan karena pandemi. Refactory berkomitmen membantu mereka yang terdampak pandemi untuk belajar pemrograman secara daring hingga siap bekerja dan disalurkan di industri yang terus berkembang. Dari awam sampai mampu!'
    }
  }
}
</script>

<style scoped>


.homepage-section{
  padding: 12%;
  width: 100%;
  /* background-image: linear-gradient(110deg, #00256C 10%, #04ACA4 90%); */
  background-image: url(https://refactory.id/wp-content/uploads/2021/01/Space12-1.png);
  background-position: center right;
  background-repeat: no-repeat;
  background-size: cover;
  

}

.content{
  color: #FFFFFF;
    /* font-family: Sans-serif; */
    font-size: 36px;
    font-weight: 400;
    line-height: 48px;
}
.subcontent{
  color: #FFFFFF;
    /* font-family: "Montserrat", Sans-serif; */
    font-size: 14px;
    font-weight: 400;
    font-style: normal;
    text-align: justify;
}

.link{
  /* font-family: "Montserrat", Sans-serif; */
  font-size: 16px;
  color: #FFFFFF;
  text-decoration: underline;
}
</style>
