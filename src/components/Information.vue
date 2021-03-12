<template>
<div class="alumni-section">
    <b-container>
        <b-row>
            <b-col>
                <div>
                    <h2 class="title-alumni"> {{titleAlumni}} </h2>
                </div>
                <div>
                    <h2 class="title-review-alumni"> {{titleReviewAlumni}} </h2>
                </div>
                <div class="title-ulas-alumni">
                    {{ titleUlasAlumni }}
                    <span> <a href="#" class="title-report-alumni"> <strong> {{ titleReportAlumni }}  </strong>  </a> </span>
                </div>
            </b-col>
        </b-row>
        <b-row>
            
                <b-col class="course-report">
                    <span class="course-report-text">
                        COURSE <br>
                        REPORT
                    </span>
                </b-col>
                <b-col>
                    <div class="review-section">
                        <b-icon icon="star-fill" style="color:#E89A01"></b-icon> 
                        <b-icon icon="star-fill" style="color:#E89A01"></b-icon> 
                        <b-icon icon="star-fill" style="color:#E89A01"></b-icon>
                        <b-icon icon="star-fill" style="color:#E89A01"></b-icon> 
                        <b-icon icon="star-fill" style="color:#E89A01"></b-icon>
                        <span>
                            <h2>4.74/5 Rating</h2>
                        </span>
                    </div>
                </b-col>
        </b-row>
</b-container>
</div>
</template>

<script>
export default {
    data(){
        return{
            titleAlumni: 'Temui Lulusan Kami',
            titleReviewAlumni: 'Review',
            titleUlasAlumni: 'Baca apa yang alumni ulas melalui',
            titleReportAlumni: 'Course Report'
        }
    }

}
</script>

<style scoped>
.alumni-section{
    text-align: center;
    padding: 6%;
    background-color: #F4F5F6;
}

.title-alumni{
    color: rgba(11, 22, 43, 0.6);
    font-family: "Raleway", Sans-serif;
    font-size: 16px;
    font-weight: 400;
    text-transform: uppercase;
    font-style: normal;
    line-height: 20px;
    letter-spacing: 2px;
}

.title-review-alumni {
    font-size: 2rem;
    margin-bottom: 0.5rem;
    font-weight: 500;
    line-height: 1.2;
}

.title-ulas-alumni{
    font-family: "Raleway", Sans-serif;
    font-size: 20px;
    font-weight: 400;
    font-style: normal;
    line-height: 60px;
    letter-spacing: 0.5px;
}

.title-report-alumni{
    text-decoration: none;
    /* font-weight: 800; */
    color: #333333;
}

.course-report{
    text-align: right;
}

.review-section{
    text-align: left;
}

.course-report-text{
    font-family: "Montserrat", Sans-serif;
    font-size: 32px;
    font-weight: 900;
    font-style: normal;
    line-height: 0.8em;
    letter-spacing: -2.3px;
    fill: #B4B6B9;
    color: #B4B6B9;
    background-color: #14141400;
    border-radius: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
    
}
</style>>
