<template>
<div class="corporate">
    <div class="corporate-section">
        <p class="title">as seen us</p>
    </div>
    <div class="corporate-element">
        <img class="logo" alt="CNN Logo" src="../assets/cnn_logo.png">
        <img class="logo" alt="Metro Logo" src="../assets/metro_logo.png">
        <img class="logo" alt="Beritasatu Logo" src="../assets/beritasatu_logo.png">
        <img class="logo" alt="Kumparan Logo" src="../assets/kumparan_logo.png">
        <img class="logo" alt="IDN Logo" src="../assets/idn_logo.png">
        <!-- <img alt="Viva Logo" src="../assets/viva_logo.png"> -->
    </div>
</div>
</template>
<script>

export default {
    name: "Corporate"
}
</script>

<style scoped>
.corporate{
    background-color: #E5E7E9;
}

.corporate-section {
    text-align: center;
    padding: 16px;
    text-transform: uppercase;
}
.title{
    font-size: 34px;
    line-height: 40px;
    letter-spacing: 1.5px;
    color: #0B162B;
    font-family: "Raleway", Sans-serif;
    font-weight: 700;
}

.corporate-element{
    padding: 16px;
    text-align: center;
}

.logo{
    max-width: 100%;
    padding: 26px;
}
</style>