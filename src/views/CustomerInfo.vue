<template>
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
          <img src="@/assets/Images/search.png" />
        </div>
        <input type="text" placeholder="Search here" />
        <div class="icon1">
          <img src="@/assets/Images/shopping-cart.png" />
        </div>
      </div>
    </div>
    <div class="relate-product">
      <h1>Your Information</h1>
      <p>Please spend few minute to complete your information here</p>
    </div>
    <div class="customer">
        <div class="customer-info">
            <div class="email">
                <h2>Customer Information</h2>
                <div class="title">
                    <h2>Already have an account?</h2>
                    <a href="">Login</a>
                </div>
            </div>
            <input class="input1" type="text" placeholder="Your email">
            <div class="shipping">
              <h1>Shipping Address</h1>
              <div class="name">
                <input type="text" placeholder="First Name">
                <input type="text" placeholder="Last Name">
              </div>
              <input class="input1" type="text" placeholder="Company">
              <div class="add">
                <input type="text" placeholder="Address">
                <input type="text" placeholder="Apt">
              </div>
              <div class="coun">
                <input type="text" placeholder="Country">
                <input type="text" placeholder="State">
                <input type="text" placeholder="Zip">
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
            <td>-- --</td>
          </tr>
        </table>
        <table>
          <tr>
            <td>Est. Taxes</td>
            <td>-- --</td>
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
    <button class="return">Return to cart</button>
    <button class="continue">Continue to Shipping Method</button>
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
  .customer{
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 10px;
    display: flex;
  }
  .customer .customer-info{
    width: 55%;
    background-color: #BC95AD;
    margin-right: 10px;
  }
  .customer .customer-info .email{
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    padding-left: 10px;
    padding-right: 10px;
  }
  .customer .customer-info .email .title{
    display: flex;
    align-items: baseline;
  }
  .customer .customer-info .input1{
    margin-left: 10px;
    margin-right: 10px;
    width: 94%;
    height: 30px;
    font-size: 20px;
    padding-left: 20px;
    outline: none;
  }
  .shipping h1{
    margin-left: 10px;
  }
  .name,
  .add,
  .coun{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-around;
  }
  .name input{
    width: 45%;
    height: 30px;
    padding-left: 10px;
    outline: none;
    margin-bottom: 10px;
  }
  .add input:nth-child(1){
    width: 60%;
    height: 30px;
    padding-left: 10px;
    outline: none;
    margin-bottom: 10px;
    margin-top: 10px;
    margin-left: 3px;
  }
  .add input:nth-child(2){
    width: 30%;
    height: 30px;
    padding-left: 10px;
    outline: none;
    margin-bottom: 10px;
    margin-top: 10px;
    margin-left: 7px;
  }
  .coun input{
    width: 200px;
    height: 30px;
    outline: none;
    padding-left: 10px;
    margin-bottom: 10px;
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
  