<template>
<div>
    <b-container :class="[$style.middle]">
        <div :class="[$style.section]">
            <p :class="[$style.title]">Apa Yang Refactory Dapat Bantu?</p>
        </div>
        <b-row>
            <b-col>
                <img :class="[$style.logo]" alt="Approval Logo" src="../assets/material_approval.png">
                <p :class="[$style.subtitle]">Memperkuat Tim Engineer Anda</p>
                <p :class="[$style.content]">
                    Bisnis di jaman modern membutuhkan keterampilan 
                    pengembangan terbaik untuk meningkatkan skala 
                    produk. 
                    Kami dapat mempersiapkan course dan juga 
                    dapat menyediakan tim yang menangani kebutuhan digital Anda.
                </p>
            </b-col>
            <b-col>
                <img :class="[$style.logo]" alt="Bolt Logo" src="../assets/material_bolt.png">
                <p :class="[$style.subtitle]">Wujudkan Software Impian Anda</p>
                <p :class="[$style.content]">
                    Kami adalah perusahaan One-Stop IT Solution untuk 
                    proyek Anda, 
                    membantu di setiap tahap mulai dari 
                    menyusun ide, melalui desain dan pengembangan 
                    aplikasi seluler, situs web dan aplikasi desktop, hingga 
                    peluncuran produk
                </p>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<script>
export default {
    name : 'Information'
}
</script>

<style module>
.middle{
    text-align: center;
}

.section {
    padding: 4%;
}

.title {
    color: #0B162B;
    font-family: "Raleway", Sans-serif;
    font-size: 38px;
    font-weight: 700;
    font-style: normal;
    line-height: 42px;
    letter-spacing: 2px;
}

.logo{
    text-align: center;
}

.subtitle {
    color: #0B162B;
    font-family: "Raleway", Sans-serif;
    font-size: 28px;
    font-style: normal;
    line-height: 32px;
    text-align: center;
}

.content {
    color: rgba(11, 22, 43, 0.6);
    font-family: "Montserrat", Sans-serif;
    font-size: 16px;
    font-weight: 400;
    font-style: normal;
    line-height: 30px;
    text-align: center;
}
</style>