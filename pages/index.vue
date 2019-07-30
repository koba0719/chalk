<template>
  <div>
    <div class="flex-title-container">
      <!--  <b-container>-->
      <!--    <b-row>-->
      <!--      <b-col cols="6">-->
      <div class="flex-title">
        <h1 class="title">
          Chalkで貯金！?<br>
          お金を人質にToDoを完遂させましょう！<br>
        </h1>
        <p class="header-content">
          Chalkを利用することで現実的な計画をたてることができます。<br>
          達成できなければ貯金です <br>
          お金が全部無くならないようにがんばりましょう
        </p>
        <b-button class="start-button" variant="success">アカウントを作成！ - 今すぐ始めましょう！！</b-button>
      </div>
      <!--      </b-col>-->
      <!--      <b-col cols="6">-->
      <div class="flex-img">
        <img class="img-top" src="~/assets/undraw_Checklist_7dx2.svg" alt="TOP">
      </div>
      <!--      </b-col>-->
      <!--    </b-row>-->
      <!--    <b-row>-->
      <!--      <b-col cols="5">-->
    </div>
    <div class="flex-container">
      <div class="flex-title-1">
        <h1 class="title-1">
          あなたの目標にお金を設定<br>
        </h1>
        <p class="header-content-1">
          作成したToDoには罰金を設定できます。<br>
          甘えた自分を律するため丁度良い金額を設定しましょう。 <br>
        </p>
      </div>
      <div class="flex-img-1">
        <img src="~/assets/undraw_wallet_aym5.svg" alt="img1" class="img-top">
      </div>
    </div>
  </div>
</template>

<style scoped>
  .flex-img {
    width: 40%;
  }

  .start-button {
    margin-top: 4vh;
    font-size: 20px;
  }

  .flex-title-1 {
    padding-top: 10vh;
    width: 55%;
  }

  .flex-container {
    /*margin-top: 7vh;*/
    padding-top: 4vw;
    padding-left: 10vw;
    padding-right: 10vw;
    display: flex;
    flex-wrap: nowrap;
    height: 30vh;
  }

  .flex-title-container {
    padding-top: 3vw;
    padding-left: 10vw;
    padding-right: 10vw;
    background-color: #0079BF;
    display: flex;
    flex-wrap: nowrap;
    height: 63vh;
  }

  .img-top {
    width: 35vw;
  }

  .container {
    padding-top: 20vh;
    margin: 0 auto;
    min-height: 100vh;
  }

  .header-content-1 {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    font-weight: 200;
    font-size: 20px;
    line-height: 1.5;
    margin-top: 1.5vh;
  }

  .header-content {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    font-weight: 200;
    font-size: 20px;
    line-height: 1.5;
    color: #ffffff;
    margin-top: 3vh;
  }

  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    display: block;
    font-weight: bold;
    font-size: 35px;
    line-height: 1.5;
    color: #ffffff;
    letter-spacing: 1px;
  }

  .title-1 {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    display: block;
    font-size: 35px;
    line-height: 1.5;
    letter-spacing: 1px;
  }

  .links {
    padding-top: 15px;
  }
</style>
