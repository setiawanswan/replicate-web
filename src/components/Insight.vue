<template>
<div class="insight-section">
    <b-container>
        <b-row>
            <b-col>
                <div>
                    <h2 class="title-insight"> {{ titleInsight }} </h2>
                </div>
                <div>
                    <h2 class="title-knowledge"> {{titleKnowledge}} </h2>
                </div>
            </b-col>
        </b-row>
        <b-row>
            <b-col>
                adasd
            </b-col>
            <b-col>
adasd
            </b-col>
            <b-col>
adas
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<script>
export default {
    data(){
        return{
            titleInsight: 'Insight Terbaru',
            titleKnowledge: 'Knowledge Sharing'
        }
    }
}
</script>

<style scoped>
.insight-section{
    text-align: center;
    padding: 6%;
    background-color: #F4F5F6;
}

.title-insight{
    color: #718096;
    font-family: "Raleway", Sans-serif;
    font-size: 20px;
    font-weight: 400;
    text-transform: uppercase;
    font-style: normal;
    letter-spacing: 2px;
}

.title-knowledge{
    color: #000000;
    font-family: "Raleway", Sans-serif;
    font-size: 48px;
    font-weight: 700;
    font-style: normal;
}

</style>