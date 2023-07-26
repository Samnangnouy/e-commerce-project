<template>
  <div class="head">
    <div class="title">
      <h3>Hero Boots</h3>
    </div>
    <div class="content">
      <router-link to="/"><a href="#">Home |</a></router-link>
      <router-link to="/product"><a href="#">Product |</a></router-link>
      <router-link to="/contact"><a href="#">Contact |</a></router-link>
    </div>
    <div class="search">
      <div class="icon">
        <img src="@/assets/Images/search.png">
      </div>
      <input type="text" placeholder="Search here">
      <div class="icon1">
        <router-link to="/carts"><img src="@/assets/Images/shopping-cart.png"></router-link>
      </div>
    </div>
  </div>
  <div class="shop1">
    <div class="con">
      <p>Trade-in-offer</p>
      <h1>Super Value deals</h1>
      <h1>All on products</h1>
      <p>Save more with coupons & up to 70% off</p>
      <router-link to="/product"><button>Shop Now</button></router-link>
    </div>
  </div>
  <div class="trend">
    <div class="content3">
      <div class="the-title">
        <h1>20% Off On Tank Tops</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit, assumenda? Non praesentium accusantium quod sit?</p>
        <router-link to="/product"><button>Shop Now</button></router-link>
      </div>
    </div>
    <div class="content1">
      <div class="the-title">
        <h1>20% Off On Tank Tops</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit, assumenda? Non praesentium accusantium quod sit?</p>
        <router-link to="/product"><button>Shop Now</button></router-link>
      </div>
    </div>
    <div class="content2">
      <div class="the-title">
        <h1>20% Off On Tank Tops</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit, assumenda? Non praesentium accusantium quod sit?</p>
        <router-link to="/product"><button>Shop Now</button></router-link>
      </div>
    </div>
  </div>
  <div class="arrive">
    <h1>Featured Products</h1>
    <p>Summer Collection New Modern Design</p>
  </div>
  <!-- <div class="info">
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
  </div> -->
  <div class="info">
    <div class="detail">
      <div class="pic">
        <img src="@/assets/Images/clothes4.jpg">
      </div>
      <div class="more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="wrapper">
          <router-link to="/detail"><button>Details</button></router-link>
          <p>32.12$</p>
        </div>
      </div>
    </div>
    <div class="detail">
      <div class="pic">
        <img src="@/assets/Images/clothes5.jpg">
      </div>
      <div class="more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="wrapper">
          <router-link to="/detail"><button>Details</button></router-link>
          <p>32.12$</p>
        </div>
      </div>
    </div>
    <div class="detail">
      <div class="pic">
        <img src="@/assets/Images/clothes6.jpg">
      </div>
      <div class="more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="wrapper">
          <router-link to="/detail"><button>Details</button></router-link>
          <p>32.12$</p>
        </div>
      </div>
    </div>
  </div>
  <div class="feature">
    <div class="left">
      <div class="con">
        <h3>New Collection</h3>
        <h1>Summer Collection New Modern Design</h1>
        <h2>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Necessitatibus, quidem.</h2>
        <router-link to="/product"><button>Shop Now</button></router-link>
      </div>
      <div class="product">
        <img src="@/assets/Images/jacket.png">
      </div>
    </div>
    <div class="right">
      <div class="con">
        <h3>New Collection</h3>
        <h1>Summer Collection New Modern Design</h1>
        <h2>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Necessitatibus, quidem.</h2>
        <router-link to="/product"><button>Shop Now</button></router-link>
      </div>
      <div class="product">
        <img src="@/assets/Images/jacket.png">
      </div>
    </div>
  </div>
  <div class="collection">
    <p>New Collection</p>
    <h1>Be different in your own way!</h1>
    <h3>Find your unique style.</h3>
    <p>Summer Collection New Modern Design</p>
    <router-link to="/product"><button>Shop Now</button></router-link>
  </div>
  <div class="men">
    <div class="left">
      <div class="img">
        <img src="@/assets/Images/collection-02.jpg">
      </div>
      <p>Men</p>
      <h1>The base collection - Ideal every day.</h1>
      <router-link to="/product"><button>Shop Now</button></router-link>
    </div>
    <div class="right">
      <img src="@/assets/Images/shop-.jpg">
    </div>
  </div>
  <div class="footer">
    <div class="followup">
      <p>Follow Us On</p>
      <img src="@/assets/Images/tik-tok.png">
      <img src="@/assets/Images/instagram.png">
      <img src="@/assets/Images/facebook.png">
      <img src="@/assets/Images/twitter.png">
    </div>
    <div class="subscribe">
      <p>Stay in Touch! Join Our Newletters</p>
      <input type="text" placeholder="Enter your email">
      <button>subscribe</button>
    </div>
  </div>
</template>

<style>
*{
  font-family: 'Inria Serif';
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
  font-size: 26px;
  color: #fff;
}
.content a{
  margin: 10px;
  font-size: 22px;
  color: #fff;
  display: inline-block;
  text-decoration: none;
  font-family: Inria Serif;
}
.content a::after{
  content: '';
  width: 0%;
  height: 2px;
  display: block;
  background-color: #FFFFFF;
  transition: 0.5s;
}
.content a:hover::after{
  width: 100%;
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
  width: 300px;
  background-color: #D9D9D9;
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
  background-color: #D9D9D9;
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
  cursor: pointer;
}
.search .icon img{
  width: 30px;
  height: 30px;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
  color: transparent;
}
.trend{
  margin-left: 30px;
  margin-right: 30px;
  margin-bottom: 15px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.trend .content3{
  margin-top: 20px;
  width: 28%;
  height: 500px;
  margin-right: 20px;
  background-image: linear-gradient(rgba(190, 96, 19, 0.7),rgba(4,9,30,0.7)),url("@/assets/Images/product-06-a.jpg");
  background-position: center;
  background-size: cover;
  position: relative;
}
.trend .content3 .the-title{
  position: absolute;
  bottom: 30px;
  left: 20px;
}
.trend .content3 .the-title h1,
.trend .content3 .the-title p{
  color: #ffffff;
}
.trend .content3 .the-title button{
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
.trend .content1{
  margin-top: 20px;
  width: 28%;
  height: 500px;
  margin-right: 20px;
  background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)),url("@/assets/Images/product-09.jpg");
  background-position: center;
  background-size: cover;
  position: relative;
}
.trend .content1 .the-title{
  position: absolute;
  bottom: 30px;
  left: 20px;
}
.trend .content1 .the-title h1,
.trend .content1 .the-title p{
  color: #ffffff;
}
.trend .content1 .the-title button{
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
.trend .content2{
  margin-top: 20px;
  width: 28%;
  height: 500px;
  margin-right: 20px;
  background-image: linear-gradient(rgba(255, 99, 71, 0.4),rgba(4,9,30,0.7)),url("@/assets/Images/product-08-a.jpg");
  background-position: center;
  background-size: cover;
  position: relative;
}
.trend .content2 .the-title{
  position: absolute;
  bottom: 30px;
  left: 20px;
}
.trend .content2 .the-title h1,
.trend .content2 .the-title p{
  color: #ffffff;
}
.trend .content2 .the-title button{
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
.shop1{
  margin-left: 30px;
  margin-right: 30px;
  margin-top: 15px;
  height: 278px;
  background-color: #BC95AD;
}
.shop1 .con{
  padding-left: 100px;
  padding-top: 30px;
}
.shop1 .con p{
  color: #fff;
  font-weight: bold;
  font-size: 14px;
  margin-bottom: 10px;
}
.shop1 .con h1{
  font-weight: 550;
  margin-bottom: 0px;
  margin-top: 10px;
}
.shop1 .con button{
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
.shop1 .con button:hover{
  background-image: linear-gradient(-225deg, #5D9FFF 0%, #B8DCFF 48%, #6BBBFF 100%);
  color: #222;
  font-weight: 600;
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
  margin-top: 20px;
  width: 32%;
  height: 390px;
  background-color: #BC95AD;
}
.detail .pic{
  width: 100%;
  height: 270px;
}
.detail .pic img{
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.detail .more{
  width: 100%;
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
  /* background-image: linear-gradient(to top, #09203f 0%, #537895 100%); */
  background-image: linear-gradient(45deg, #874da2 0%, #c43a30 100%);
  transition-duration: 0.4s;
}
.more .wrapper p{
  font-size: 16px;
  font-weight: 600;
}
.feature{
  margin-left: 30px;
  margin-right: 30px;
  margin-top: 15px;
  margin-bottom: 15px;
  display: flex;
}
.feature .left{
  width: 50%;
  height: 68vh;
  background-image: linear-gradient(to top, #a18cd1 0%, #fbc2eb 100%);
  display: flex;
  margin-right: 10px;
  justify-content: center;
}
.feature .left .con{
  margin-top: 30px;
  margin-left: 20px;
}
.feature .left .con button{
  width: 140px;
  height: 40px;
  border-radius: 8px;
  background-color: #6598BC;
  font-size: 16px;
  color: #FFFFFF;
  font-weight: 600;
  border: none;
  box-shadow: 5px 5px 5px 1px rgba(0,0,0,.6);
  margin-top: 20px;
  cursor: pointer;
}
.feature .product{
  margin-top: 50px;
  width: 100%;
  height: 280px;
}
.feature .product img{
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.feature .right{
  width: 50%;
  height: 68vh;
  margin-left: 10px;
  background-image: linear-gradient(120deg, #a1c4fd 0%, #c2e9fb 100%);
  display: flex;
  /* align-items: center; */
  justify-content: center;
}
.feature .right .con{
  margin-top: 30px;
  margin-left: 20px;
}
.feature .right .con button{
  width: 140px;
  height: 40px;
  border-radius: 8px;
  background-color: #6598BC;
  font-size: 16px;
  color: #FFFFFF;
  font-weight: 600;
  border: none;
  box-shadow: 5px 5px 5px 1px rgba(0,0,0,.6);
  margin-top: 20px;
  cursor: pointer;
}
.collection{
  height: 204px;
  background-color: #BC95AD;
  margin-left: 30px;
  margin-right: 30px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.collection p{
  margin-top: 4px;
  margin-bottom: 0;
}
.collection h1{
  margin-top: 10px;
  margin-bottom: 6px;
}
.collection h3{
  margin-top: 0;
  margin-bottom: 0;
}
.collection button{
  width: 140px;
  height: 40px;
  border-radius: 8px;
  background-color: #6598BC;
  font-size: 16px;
  color: #FFFFFF;
  font-weight: 600;
  border: none;
  box-shadow: 5px 5px 5px 1px rgba(0,0,0,.6);
  margin-top: 20px;
  cursor: pointer;
}
.men{
  margin-left: 30px;
  margin-right: 30px;
  margin-top: 15px;
  margin-bottom: 20px;
  height: 90vh;
  display: flex;
}
.men .left{
  width: 50%;
  height: 100%;
  margin-right: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  /* justify-content: center; */
}
.men .left .img{
  width: 560px;
  height: 400px;
}
.men .left p{
  margin-top: 10px;
  margin-bottom: 10px;
}
.men .left h1{
  margin-top: 0;
  margin-bottom: 0;
}
.men .left button{
  width: 140px;
  height: 40px;
  border-radius: 8px;
  background-color: #6598BC;
  font-size: 16px;
  color: #FFFFFF;
  font-weight: 600;
  border: none;
  box-shadow: 5px 5px 5px 1px rgba(0,0,0,.6);
  margin-top: 20px;
  cursor: pointer;
}
.men .left img{
  width: 100%;
  height: 100%;
}
.men .right{
  width: 50%;
  height: 100%;
  margin-left: 10px;
}
.men .right img{
  width: 100%;
  height: 100%;
}
.footer{
  height: 122px;
  background-color: #4391AA;
  margin-top: 15px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.followup{
  display: flex;
  align-items: center;
  margin-left: 70px;
}
.followup p{
  font-size: 20px;
  font-weight: 600;
  margin-right: 15px;
}
.followup img{
  width: 30px;
  height: 30px;
  margin-right: 15px;
  cursor: pointer;
}
.subscribe{
  margin-right: 70px;
}
.subscribe p{
  font-size: 16px;
  font-weight: 600;
  margin-bottom: 10px;
}
.subscribe input{
  width: 225px;
  height: 45px;
  padding-left: 60px;
  font-size: 16px;
  font-weight: 600;
  color: #222;
  outline: none;
}
.subscribe input::placeholder{
  color: #222;
}
.subscribe button{
  width: 122px;
  height: 50px;
  font-size: 16px;
  font-weight: 600;
  color: #FFFFFF;
  background-color: #4B43AA;
  border: none;
  cursor: pointer;
}
.subscribe button:hover{
  background-image: linear-gradient(to right, #f83600 0%, #f9d423 100%);
  box-shadow: 5px 5px 10px 2px rgba(0,0,0,.8);
  transition-duration: 0.4s;
}
</style>