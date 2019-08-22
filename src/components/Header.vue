<template functional>
  <!-- <div id="header" slot="header">{{props.header}}</div> -->
  <div id="header" class="header">
    <div id="brand-logo" class="logo"><img src="../assets/ml-logo.png" alt="menu planer" class="logo-image"></div>
  </div>
</template>

<style scoped>
.header{
    margin: 0;
    background-color: #ffffff;
}
.logo{
  display: inline-block;
  margin-left: 30px;
  margin-top: 15px;
  margin-bottom: 15px;
  width: 20%;
  height:auto;
}
.logo-image{
  width:100%;
  height: auto;
}
</style>