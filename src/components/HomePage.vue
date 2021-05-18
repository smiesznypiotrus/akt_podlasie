<template>
    <div class="container-fluid m-0 p-0">
      <div id="header" class="image p-0">

      </div>
      <div id="content" class="">
         <div class="row pb-2"> <!--padding bottom 5 -->
          <div class="col-sm-4">
            <img id="typ_wyjazdu" src="../assets/ico_1.svg" class="conent-img">
          </div>
          <div class="col-sm-4">
            <img id="trudnosc" src="../assets/ico_2.svg" class="conent-img">
          </div>
          <div class="col-sm-4">
            <img id="termin" src="../assets/ico_3.svg" class="conent-img">
          </div>
        </div>
      </div>
        <div>
          <img id="domek" src="../assets/house title.png" class="house-img">
        </div>
        <div class="pt-2 house_text">Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut 
              laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper 
              suscipit lobortis nisl ut aliquip ex ea commodo consequat.
        </div>
        
        <div class="row pb-2 pt-5">
          <div class="col-sm-6 text-right pt-photo" style="position:relative;">
            <img id="szlak_green_velo" src="../assets/title_1.svg" class="title-img">
            <div class="right-text">
              Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut 
              laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper 
              suscipit lobortis nisl ut aliquip ex ea commodo consequat.
            </div>
          </div>
          <div class="col-xs-6">
            <img id="szlak_green_velo" src="../assets/photo_1@2x.png" class="photo float-left">
          </div>
        </div>
        <div class="row pb-2 pt-5">
          <div class="col-sm-6">
            <img id="szlak_green_velo" src="../assets/title_1.svg" class="text float-right">
          </div>
          <div class="col-sm-6">
            <img id="szlak_green_velo" src="../assets/title_1.svg" class="text float-left">
          </div>
        </div>
        <div class="row pb-2 pt-5">
          <div class="col-sm-6">
            <img id="szlak_green_velo" src="../assets/title_1.svg" class="text float-right">
          </div>
          <div class="col-sm-6">
            <img id="szlak_green_velo" src="../assets/title_1.svg" class="text float-left">
          </div>
        </div>
        <div class="row pb-2 pt-5">
          <div class="col-sm-6">
            <img id="szlak_green_velo" src="../assets/title_1.svg" class="text float-right">
          </div>
          <div class="col-sm-6">
            <img id="szlak_green_velo" src="../assets/title_1.svg" class="text float-left">
          </div>
        </div>
        <div id="footer" class="image p-0"></div>      
    </div>
</template>

<script>
export default {
  data () {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  #header {
    content: url('../assets/header.png');
    height: auto;
    max-width: 100%;
  }

  #footer {
    content:url('../assets/bottom.png');
    height: auto;
    max-width: 100%;
  }

  #content {
    margin-left: 12vw;
    margin-right: 12vw;
  }

  .pt-photo {
    padding-top: 3vw;
  }

  .conent-img {
    height: auto;
    max-width: 100%;
    max-height: 30vw;
  }

  .house-img {
    height: auto;
    max-width: 50%;
  }

  .title-img {
    width: 25vw;
    max-width: 50%;
  }

  .house_text {
    display: inline-block;
    width: 50vw;
    text-align: center;
    font: normal normal normal 12px/15px Open Sans;
    letter-spacing: 0px;
    color: #707070;
    opacity: 1;
  }

  .text {
    display: inline-block;
    max-width: 50%;
    height: auto;
  }

  .text-left {
    align-content: left;
  }

  .right-text {
    padding-top: 1vw;
    padding-left: 10vw;
    max-width: 45vw;
    min-width: 45vw;
    display: inline-block;
    text-align: right;
    font: normal normal normal 2.5vw/2vw Open Sans;
    font-size: 2vw;
    letter-spacing: 0px;
    color: #707070;
    opacity: 1;
  }

  .photo {
    max-height: 25vw;
  }
</style>
