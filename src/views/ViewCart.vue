<template>
  <div class="head">
    <div class="title">
      <h3>Hero Boots</h3>
    </div>
    <div class="content">
      <router-link to="/"><a href="#">Home |</a></router-link>
      <router-link to="/product"><a href="#">Product |</a></router-link>
      <a href="#">Contact |</a>
    </div>
    <div class="search">
      <div class="icon">
        <img src="@/assets/Images/search.png" />
      </div>
      <input type="text" placeholder="Search here" />
      <div class="icon1">
        <router-link to="/carts"><img src="@/assets/Images/shopping-cart.png"></router-link>
      </div>
    </div>
  </div>
  <div class="relate-product1">
    <h1>Your Cart</h1>
    <p>Please spend few minute to check your cart again</p>
  </div>
  <div class="container2">
    <table width="100%">
      <thead>
        <tr>
          <td>Item</td>
          <td>Price</td>
          <td>Quantity</td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            <div class="image-box">
              <div class="image">
                <img src="@/assets/Images/jacket.png" />
              </div>
              <div class="detail-product2">
                <h2>Women Clothes</h2>
                <h2>Size small</h2>
              </div>
            </div>
          </td>
          <td>
            <span>29.80$</span>
          </td>
          <td>
            <span>1</span>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
  <div class="coupon">
    <div class="left">
      <div class="content">
        <h1>Apply Coupon</h1>
        <input type="text" placeholder="Enter your coupun" />
        <input type="submit" value="Submit" />
      </div>
    </div>
    <div class="right">
      <div class="righ-content">
        <h1>Cart Total</h1>
        <table>
          <tr>
            <td>Company</td>
            <td>Contact</td>
          </tr>
        </table>
        <table>
          <tr>
            <td>Company</td>
            <td>Contact</td>
          </tr>
        </table>
        <table>
          <tr>
            <td>Company</td>
            <td>Contact</td>
          </tr>
        </table>
        <router-link to="/CustomerInfo"><button>Procced to checkout</button></router-link>
      </div>
    </div>
  </div>
  <div class="footer">
    <div class="followup">
      <p>Follow Us On</p>
      <img src="@/assets/Images/tik-tok.png" />
      <img src="@/assets/Images/instagram.png" />
      <img src="@/assets/Images/facebook.png" />
      <img src="@/assets/Images/twitter.png" />
    </div>
    <div class="subscribe">
      <p>Stay in Touch! Join Our Newletters</p>
      <input type="text" placeholder="Enter your email" />
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
  
  .relate-product1{
  height: 104px;
  background-color: #BC95AD;
  margin-top: 15px;
  margin-left: 10px;
  margin-right: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.relate-product1 h1{
  margin-top: 0;
  font-size: 32px;
  margin-bottom: 10px;
}
.relate-product1 p{
  font-size: 18px;
  color: #FFFFFF;
  margin-top: 0;
}
.container2{
    margin: 20px 20px;
}
table{
    /* background-color: red; */
    width: 100%;
    border-collapse: collapse;
    table-layout: fixed;
    white-space: nowrap;
}
table td:nth-child(1){
    width: 200px;
    text-align: center;
    /* background-color: blue; */
}
table td:nth-child(1) .image-box{
    width: 100%;
    height: 50%;
    display: flex;
    align-items: center;
}
table td:nth-child(1) .image-box .image{
    width: 300px;
    height: 300px;
    background-color: #ffffff;
    border: 1px solid black;
    margin-right: 30px;
    display: flex;
    align-items: center;
    justify-content: center;
}
table td:nth-child(1) .image-box .image img{
    width: 90%;
    height: 90%;
    object-fit: contain;
}
table td:nth-child(2){
    width: 100px;
    text-align: center;
    /* background-color: red; */
}
table td:nth-child(2) span{
    font-size: 24px;
    font-weight: bold;
    /* background-color: blue; */
    padding: 10px 15px;
}
table td:nth-child(3){
    width: 100px;
    text-align: center;
    /* background-color: yellow; */
}
table td:nth-child(3) span{
    font-size: 24px;
    font-weight: bold;
}
table thead{
    border: 1px solid #b2bbb2;
    border-left: none;
    border-right: none;
}
table thead td{
    font-weight: 700;
    text-transform: uppercase;
    font-size: 13px;
    padding: 18px 0;
}
table tbody tr td{
    padding-top: 15px;
}
table tbody td{
    font-size: 15px;
}
.coupon{
  width: 100%;
  /* background-color: red; */
  /* margin-left: 20px;
  margin-right: 20px; */
  display: flex;
  align-items: baseline;
}
.coupon .left{
  width: 40%;
  /* background-color: blue; */
}
.coupon .left .content{
  display: flex;
  flex-direction: column;
  margin-left: 10px;
}
.coupon .left .content input[type="text"]{
  width: 300px;
  height: 40px;
  font-size: 18px;
  padding-left: 20px;
  outline: none;
  background-color: #D18585;
  border: none;
  margin-bottom: 20px;
  border-radius: 8px;
  box-shadow: 2px 3px #fcf1f1;
}
.coupon .left .content input[type="submit"]{
  width: 150px;
  height: 40px;
  font-size: 18px;
  outline: none;
  background-color: #D18585;
  border: none;
  box-shadow: 2px 3px #fcf1f1;
}
.coupon .right{
  width: 50%;
  /* background-color: blue; */
  margin-left: 40px;
  background-color: #4391AA;
  display: flex;
  justify-content: center;

}
.coupon .right .righ-content{
  margin-left: 20px;
  margin-right: 20px;
  margin-bottom: 20px;
  
}
.coupon .right .righ-content table{
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width: 100%;
  margin-bottom: 6px;
}
.coupon .right .righ-content table td{
  border: 1px solid black;
  width: 100px;
  text-align: center;
  background-color: #ffffff;
  padding: 8px;
}
  .footer{
    height: 122px;
    background-color: #4391AA;
    margin-top: 15px;
    margin-top: 30px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .coupon .right .righ-content button{
    width: 300px;
    height: 52px;
    font-size: 18px;
    color: #ffffff;
    background-color: #D18585;
    border: none;
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
