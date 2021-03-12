<template>
    <div class="review-section">
        <b-container>
            <b-row>
                <b-col>
                    <b-card
                    img-src="https://refactory.id/wp-content/uploads/2020/01/agent-1.jpg"
                    img-alt="Image"
                    img-top
                    tag="article"
                    style="max-width: 24rem;"
                    class="mb-2"
                    >
                    <div>
                        <a href="#" class="nameReviewer"> {{ content.name }} </a> 
                    </div>
                    <div >
                        <a href="#" class="roleReviewer"> {{ content.role }} </a> 
                    </div>
                    <div class="icon">
                        <b-icon icon="star-fill" style="color:#E89A01" font-scale="2"></b-icon>
                    </div>
                    <div class="infoReviewer">
                        {{ content.info }}
                    </div>
                    <div class="reviewReviewer">
                        {{ content.review }}
                    </div>
                    </b-card>
                </b-col>
                <b-col>
                    <b-card
                    img-src="https://refactory.id/wp-content/uploads/2020/01/agent-2.jpg"
                    img-alt="Image"
                    img-top
                    tag="article"
                    style="max-width: 24rem;"
                    class="mb-2"
                    >
                    <div>
                        <a href="#" class="nameReviewer"> {{ information.name }} </a> 
                    </div>
                    <div >
                        <a href="#" class="roleReviewer"> {{ information.role }} </a> 
                    </div>
                    <div class="icon">
                        <b-icon icon="star-fill" style="color:#E89A01" font-scale="2"></b-icon>
                    </div>
                    <div class="infoReviewer">
                        {{ information.info }}
                    </div>
                    <div class="reviewReviewer">
                        {{ information.review }}
                    </div>
                    </b-card>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
export default {
    data(){
        return {
            content : {
                name: 'HARI TRI WIBOWO',
                role: 'Software Engineer at AsiaCommerce',
                info: 'Dare to face real experience?',
                review: 'I am one of a graduate from batch 1, this Bootcamp really boosting my skill and knowledge related to mobile programming and acknowledge me there is another important aspect which is soft skills. If You want to pursue in the mobile programming career, then this it is.'

            },
            information : {
                name: 'WANDA ICHSANUL ISRA',
                role: 'Software Engineer at Tokopedia',
                info: 'Right Place to Boost Your Programming Career',
                review: 'Refactory is one of the most wonderful experience that I’ve ever had in my entire life. Friendly and professional mentors, curriculum that aligned with the needs of software industry, real working experience in comfortable place, those all totally worth time and money. Thanks Refactory family!'

            }
        }
    }
}
</script>

<style scoped>
.review-section{
    padding: 6%;
}

.nameReviewer{
    color: #111111;
    /* font-family: "Raleway", Sans-serif; */
    font-size: 28px;
    font-weight: 400;
    text-transform: uppercase;
    font-style: normal;
    line-height: 32px;
    letter-spacing: 0.2px;
    text-decoration: none;
}

.roleReviewer{
    color: #999999;
    /* font-family: "Montserrat", Sans-serif; */
    font-size: 18px;
    font-weight: 500;
    font-style: normal;
    line-height: 22px;
    text-decoration: none;
}

.infoReviewer{
    color: rgba(11, 22, 43, 0.8);
    /* font-family: "Montserrat", Sans-serif; */
    font-size: 18px;
    font-weight: 700;
    font-style: normal;
    line-height: 30px;
}

.reviewReviewer{
    color: #0B162B;
    /* font-family: "Montserrat", Sans-serif; */
    font-size: 16px;
    font-weight: 300;
    font-style: normal;
    line-height: 30px;
    /* text-align:justify */
}

.image-review{
    /* padding: 6%; */
}
</style>