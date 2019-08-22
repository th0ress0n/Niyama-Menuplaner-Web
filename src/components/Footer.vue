
<template>
  <div id="footer" class="footer">
    <div class="top"></div>
    <div class="middle">
      <div id="centre-container" class="centre">
        <div id="col-one" class="column">
          <div id="col-one-title" class="column-title"></div>
          <div id="col-one-body" class="column-body"></div>
        </div>
        <div id="col-two" class="column">
          <div id="col-two-title" class="column-title"></div>
          <div id="col-two-body" class="column-body"></div>
        </div>
        <div id="col-three" class="column">
          <div id="col-three-title" class="column-title"></div>
          <div id="col-three-body" class="column-body"></div>
        </div>
        <div id="col-four" class="column">
          <div id="col-four-title" class="column-title"></div>
          <div id="col-four-body" class="column-body"></div>
        </div>
      </div>
    </div>
    <div class="bottom"></div>
  </div>
</template>

<style scoped> 
  .footer {
    position: fixed;
    bottom: 0;
    height: 100px;
    line-height: 60px;
    background-color: #015baf;
  }

  .column-title{
    font-weight: 700;
    color: #ffffff
  }

  .column-body{
    font-weight: 300;
    color: #ededed
  }

  .top{
    background-color: #09c!important;
  }

  .middle{
    background-color: #1c2331!important;
  }

  .bottom{
    background-color: #0f131b;
    height: 20px;
  }

</style>