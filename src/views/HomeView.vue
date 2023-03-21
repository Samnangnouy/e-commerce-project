<template>
  <!-- <div class="about">
    <h1>This is an home page</h1>
  </div> -->
  <div class="head">
    <div class="title">
      <h3>Hero Boots</h3>
    </div>
    <div class="content">
      <a href="#">Home |</a>
      <a href="#">About |</a>
      <a href="#">Contact |</a>
    </div>
    <div class="search">
      <div class="icon">
        <img src="@/assets/Images/search.png">
      </div>
      <input type="text" placeholder="Search here">
      <div class="icon1">
        <img src="@/assets/Images/cart.png" style="background-color:red;">
      </div>
    </div>
  </div>
  <div class="shop"></div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
body{
  background-color: transparent;
}
.head{
  height: 120px;
  background-color: #4391AA;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-left: 50px;
  padding-right: 50px;
}
.title h3{
  font-size: 20px;
  color: #fff;
  font-family: Inria Serif;
}
.content a{
  margin: 10px;
  font-size: 20px;
  color: #fff;
  font-family: Inria Serif;
}
.search{
  display: flex;
  align-items: center;
  justify-content: center;
}
.search input{
  width: 224px;
  height: 38px;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
  font-size: 20px;
  border: none;
  outline: none;
  padding-left: 15px;
}
.search input::placeholder{
  opacity: 0.5;
  color: #D18585;
}
.search .icon{
  width: 40px;
  height: 40px;
  /* color: #4391AA; */
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
  /* background-color: transparent; */
}
.search .icon1{
  width: 40px;
  height: 40px;
  margin-left: 15px;
  background-color: #fff;
}
.search .icon1 img{
  width: 100%;
  object-fit: cover;
  color: #fff;
}
.search .icon img{
  width: 100%;
  object-fit: cover;
  background-color: #fff;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
  color: transparent;
}
.shop{
  margin: 30px;
  height: 278px;
  background-color: #BC95AD;
}
</style>