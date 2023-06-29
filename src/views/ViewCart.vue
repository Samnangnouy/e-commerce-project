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
          <img src="@/assets/Images/search.png">
        </div>
        <input type="text" placeholder="Search here">
        <div class="icon1">
          <img src="@/assets/Images/shopping-cart.png">
        </div>
      </div>
    </div>
    <div class="relate-product">
      <h1>Your Cart</h1>
      <p>Please spend few minute to check your cart again</p>
    </div>
    <div class="container">
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
                                <img src="@/assets/Images/clothe3.jpg">
                                <div class="detail-product">
                                    <h2>Women Clothes</h2>
                                    <h2>Size small</h2>
                                </div>
                            </div>
                        </td>
                        <td>1</td>
                        <td>1</td>
                    </tr>
                </tbody>
            </table>
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
.container{
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
    background-color: blue
}
table td:nth-child(1) .image-box{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
table td:nth-child(1) .image-box img{
    width: 200px;
}
table td:nth-child(2){
    width: 150px;
    text-align: center;
    background-color: red;
}
table td:nth-child(3){
    width: 100px;
    text-align: center;
    background-color: #222;
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
  .footer{
    height: 122px;
    background-color: #4391AA;
    margin-top: 15px;
    margin-top: 30px;
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