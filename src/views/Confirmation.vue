<template>
  <div class="head1">
    <div class="title1">
      <h3>Order 1234567890 Confirmation</h3>
    </div>
  </div>
  <div class="container4">
    <h4>hello@sitename.com</h4>
    <h4>to me</h4>
    <div class="content4">
      <h2>Hero Boots</h2>
      <h4>Thank you for your purchese!</h4>
      <h5>
        Hi Michael, we're getting your order ready to be shipped. We will notify
        you when it has been sent.
      </h5>
      <div class="visit4">
        <router-link to="/viewCarts"><button class="btn-order">View your order</button></router-link>
        <h4>Or</h4>
        <router-link to="/product"><a class="store" href="#">Visit our store</a></router-link>
      </div>
    </div>
  </div>
  <div class="order-sum4">
    <h3>Order Summary</h3>
    <div class="detail-pro4">
      <div class="product4">
        <div class="pic4">
          <img src="@/assets/Images/clothes4.jpg" />
        </div>
        <div class="pro-detail4">
          <h4>Bird Nerd T-shirt</h4>
          <h4>Size small</h4>
        </div>
      </div>
      <div class="price4">
        <h3>$20.00</h3>
      </div>
    </div>
  </div>
  <div class="subtotal4">
    <div class="sub-title4">
      <h4>Subtotal</h4>
      <h4>Shipping</h4>
      <h4>tax</h4>
      <h4>Total</h4>
    </div>
    <div class="sub-price4">
      <h4>$20.00</h4>
      <h4>$2.20</h4>
      <h4>$1.40</h4>
      <h4>$23.60</h4>
    </div>
  </div>
  <h3>Customer Information</h3>
  <div class="shipping">
    <div class="shipping-add">
      <h4>Shipping Address</h4>
      <h4>Kenny Bostic</h4>
      <a href="">12 Waldo Point Road, Mishauken, NY11200, United State</a>
    </div>
    <div class="shipping-add">
      <h4>Billing Address</h4>
      <h4>Kenny Bostic</h4>
      <a href="">12 Waldo Point Road, Mishauken, NY11200, United State</a>
    </div>
  </div>
  <div class="shipping">
    <div class="shipping-add">
      <h4>Shipping Method</h4>
      <h4>USP Ground (Estimate ship time of 3-6 days)</h4>
    </div>
    <div class="shipping-add">
      <h4>Payment Method</h4>
      <img src="@/assets/Images/tik-tok.png" />
      <h4>Ending in 3217 - $23.60</h4>
    </div>
  </div>
  <div class="footer1">
    <div class="followup1">
      <p>
        If you have any question, reply to this email or contact us at
        hell0@sitename.com
      </p>
    </div>
  </div>
</template>

<style>
* {
  font-family: "Inria Serif";
}
.head1{
  height: 70px;
  background-color: #4391aa;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-left: 80px;
  padding-right: 80px;
}
.title1 h3 {
  font-size: 20px;
  color: #fff;
}
.container4 {
  border-bottom: 1px solid black;
  border-top: 1px solid black;
  margin: 20px;
}
.container4 .content4 {
  margin-left: 40px;
}
.container4 .content4 h2,
.container4 .content4 h4,
.container4 .content4 h5 {
  margin-left: 0;
  margin-bottom: 6px;
  margin-top: 10px;
}
.container4 h4 {
  margin-bottom: 0;
  margin-top: 4px;
  margin-left: 20px;
}
.container4 .visit4 {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}
.container4 .visit4 .btn-order {
  width: 200px;
  height: 37px;
  background-color: rgb(168, 119, 214);
  border: none;
  font-size: 18px;
  color: #ffffff;
  margin-top: 10px;
  cursor: pointer;
  margin-right: 20px;
}
.container4 .visit4 a .store{
  margin-left: 20px;
  font-size: 18px;
}
.order-sum4 {
  margin: 20px;
  padding-bottom: 20px;
  border-bottom: 1px solid black;
}
.order-sum4 h3 {
  margin-left: 60px;
}
.order-sum4 .detail-pro4 {
  margin-left: 40px;
  margin-right: 40px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.order-sum4 .detail-pro4 .product4 {
  width: 50%;
  display: flex;
  align-items: center;
}
.order-sum4 .detail-pro4 .product4 .pic4 {
  width: 300px;
  height: 200px;
  border: 1px solid black;
  margin-left: 20px;
  background-color: #ffffff;
  display: flex;
  align-items: center;
  justify-content: center;
}
.order-sum4 .detail-pro4 .product4 img {
  width: 90%;
  height: 90%;
  object-fit: contain;
}
.order-sum4 .detail-pro4 .product4 .pro-detail4 {
  margin-left: 20px;
}
.subtotal4 {
  margin-right: 60px;
  margin-left: 20px;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  border-bottom: 1px solid black;
}
.subtotal4 .sub-title4 {
  margin-right: 100px;
}
.subtotal4 .sub-price4 {
  margin-left: 100px;
}
h3{
  margin-left: 20px;
}
 .shipping{
    margin-left: 20px;
    margin-right: 20px;
    font-size: 18px;
    display: flex;
    margin-bottom: 20px;
  }
  .shipping .shipping-add{
    width: 50%;
    margin-right: 20px;
  }
  .shipping .shipping-add h4{
    margin-top: 8px;
    margin-bottom: 8px;
  }
  .shipping .shipping-add img{
    width: 30px;
    height: 20px;
  }
  .shipping h3{
    margin-bottom: 10px;
    margin-right: 20px;
  }
.footer1 {
  height: 70px;
  background-color: #4391aa;
  margin-top: 15px;
  margin-top: 30px;
}
.order-sum .detail-pro .price {
  width: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.followup1 {
  display: flex;
  align-content: center;
  justify-content: center;
}
.followup1 p {
  font-size: 20px;
  font-weight: 600;
}
</style>
