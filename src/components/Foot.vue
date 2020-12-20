<template>
    <div>
        <b-container>
            <b-row>
                <b-col>
                    <div>
                        <h2>Site Map</h2>
                        <ul>
                            <li v-for="site in sites" :key="site.message"> {{site.message}} </li>
                        </ul>
                    </div>
                </b-col>
                <b-col>
                    <div>
                        <h2>Company</h2>
                        <ul>
                            <li v-for="company in companies" :key="company.message"> {{company.message}} </li>
                        </ul>
                    </div>
                </b-col>
                <b-col>
                    <div>
                        <h2>Connect</h2>
                        <ul>
                            <li v-for="connect in connects" :key="connect.message"> {{connect.message}} </li>
                        </ul>
                    </div>
                </b-col>
                <b-col>3 of 3</b-col>
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
                {message: 'Home'},
                {message: 'Bootcamp'},
                {message: 'Software Development'},
                {message: 'Course'},
                {message: 'Custom Training'},
                {message: 'Blog'}
            ],
            companies: [
                {message: 'About Us'},
                {message: 'Carrer'},
                {message: 'Press Kit'},
                {message: 'FAQ'}
            ],
            connects: [
                {message: 'Facebook'},
                {message: 'Instagram'},
                {message: 'Youtube'},
                {message: 'LinkedIn'},
            ]
        }
    }
}
</script>

<style scoped>

</style>