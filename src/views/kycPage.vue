<template>
    <div id="kycPage">
        <div class="upload">
            <h2>ID Front</h2>
            <p>A color copy of a valid government issued photo ID(e.g.passport,driving license or ID card).</p>
            <div class="choose">Choose file</div>
        </div>
        <div class="upload">
            <h2>ID Back</h2>
            <p>A color copy of a valid government issued photo ID(e.g.passport,driving license or ID card</p>
            <div class="pending">
                <span></span>
                <div>
                    <h3>Pending...</h3>
                    <p>Thank you for submitting your KYC, all KYC will be processed in bulk after the token sale.</p>
                </div>
            </div>
            <div class="save">Save</div>
        </div>
         
    </div>

</template>

<script type="text/javascript">
export default {
  data() {
    return {};
  },
  methods: {}
};
</script>


<style lang="scss">
#kycPage {
  padding: 87px 8% 1155px 8%;
  max-width: 929px;
  font-size: 0;
  div:first-of-type {
    margin-right: 3%;
  }
  .upload {
    width: 48.5%;
    min-height: 452px;
    box-sizing: border-box;
    padding: 22px 39px 71px 39px;
    background-color: #23252a;
    border: solid 1px #999999;
    display: inline-block;
    overflow: hidden;
    position: relative;
    h2 {
      font-size: 20px;
      font-weight: normal;
      font-stretch: normal;
      color: #fff;
      margin-bottom: 20px;
    }
    p {
      font-size: 16px;
      font-weight: normal;
      font-stretch: normal;
      line-height: 24px;
      color: #ffffff;
    }
    .choose {
      width: 130px;
      height: 30px;
      border-radius: 14px;
      border: solid 1px #05e1e3;
      margin-top: 24px;
      font-size: 16px;
      color: #fff;
      text-align: center;
      line-height: 30px;
    }
    .pending {
      border-radius: 10px;
      border: solid 1px #626262;
      padding: 11px 15px;
      margin-top: 24px;
      position: relative;
      div {
        margin-left: 46px;
      }
      span {
        position: absolute;
        left: 15px;
        top: 0;
        bottom: 0;
        margin: auto;
        width: 34px;
        height: 34px;
        background: url(../../images/myprofile_pc/clock.png) no-repeat;
      }
      p,
      h3 {
        font-size: 16px;
        font-weight: normal;
        font-stretch: normal;
        line-height: 24px;
        color: #626262;
        text-align: left;
      }
      h3 {
        margin-bottom: 13px;
      }
    }
    .save {
      position: absolute;
      width: 79px;
      height: 30px;
      background-color: #05e1e3;
      border-radius: 14px;
      font-size: 16px;
      color: #fff;
      line-height: 30px;
      text-align: center;
      left: 37px;
      bottom: 71px;
    }
  }
}
@media screen and (max-width: 1080px) {
  #kycPage {
    padding: 31px 13px 88px 13px;
    div:first-of-type {
      margin-right: auto;
    }
    .upload {
      width: 334px;
      height: 333px;
      box-sizing: border-box;
      padding: 21px 10px 29px 10px;
      background-color: #23252a;
      border: solid 1px #999999;
      display: block;
      margin: 15px auto 0;
      p {
        font-size: 12px;
        line-height: 34px;
      }
      .choose {
        width: 99px;
        height: 30px;
        border-radius: 14px;
        border: solid 1px #05e1e3;
        margin-top: 57px;
        font-size: 12px;
      }
      .save {
        left: 11px;
        bottom: 29px;
      }
    }
  }
}
</style>