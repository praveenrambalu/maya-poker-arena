<script setup lang="ts">
</script>

<template>
  <video autoplay muted loop id="bgVideo">
    <source src="@/assets/poker-arena-website.mp4" type="video/mp4">
  </video>
  <div class="content">
    <img src="@/assets/logo.png" alt="Logo" class="logo">
    <div class="content-inner">

      <h1>AI vs AI NFT Poker Game</h1>
      <h3>Train unique AI poker agents (NFTs) to play, earn and dominate in the Play-to-Earn Poker Revolution! </h3>
      <button>JOIN WAITLIST</button>
    </div>
  </div>
</template>


<style lang="scss">
body {
  margin: 0;
  padding: 0;
  overflow-y: hidden;
  position: relative;

  #bgVideo {
    width: 100%;
    height: 100%;
    background-color: red;
  }

  .content {
    position: absolute;
    top: 0;
    height: 100vh;
    width: 100%;
    background: #0000002b;

    .logo {
      position: absolute;
      left: 0;
      height: 200px;
    }

    .content-inner {
      text-align: center;
      bottom: 100px;
      position: absolute;
      width: 100%;

      h1 {
        color: white;
        text-shadow: 0 4px 3.3px 0 #000000;
        font-family: "Outfit", sans-serif;


        font-size: 40px;
        font-weight: 900;



      }

      h3 {
        color: white;
        text-shadow: 0 4px 3.3px 0 #000000;
        font-family: "Outfit", sans-serif;

        font-size: 20px;
        font-weight: 500;
        text-align: center;
        width: 50%;
        margin: auto;
        line-height: 40px;
        margin-bottom: 20px;

      }

      button {
        padding: 15px 30px;
        font-family: "Outfit", sans-serif;
        box-shadow: 2px -2px 2px 0px #FFFFFF;
        border: none;
        background: linear-gradient(180deg, #FF6651 0%, #E92929 100%);
        color: white;

        font-size: 20px;
        font-weight: 800;
        text-align: center;
        border-radius: 15px;

      }
    }
  }
}
</style>