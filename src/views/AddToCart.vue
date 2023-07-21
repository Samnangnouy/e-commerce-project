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
    <div class="details">
        <div class="left">
            <div class="object">
                <img src="@/assets/Images/jacket.png">
            </div>
            <div class="relate">
                <div class="relate-box">
                    <img src="@/assets/Images/jacket.png">
                </div>
                <div class="relate-box">
                    <img src="@/assets/Images/jacket.png">
                </div>
                <div class="relate-box">
                    <img src="@/assets/Images/jacket.png">
                </div>
                <div class="relate-box">
                    <img src="@/assets/Images/jacket.png">
                </div>
            </div>
        </div>
        <div class="right">
            <div class="add-item">
              <h3>Item added to cart</h3>
              <h3>My Cart</h3>
            </div>
            <h4>Favourite Cotton Jersy Short</h4>
            <h4>Qty: 1 | $20</h4>
            <div class="button">
              <button>View Cart</button>
              <button>Checkout</button>
            </div>
        </div>
    </div>
    <div class="relate-product">
      <h1>Related Products</h1>
      <p>Summer Collection New Modern Design</p>
    </div>
    <div class="relate-info">
    <div class="relate-detail">
      <div class="relate-pic">
        <img src="@/assets/Images/clothes4.jpg">
      </div>
      <div class="relate-more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="relate-wrapper">
          <button>Details</button>
          <p>32.12$</p>
        </div>
      </div>
    </div>
    <div class="relate-detail">
      <div class="relate-pic">
        <img src="@/assets/Images/clothes5.jpg">
      </div>
      <div class="relate-more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="relate-wrapper">
          <button>Details</button>
          <p>32.12$</p>
        </div>
      </div>
    </div>
    <div class="relate-detail">
      <div class="relate-pic">
        <img src="@/assets/Images/clothes6.jpg">
      </div>
      <div class="relate-more">
        <div class="title">
          <p>Ninedaily Women's 3/4 Sleeve</p>
        </div>
        <div class="relate-wrapper">
          <button>Details</button>
          <p>32.12$</p>
        </div>
      </div>
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
  .details{
    margin-top: 15px;
    /* width: 100%; */
    height: 400px;
    /* background-color: rgb(155, 172, 187); */
    padding: 10px;
    display: flex;
  }
  .details .left{
    width: 60%;
    height: 100%;
    /* background-color: #4B43AA; */
    /* border: 1px solid blueviolet; */
  }
  .details .left .object{
    width: 100%;
    height: 65%;
    background-color: #D9D9D9;
    /* border: 1px solid black; */
  }
  .details .left .object img{
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
  .details .left .relate{
    width: 100%;
    height: 40%;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .details .left .relate .relate-box{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 23%;
    height: 87%;
    /* border: 1px solid blueviolet; */
    background-color: #D9D9D9;
    border-radius: 10px;
    border-left: none;
    border-bottom: none;
  }
  .details .left .relate .relate-box:nth-child(4){
    width: 23%;
    height: 87%;
    border-left: none;
    border-bottom: none;
    border-right: none;
  }
  .details .left .relate img{
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
  .details .right{
    width: 50%;
    height: 100%;
    background-color: #BC95AD;
    margin-left: 20px;
    padding-left: 20px;
    padding-right: 20px;
  }
  .right .add-item{
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: #ffffff;
    border-bottom: 1px solid #ffffff;
  }
  .right .button button{
    width: 200px;
    height: 50px;
    background-color: rgb(111, 63, 156);
    border: none;
    font-size: 18px;
    color: #ffffff;
    cursor: pointer;
  }
  .right .button button:nth-child(2){
    width: 200px;
    height: 50px;
    background-color: rgb(94, 47, 138);
    border: none;
    margin-left: 20px;
    font-size: 18px;
    color: #ffffff;
    cursor: pointer;
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
.relate-info{
  margin-left: 30px;
  margin-right: 30px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.relate-detail{
  margin-top: 20px;
  width: 32%;
  height: 390px;
  background-color: #BC95AD;
}
.relate-detail .relate-pic{
  width: 100%;
  height: 270px;
}
.relate-detail .relate-pic img{
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.relate-detail .relate-more{
  width: 100%;
  height: 120px;
  background-color: #D9D9D9;
}
.relate-more .title{
  display: flex;
  align-items: center;
  justify-content: center;
}
.relate-more .title p{
  margin-top: 10px;
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 600;
}
.relate-more .relate-wrapper{
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-right: 50px;
  margin-left: 50px;
}
.relate-more .relate-wrapper button{
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
.relate-more .relate-wrapper button:hover{
  /* background-image: linear-gradient(to top, #09203f 0%, #537895 100%); */
  background-image: linear-gradient(45deg, #874da2 0%, #c43a30 100%);
  transition-duration: 0.4s;
}
.relate-more .relate-wrapper p{
  font-size: 16px;
  font-weight: 600;
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