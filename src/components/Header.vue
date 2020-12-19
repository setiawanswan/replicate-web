<template>
  <div class="hello">
    <b-container class="bv-example-row">
      <b-row>
        <b-col>
          <div>
            <div>Empowering <span :class="[$style.title]">People </span> <br>
              Through Programming
            </div>
          </div>
          <div>
            <div>
              Refactory adalah perusahaan edukasi dan] teknologi yang menyediakan layanan lengkap berupa course maupun custom training yang materinya dapat disesuaikan dengan kebutuhan teknologi dan bisnis perusahaan Anda.
            </div>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
  }
}
</script>

<style module>
.title {
  color: #e48800
}
</style>
