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
    <div class="relate-product">
      <h1>Payment Details</h1>
      <p>Please spend few minute to complete your shipping payment information here</p>
    </div>
    <div class="customer3">
        <div class="customer3-info">
            <div class="email3">
                <div class="cus3-info">
                    <h3>Shipping address 12 waldo Point Road, Mishauken, NY 11200</h3>
                    <a href="">Edit</a>
                </div>
                <div class="cus3-info">
                    <h3>Shipping Method UPS Ground, $2.20</h3>
                    <a href="">Edit</a>
                </div>
            </div>
            <div class="shipping3">
                <h3>Payment Method</h3>
                <input class="input3" type="text" placeholder="Card Number">
                <div class="coun3">
                    <input type="text" placeholder="Name on card">
                    <input type="text" placeholder="MM/YY">
                    <input type="text" placeholder="CVV">
                </div>
            </div>
            <div class="shipping3">
                <h3>Billing Address</h3>
                <div class="billing">
                    <input type="radio" value="HTML">
                    <label for="html">Same as shipping address</label><br>
                </div>
                <div class="billing">
                    <input type="radio" value="HTML">
                    <label for="html">Same as shipping address</label><br>
                </div>
                <h3>Remember me</h3>
                <div class="billing">
                    <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
                    <label for="vehicle1"> Save my information for a faster checkout</label><br>
                </div>
            </div>    
        </div>
        <div class="summary">
          <h1>Summary(1 item)</h1>
          <table>
          <tr>
            <td>Subtotal</td>
            <td>$20.00</td>
          </tr>
        </table>
        <table>
          <tr>
            <td>Shipping</td>
            <td>$2.20</td>
          </tr>
        </table>
        <table>
          <tr>
            <td>Est. Taxes</td>
            <td>$1.40</td>
          </tr>
        </table>
        <div class="gift">
          <h1>Gift Card or discount code</h1>
          <div class="btn">
          <input type="text">
          <button>Apply</button>
        </div>
        </div>
        </div>
    </div>
    <router-link to="/Shipping"><button class="return">Return to Shipping Info</button></router-link>
    <router-link to="/Checkout"><button class="continue">Continue to Checkout Method</button></router-link>
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
    .relate-product{
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
  .relate-product h1{
    margin-top: 0;
    font-size: 32px;
    margin-bottom: 10px;
  }
  .relate-product p{
    font-size: 18px;
    color: #FFFFFF;
    margin-top: 0;
  }
  .customer3{
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 10px;
    display: flex;
  }
  .customer3 .customer3-info{
    width: 55%;
    background-color: #BC95AD;
    margin-right: 10px;
  }
  .customer3 .customer3-info .email3{
    margin-top: 10px;
    margin-left: 10px;
    margin-right: 10px;
  }
  .customer3 .customer3-info .email3 .cus3-info{
    border: 1px solid black;
    border-left: none;
    border-right: none;
    display: flex;
    align-items: baseline;
    justify-content: space-between;
  }
  .customer3 .customer3-info .email3 .cus3-info:nth-child(2){
    border: 1px solid black;
    border-left: none;
    border-right: none;
    border-top: none;
    display: flex;
    align-items: baseline;
    justify-content: space-between;
  }
  .customer3 .customer3-info .shipping3{
    margin-left: 10px;
    margin-right: 10px;
    font-size: 18px;
    width: 100%;
  }
  .customer3 .customer3-info .shipping3 h3{
    margin-bottom: 10px;
    margin-right: 20px;
  }
  .customer3 .customer3-info .shipping3 .input3{
    margin-right: 10px;
    width: 94%;
    height: 30px;
    font-size: 16px;
    padding-left: 20px;
    outline: none;
  }
  .customer3 .customer3-info .shipping3 .coun3{
    margin-right: 18px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .coun3 input{
    width: 200px;
    height: 30px;
    outline: none;
    margin-top: 10px;
  }
  .customer3 .customer-info3 .shipping3 h3{
    margin-bottom: 10px;
    margin-right: 20px;
    border-top: 1px solid black;
  }
  .customer3 .customer3-info .shipping3{
    margin-left: 10px;
    margin-right: 10px;
    font-size: 18px;
    width: 100%;
    margin-bottom: 10px;
  }
  .customer3 .customer3-info .shipping3 .billing{
    margin-right: 20px;
    height: 30px;
    border: 1px solid black;
    display: flex;
    align-items: center;
    background-color: #ffffff;
  }
  .customer3 .customer3-info .shipping3 .billing:nth-child(3){
    margin-right: 20px;
    height: 30px;
    border: 1px solid black;
    border-top: none;
    display: flex;
    align-items: center;
    background-color: #ffffff;
  }
  .customer3 .customer3-info .shipping3 .billing input{
    margin-right: 20px;
    margin-left: 20px;
  }
  .summary{
    padding: 10px;
    width: 45%;
    background-color: #BC95AD;
    margin-left: 10px;
    height: auto;
  }
  .summary table{
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width: 100%;
  margin-bottom: 6px;
}
.summary table td{
  border: 1px solid black;
  width: 100px;
  text-align: center;
  background-color: #ffffff;
  padding: 8px;
}
.gift{
  margin-top: 10px;
  border: 1px solid black;
  border-left: none;
  border-right: none;
}
.gift h1{
  margin-bottom: 10px;
}
.btn{
  width: 100%;
}
.btn input{
  width: 200px;
  height: 30px;
  outline: none;
  font-size: 18px;
}
.btn button{
  width: 100px;
  height: 37px;
  background-color: rgb(168, 119, 214);
  border: none;
  font-size: 18px;
  color: #ffffff;
  margin-left: 10px;
  margin-top: 10px;
  cursor: pointer;
  margin-bottom: 10px;
}
.return{
  width: 200px;
  height: 45px;
  background-color: rgb(168, 119, 214);
  border: none;
  font-size: 18px;
  color: #ffffff;
  margin-left: 10px;
  margin-top: 10px;
  cursor: pointer;
}
.continue{
  width: 300px;
  height: 45px;
  background-color: rgb(168, 119, 214);
  border: none;
  font-size: 18px;
  color: #ffffff;
  margin-left: 40px;
  margin-top: 10px;
  cursor: pointer;
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
  