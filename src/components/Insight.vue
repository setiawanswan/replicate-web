<template>
<body>
    <div class="insight-section">
        <p class="insight-subtitle">Insight Terbaru</p>
        <p class="insight-title">Knowledge Sharing</p>
    </div>
    <div class="letsee-section">
        <a href=""><p class="letsee-text">Lihat Semua</p></a>
    </div>
</body>
</template>

<script>
export default {
    nama: "Insight"
}
</script>

<style scoped>
.body {
    background-image: url("https://refactory.id/wp-content/uploads/2020/01/ripple-bg.png");
}

.insight-section {
    text-align: center;
    padding: 16px;
}

.insight-subtitle{
    color: rgba(11, 22, 43, 0.6);
    font-family: "Raleway", Sans-serif;
    font-size: 18px;
    font-weight: 400;
    text-transform: uppercase;
    font-style: normal;
    margin-bottom: 20px;
}

.insight-title{
    color: #0B162B;
    font-family: "Raleway", Sans-serif;
    font-size: 28px;
    font-weight: 700;
    font-style: normal;
    margin-bottom: 20px;
}

.letsee-text{
    font-family: "Raleway", Sans-serif;
    font-size: 18px;
    font-weight: 400;
    line-height: 22px;
    color: #007BFF;
    text-align: center;
    padding: 3%;
    text-decoration: none;
}
</style>>
