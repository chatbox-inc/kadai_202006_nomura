<template>
<div>
  <div class="header">
    <img src="~/assets/img/flower2.png" class="logo">
    <div class="title">かわいいが届くお花便</div>
    <p>* 北海道、沖縄、離島エリアは現在対象外です</p>
  </div>
  <nuxt />
  <div class="footer">
   <img class="instagram" src="~/assets/img/flower19.png">
   <div class="container">
     <p>お知らせnote</p>
     <p>FAQ</p>
     <p>プライバシーポリシー</p>
     <p>利用規約</p>
     <p>特定商取引法に関する表記</p>
     <p>運営会社</p>
   </div>
   <p class="copyright">Copyright ROLLCAKE Inc. All Rights Reserved.</p>
  </div>
</div>
</template>

<script>
  export default {
  }
</script>

<style>
 @media screen and (max-width: 480px){
   .header{
    background-image: url("~static/img/flower1.jpg");
    background-size: cover;
    background-position: center;
    height: 100vh;
    min-height: 660px;
    text-align: center;
    position: relative;
    padding-top: 48px;
    background-color: pink;
   }

   .header .logo{
    margin: 0 auto 16px;
    width: 131px;
    height: 116px;
    background-size: contain;
    background-position: center;
    background-repeat: no-repeat;
    margin-top: 5vh;
   }

   .header .title{
   font-size: 18px;
    color: #fff;
    margin: 16px 6vmin 24px;
   }

   .header p{
    font-size: 13px;
    margin-bottom: 4px;
    padding-top: 260px;
    position: absolute;
    bottom: 24px;
    left: 0;
    right: 0;
    color: #fff;
   }

   .footer {
    /* width: 400px; */
    height: 437px;
    padding: 32px 32px 128px;
    background: #3f434a;
    position: relative;
    min-height: 164px;
    color: #fff;
   } 

   .footer .instagram{
    width: 64px;
    height: 64px;
    background-size: cover;
    position: absolute;
    top: 24px;
    right: 24px;
   }

   .footer .container{
    display: flex;
    flex-direction: column;
    margin-bottom: 48px;
   }

   .footer p{
    flex-grow: 1;
    margin-bottom: 16px;
    font-size: 14px;
   }

   .footer p.copyright{
      font-size: 13px;
      color: #FFFFFF;
      opacity: 0.4;
      text-align: center;
      bottom: 124px;
      right: 0;
      left: 0;
      /* margin: auto; */
    }
 }

@media screen and (min-width: 481px){
  .header{
    background-image: url("~static/img/hana1.jpg");
    background-position: center bottom;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
    min-height: 660px;
    text-align: center;
    position: relative;
    padding-top: 100px;
    color: #fff;
   }

   .header .logo{
    margin: 0 auto 16px;
    height: 126px;
    width: 141px;
    background-size: contain;
    background-position: center;
    background-repeat: no-repeat;
   }

   .header .title{
    font-size: 20px;
    font-weight: 400;
    margin-top: 24px
   }

   .header p{
    font-size: 13px;
    position: absolute;
    bottom: 40px;
    left: 0;
    right: 0;
   }

   .footer {
    padding: 32px 32px 128px;
    background: #3f434a;
    position: relative;
    min-height: 164px;
    color: #fff;
   } 

   .footer .instagram{
    position: absolute;
    top: 24px;
    right: 24px;
    width: 64px;
    height: 64px;
   }

   .footer .container{
    flex-direction: row;
    width: 90%;
    display: flex;
    margin-bottom: 48px;
   }

  .footer p{
    flex-grow: 1;
    margin-bottom: 16px;
   }

  .footer p.copyright{
    text-align: center;
    position: absolute;
    bottom: 124px;
    right: 0;
    left: 0;
    font-size: 13px;
    color: #FFFFFF;
    opacity: 0.4;
   }
}
</style>
