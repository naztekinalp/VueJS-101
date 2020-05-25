<!--lacıvert kısım icine ıvır zıvırı ekle
bunu da maine bagla ait oldugu yer orası , main de home a baglı olacak-->
<template>
  <div class="header">
    <div class="container-fluid">
        <div class="container">
      <div class="row">
      <div class="button">
        <input class="form-control" type="text" placeholder="Search" aria-label="Search" />
          </div>
          <div class="col5 mt-3" style="margin-right:10px; padding-left:0px;">
          <img src="src/img/top.png" alt="">
          </div>
      </div>
      </div>
      <div class="container pt-2 ml-2">
      <div class="row">
        <p>ss<img src="src/img/home.png" style="width:16px; height:15px margin-bottom:260px;" /></p>
      </div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col0">
            <img src="src/img/box1.png" style="width:240px; height:100px" />
          </div>
          <div class="col3">
            <img src="src/img/box1.png" style="width:240px; height:100px" />
          </div>
          <div class="col5">
            <img src="src/img/box1.png" style="width:240px; height:100px" />
          </div>
          <div class="col7">
            <img src="src/img/box1.png" style="width:240px; height:100px" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.container-fluid {
  height: 228px;
  background-color: #172b4d;
}
.button{
    margin-bottom:'300px;'
}
h3 {
  margin-top: 50px;
  float: left;
  margin-left: 10px;
  color: white;
  font-size: 25px;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
.button {
  padding-top: 20px;
  width: 200px;
  border-radius: 50px;
  height: 50px;
}
.form-control {
  border-radius: 20px;
  height: 40px;
}
</style>
