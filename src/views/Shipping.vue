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
      <h1>Your Shipping Information</h1>
      <p>Please spend few minute to complete your shipping information here</p>
    </div>
    <div class="customer2">
        <div class="customer2-info">
            <div class="email2">
                <h3>Customer Information</h3>
                <div class="cus2-info">
                    <h3>Shipping address 12 waldo Point Road, Mishauken, NY 11200</h3>
                    <a href="">Edit</a>
                </div>
            </div>
            <div class="shipping2">
                <h3>Shipping Method</h3>
                <input type="radio" value="HTML">
                <label for="html">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;UPS Ground&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $2.20</label><br>
                <input type="radio" value="CSS">
                <label for="css">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;UPS 3 Day Select&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $5.50</label><br>
                <input type="radio" value="JavaScript">
                <label for="javascript">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;UPS 2nd Day Air&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $9.50</label><br>
                <input type="radio" value="JavaScript">
                <label for="javascript">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;UPS Next Day Air&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $1.40</label>
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
    <router-link to="/CustomerInfo"><button class="return">Return to Customer Info</button></router-link>
    <router-link to="/Payment"><button class="continue">Continue to Payment Method</button></router-link>
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
  .customer2{
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 10px;
    display: flex;
  }
  .customer2 .customer2-info{
    width: 55%;
    background-color: #BC95AD;
    margin-right: 10px;
  }
  .customer2 .customer2-info .email2{
    border: 1px solid black;
    border-left: none;
    border-right: none;
    margin-top: 10px;
    margin-left: 10px;
    margin-right: 10px;
  }
  .customer2 .customer2-info .email2 .cus2-info{
    display: flex;
    align-items: baseline;
    justify-content: space-between;
  }
  .customer2 .customer2-info .shipping2{
    margin-left: 10px;
    margin-right: 10px;
    font-size: 18px;
  }
  .shipping2 input{
    width: 40px;
    margin-bottom: 20px;
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
  