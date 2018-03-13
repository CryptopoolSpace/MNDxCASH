<template>
    <div class="teamBox">
        <Head htitle="ADVISORS"></Head>

        <div class="advisorMemberBox">
            <div style="height: 90px" class="mobileHide"></div>
            <ul class="clearfix">
                <li>
                    <img src="../../images/advisor/advisor_001.png"/>
                    <div class="memberItem">
                        <h2 class="title mobileHide">Xiahong Lin</h2>
                        <h3 class="degree mobileHide">Founder of Bodhi</h3>
                        <h2 class="title mobileShow">Xiahong Lin / Founder of Bodhi</h2>
                        <div class="desc">
                            <p>Founded Bodhi prediction market after gaining extensive working experience in IBM, Microsoft，Twitter and Tecent.</p>
                            <p>Developer of Twitter for Android.</p>
                            <p>Six years of cryptocurrency industry experience, with a Masters degree in machine learning and computer science.</p>
                        </div>
                    </div>

                </li>

                <li>
                    <img src="../../images/advisor/advisor_002.png" />
                    <div class="memberItem">
                        <h2 class="title mobileHide">Alan Wunsche</h2>
                        <h3 class="degree mobileHide">CEO of TokenFunder</h3>
                        <h2 class="title mobileShow">Alan Wunsche / CEO of TokenFunder</h2>
                        <div class="desc">
                            <p>CEO & Chief Token Officer of TokenFunder, a company with the mission to help Canada be a leader in blockchain technology.</p>
                            <p>Leading finance technologist focused on new blockchain business models and the disruptive impacts of blockchain on global wealth distribution and innovation.</p>
                        </div>
                    </div>

                </li>

                <li>
                    <img src="../../images/advisor/advisor_003.png" />
                    <div class="memberItem">
                        <h2 class="title mobileHide">Patrick Dai</h2>
                        <h3 class="degree mobileHide">Founder of Qtum</h3>
                        <h2 class="title mobileShow">Patrick Dai / Founder of Qtum</h2>
                        <div class="desc">
                            <p>Named to Forbes’ ”30 Under 30”.</p>
                            <p>Graduate from Draper University in Silicon Valley and dropped out from the Chinese Academy of Sciences.</p>
                            <p>Previously employed at Alibaba Group.</p>
                            <p>A bitcoin and blockchain expert, developing and striving to achieve mainstream adoption of blockchain technology.</p>
                        </div>
                    </div>

                </li>

            </ul>
        </div>

    </div>

</template>

<script type="text/javascript">

    import Head from './head';

    export default {
        data() {
            return {

            }
        },

        mounted() {
        },
        methods: {

        },
        components:{
            Head,
        }
    }
</script>


<style lang="scss">
    .advisorMemberBox{

        ul{
            width: 964px;
            margin: 0 auto;
            padding-bottom: 120px;
            li{
                width: 300px;
                margin-right: 32px;
                height: 450px;
                background: #23262a;
                border-radius: 6px;
                float: left;
                margin-top: 48px;
                background: url("../../images/advisor/advisor_bg.png") no-repeat;
                background-size: 300px 450px;

                img{
                    display: block;
                    width: 164px;
                    height: auto;
                    margin: 0 auto;
                    margin-top: -90px;

                }
                .title{
                    font-size: 20px;
                    color: #fff;
                    text-align: center;
                    font-weight: normal;
                    margin-top: 28px;
                    line-height: 22px;
                }
                .degree{
                    font-size: 15px;
                    font-weight: normal;
                    text-align: center;
                    line-height: 18px;
                    color: #999;
                    margin-top: 6px;
                }
                .desc{

                    p{
                        font-size: 16px;
                        color: #999999;
                        line-height: 20px;
                        margin-top: 18px;
                        padding-left: 26px;
                        padding-right: 6px;
                        text-align: left;
                    }
                }
            }
            li:nth-child(3){
                margin-right: 0px;
            }

        }

    }

    @media screen and (max-width: 720px) {
        .advisorMemberBox{
            ul{
                width: auto;
                margin: 0 auto;
                padding-bottom: 120px;
                padding: 0 12px;
                li{
                    border-style: solid;
                    border-width: 1px;
                    border-color: rgb(69, 71, 76);
                    border-radius: 10px;
                    box-sizing: border-box;
                    width: 100%;
                    height: auto;
                    background: #23262a;

                    padding-bottom: 14px;
                    margin-top: 64px;
                    position: relative;

                    img{
                        display: block;
                        width: 94px;
                        height: 94px;
                        margin-left: 8px;
                        margin-top: 0px;
                        padding-top: 0px;
                        position: absolute;
                        right: 36px;
                        top:-48px;

                    }
                    .memberItem{
                        padding-left: 12px;
                        .title{
                            font-size: 12px;
                            color: #fff;
                            text-align: left;
                            font-weight: normal;
                            margin-top: 20px;
                            line-height: 14px;
                        }
                        .degree{
                            font-size: 12px;
                            font-weight: normal;
                            text-align: left;
                            line-height: 18px;
                            color: #999;
                            margin-top: 6px;
                        }
                        .desc{
                            margin-top: 16px;

                            p{
                                font-size: 11px;
                                color: #999999;
                                line-height: 13px;
                                margin-top: 8px;
                                padding-left: 0px;
                                padding-right: 6px;
                                text-align: left;
                            }
                        }
                    }

                }
                li:nth-child(4){
                    margin-right: 0px;
                }
                li:nth-child(5){height: auto}
                li:nth-child(6){height: auto}
                li:nth-child(7){height: auto}
                li:nth-child(8){
                    margin-right: 0px;
                    height: auto;
                }
            }

        }
    }
</style>
