<template>
    <div class="teamBox">
        <Head htitle="TEAM"></Head>

        <div class="teamMemberBox">
            <ul class="clearfix">
                <li>
                    <img src="../../images/teamMember/team_001.png"/>
                    <div class="memberItem">
                        <h2 class="title mobileHide">Richard Tiutiun</h2>
                        <h3 class="degree mobileHide">Chief Technology Officer</h3>
                        <h2 class="title mobileShow">Richard Tiutiun / Chief Technology Officer</h2>
                        <div class="desc">
                            <p>Used to study at UC Berkeley</p>
                            <p>Proficienxt at design and development with experience on the XOR project and in the Stablecoin lab</p>
                            <p>Fanatical genius of blockchain technology and hacker born in Ukraine. Focused on research in new generation cryptocurrencies</p>
                        </div>
                    </div>
                </li>

                <li>
                    <img src="../../images/teamMember/team_002.png" />
                    <div class="memberItem">
                        <h2 class="title mobileHide">Dennis S. Lee</h2>
                        <h3 class="degree mobileHide">Chief Strategy Officer</h3>
                        <h2 class="title mobileShow">Dennis S. Lee / Chief Strategy Officer</h2>
                        <div class="desc">
                            <p>Serial entrepreneur and Crypto evangelist</p>
                            <p>INK Business Developer</p>
                            <p>Talented in marketing and branding</p>
                        </div>
                    </div>
                </li>

                <li>
                    <img src="../../images/teamMember/team_003.png" />
                    <div class="memberItem">
                        <h2 class="title mobileHide">Nina Ni</h2>
                        <h3 class="degree mobileHide">Chief Public Relation Officer</h3>
                        <h2 class="title mobileShow">Nina Ni / Chief Public Relation Officer</h2>
                        <div class="desc">
                            <p>Not only a financial practitioner but also a brand expert</p>
                            <p>Has rich brand and marketing experience in art curatorial, luxury marketing and private banking, which has been applied to the field of cryptocurrency well</p>
                        </div>
                    </div>
                </li>

                <li>
                    <img src="../../images/teamMember/team_004.png"/>
                    <div class="memberItem">
                        <h2 class="title mobileHide">Simon Nie</h2>
                        <h3 class="degree mobileHide">Lead Engineer</h3>
                        <h2 class="title mobileShow">Simon Nie / Lead Engineer</h2>
                        <div class="desc">
                            <p>Graduated from University of Toronto</p>
                            <p>Lead engineer of BCG Digital Ventures</p>
                            <p>Experienced expert in Trading Strategy, Investment Analyst and Engineering</p>
                        </div>
                    </div>
                </li>

                <li>
                    <img src="../../images/teamMember/team_005.png"/>
                    <div class="memberItem">
                        <h2 class="title mobileHide">Vincent Deng</h2>
                        <h3 class="degree mobileHide">Engineer</h3>
                        <h2 class="title mobileShow">Vincent Deng / Engineer</h2>
                        <div class="desc">
                            <p>Serial entrepreneur, blockchain developer and hacker with rich experience in AI, big data and blockchain</p>
                            <p>Used to work for the largest Fintech company Yirendai and led the development of risk management and core products</p>
                        </div>
                    </div>
                </li>

                <li>
                    <img src="../../images/teamMember/team_006.png"/>
                    <div class="memberItem">
                        <h2 class="title mobileHide">Sam Lee</h2>
                        <h3 class="degree mobileHide">Engineer</h3>
                        <h2 class="title mobileShow">Sam Lee / Engineer</h2>
                        <div class="desc">
                            <p>Graduate at University of New South Wales with master degree of computer science</p>
                            <p>Engineering Manager and Research Scientist at Huawei and Swiss Credit Bank,</p>
                            <p>Talented in cryptography and blockchain</p>
                        </div>
                    </div>
                </li>

                <li>
                    <img src="../../images/teamMember/team_007.png"/>
                    <div class="memberItem">
                        <h2 class="title mobileHide">Julie He</h2>
                        <h3 class="degree mobileHide">Legal Intern</h3>
                        <h2 class="title mobileShow">Julie He / Legal Intern</h2>
                        <div class="desc">
                            <p>Experienced lawyer focusing on the compliance of blockchain and cryptocurrency</p>
                            <p>PhD candidate of Law at University of Osgoode Hall</p>
                            <p>Participated in the design of legal frameworks for several cryptocurrencies</p>
                        </div>
                    </div>
                </li>

                <li>
                    <img src="../../images/teamMember/team_008.png"/>
                    <div class="memberItem">
                        <h2 class="title mobileHide">Chngpng</h2>
                        <h3 class="degree mobileHide">Core Contributor</h3>
                        <h2 class="title mobileShow">Chngpng / Core Contributor</h2>
                        <div class="desc">
                            <p>Experienced engineere focused on the development of blockchain and cryptocurrency</p>
                            <p>Worked in cryptocurrency industry for 5 years specialising in human-computer interaction</p>
                            <p>Top-level participation in the research and development team for several cryptocurrencies</p>
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
    .teamMemberBox{
        /*width: 20px 250px*/

        ul{
            width: 1066px;
            margin: 0 auto;
            padding-bottom: 120px;
            li{
                width: 250px;
                margin-right: 22px;
                height: 475px;
                background: #23262a;
                border-radius: 6px;
                float: left;
                margin-top: 48px;
                background: url("../../images/teamMember/team_item_bg.png") no-repeat;

                img{
                    display: block;
                    width: 126px;
                    height: auto;
                    margin: 0 auto;
                    padding-top: 32px;
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
            li:nth-child(4){
                margin-right: 0px;
            }
            li:nth-child(5){height: 544px;background-size: 250px 544px;}
            li:nth-child(6){height: 544px;background-size: 250px 544px;}
            li:nth-child(7){height: 544px;background-size: 250px 544px;}
            li:nth-child(8){
                margin-right: 0px;
                height: 544px;
                background-size: 250px 544px;

            }
        }

    }




    @media screen and (max-width: 720px) {
        .teamMemberBox{
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
                    position: relative;
                    margin-top: 10px;
                    img{
                        display: block;
                        width: 88px;
                        height: 88px;
                        //margin-left: 8px;
                        //margin-top: 14px;
                        padding-top: 0px;
                        position: absolute;
                        left: 8px;
                        top: 14px;
                    }
                    .memberItem{


                        padding-left: 112px;
                        .title{
                            font-size: 12px;
                            color: #fff;
                            text-align: left;
                            font-weight: normal;
                            margin-top: 14px;
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
