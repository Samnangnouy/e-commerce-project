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
  <div class="in-touch">
    <div class="message">
      <h1>Get In Touch!!</h1>
      <p>Want to get in touch? We'd love to hear from you. Here's how you can reach us...</p>
    </div>
    <div class="contact-pic">
      <img src="@/assets/Images/call.jpg">
    </div>
  </div>
  <div class="contact">
    <div class="phone">
      <img src="@/assets/Images/phone.png">
      <h4>Talk to sales</h4>
      <p>Interest in Hero Boot e-commerce? Just pick up the phone</p>
      <p>to chat with a member of our sales team.</p>
      <h4>+353 1 512 4400</h4>
    </div>
    <div class="phone">
      <img src="@/assets/Images/message.png">
      <h4>Contact Customer Support</h4>
      <p>Sometimes you need a little help from your friends. Or a</p>
      <p>Hero Boot support rep. Don't worry... we're here for you.</p>
      <h4>Email: heroboot@gmail.com</h4>
    </div>
  </div>
  <div class="address">
    <p>If you have a problem want to direct to us by the address</p>
    <p>#143, St105, Khan Boeng KengKang, Phnom Penh, Cambodia</p>
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
.in-touch{
  margin-top: 20px;
  margin-left: 20px;
  margin-right: 20px;
  background-color: rgb(212, 202, 202);
  height: 300px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.in-touch .message{
  margin-left: 100px;
  width: 32%;
}
.in-touch .contact-pic{
  width: 40%;
  height: 100%;
}
.in-touch .contact-pic img{
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-top-left-radius: 30%;
}
.contact{
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: -30px;
}
.contact .phone{
  width: 40%;
  background-color: aliceblue;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding-top: 40px;
  padding-bottom: 40px;
  margin-right: 10px;
  margin-left: 10px;
}
.contact .phone p{
  letter-spacing: 1px;
  margin-top: 4px;
  margin-bottom: 4px;
}
.contact .phone img{
  width: 50px;
  height: 50px;
}
.address{
  margin-top: 30px;
  height: auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.address p{
  margin: 4px;
  letter-spacing: 2px;
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