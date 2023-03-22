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
        <img src="@/assets/Images/shopping-cart.png">
      </div>
    </div>
  </div>
  <div class="shop">
    <div class="con">
      <p>Trade-in-offer</p>
      <h1>Super Value deals</h1>
      <h1>All on products</h1>
      <p>Save more with coupons & up to 70% off</p>
      <button>Shop Now</button>
    </div>
  </div>
  <div class="arrive">
    <h1>New Arrival</h1>
    <p>Summer Collection New Modern Design</p>
  </div>
  <div class="info">
    <div class="detail">
      <div class="pic">
        <img src="@/assets/Images/clothe1.jpg">
      </div>
      <div class="more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="wrapper">
          <button>Details</button>
          <p>32.12$</p>
        </div>
      </div>
    </div>
    <div class="detail">
      <div class="pic">
        <img src="@/assets/Images/clothe3.jpg">
      </div>
      <div class="more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="wrapper">
          <button>Details</button>
          <p>32.12$</p>
        </div>
      </div>
    </div>
    <div class="detail">
      <div class="pic">
        <img src="@/assets/Images/clothe2.jpg">
      </div>
      <div class="more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="wrapper">
          <button>Details</button>
          <p>32.12$</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
*{
  font-family: 'Inria Serif';
}
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
.head{
  height: 120px;
  background-color: #4391AA;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-left: 80px;
  padding-right: 80px;
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
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50px;
  height: 40px;
  background-color: #fff;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
}
.search .icon1{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50px;
  height: 40px;
}
.search .icon1 img{
  width: 30px;
  height: 30px;
}
.search .icon img{
  width: 30px;
  height: 30px;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
  color: transparent;
}
.shop{
  margin-left: 30px;
  margin-right: 30px;
  margin-top: 15px;
  margin-bottom: 15px;
  height: 278px;
  background-color: #BC95AD;
}
.shop .con{
  padding-left: 70px;
  padding-top: 30px;
}
.shop .con p{
  color: #fff;
  font-weight: bold;
  font-size: 14px;
  margin-bottom: 10px;
}
.shop .con h1{
  font-weight: 550;
  margin-bottom: 0px;
  margin-top: 10px;
}
.shop .con button{
  width: 224px;
  height: 58px;
  border-radius: 10px;
  background-color: #334C7B;
  font-size: 20px;
  color: #FFFFFF;
  font-weight: 500;
  border: none;
  box-shadow: 5px 5px 10px 2px rgba(0,0,0,.8);
  cursor: pointer;
}
.shop .con button:hover{
  background-color: #FFFFFF;
  color: #334C7B;
  transition-duration: 0.4s;
}
.arrive{
  height: 104px;
  background-color: #BC95AD;
  margin-left: 30px;
  margin-right: 30px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.arrive h1{
  margin-top: 0;
  font-size: 32px;
  margin-bottom: 10px;
}
.arrive p{
  font-size: 18px;
  color: #FFFFFF;
  margin-top: 0;
}
.info{
  margin-left: 30px;
  margin-right: 30px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.detail{
  margin-top: 30px;
  width: 400px;
  height: 390px;
  background-color: #BC95AD;
}
.detail .pic{
  width: 400px;
  height: 270px;
}
.detail .pic img{
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.more{
  width: 400px;
  height: 120px;
  background-color: #D9D9D9;
}
.more .title{
  display: flex;
  align-items: center;
  justify-content: center;
}
.more .title p{
  margin-top: 10px;
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 600;
}
.more .wrapper{
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-right: 50px;
  margin-left: 50px;
}
.more .wrapper button{
  width: 140px;
  height: 40px;
  border-radius: 8px;
  background-color: #6598BC;
  font-size: 16px;
  color: #FFFFFF;
  font-weight: 600;
  border: none;
  box-shadow: 5px 5px 5px 1px rgba(0,0,0,.6);
  cursor: pointer;
}
.more .wrapper button:hover{
  background-color: #FFFFFF;
  color: #6598BC;
  transition-duration: 0.4s;
}
.more .wrapper p{
  font-size: 16px;
  font-weight: 600;
}
</style>