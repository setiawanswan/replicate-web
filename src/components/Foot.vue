<template>
    <div class="footer">
        <b-container>
            <b-row>
                <b-col col lg="2">
                    <div>
                        <h2 class="title">Site Map</h2>
                        <p v-for="site in sites" :key="site.message"> <a href="#" class="link"> {{site.message}} </a></p>
                    </div>
                </b-col>
                <b-col col lg="2">
                    <div>
                        <h2 class="title">Company</h2>
                        <p v-for="company in companies" :key="company.message"> <a href="#" class="link">{{company.message}}</a></p>
                    </div>
                </b-col>
                <b-col col lg="2">
                    <div>
                        <h2 class="title">Connect</h2>
                        <p v-for="connect in connects" :key="connect.message"> <a href="#" class="link"> {{connect.message}}</a> </p>
                    </div>
                </b-col>
                <b-col col lg="3">
                    <div class="footer-icon">
                        <h1>Icon</h1>
                    </div>
                    <div class="footer-contact-company">
                        <b-row>
                            <b-col>
                                <h2 class="title">Company Addres</h2>
                                <p class="link"> {{ addres }} </p>
                            </b-col>
                            <b-col>
                                <h2 class="title">Contact</h2>
                                <p></p>
                            </b-col>
                        </b-row>
                    </div>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
export default {
    name: 'Footer',
    data(){
        return {
            sites : [
                {message: 'Beranda'},
                {message: 'Course'},
                {message: 'RSVP'},
                {message: 'Untuk Perusahaan'},
                {message: 'Blog'}
            ],
            companies: [
                {message: 'About Us'},
                {message: 'OKR'},
                {message: 'FAQ'},
                {message: 'Press Kit'}
            ],
            connects: [
                {message: 'Instagram'},
                {message: 'Facebook'},
                {message: 'Youtube'},
                {message: 'LinkedIn'},
            ],
            addres: 'Jln. Palagan Tentara Pelajar Km. 9,8 Ngaglik, Kab. Sleman DI Yogyakarta 55581'
        }
    }
}
</script>

<style scoped>
.footer{
    background-color: #0c162a;
    padding: 3%;
}

.title{
    font-family: 'Raleway', sans-serif;
    color: #eaeaea;
    font-size: 16px;
    font-weight: 600;
    font-style: normal;
    line-height: 20px
}

.link{
    text-decoration: none;
    color: #eaeaea;
}

</style>