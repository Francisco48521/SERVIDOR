# SERVIDOR<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <link rel="stylesheet" href="style.css">
</head>
  <div class="pricing-table">
    <div class="pricing-card">
      <h3 class="pricing-card-header">Minecraft pe</h3>
      <div class="price"><sup>$</sup>0<span>/USD</span></div>
      <ul>
        <li><strong>_________________</strong></li>
        <li><strong></strong>>Minecraft pe<</li>
        <li><strong></strong>Pirata 1.16.40.02</li>
        <li><strong></strong>$USD 0.00</li>
        <li><strong>_________________</strong></li>
      </ul>
      <a href="http://www.mediafire.com/file/e30umirwjohgpyn/minecraft-1-16-40.apk/file" class="order-btn">Order Now</a>
    </div>

    <div class="pricing-card">
      <h3 class="pricing-card-header">Minecraft pe</h3>
      <div class="price"><sup>$</sup>0<span>/USD</span></div>
      <ul>
        <li><strong>_________________</strong></li>
        <li><strong></strong>minecraft pe</li>
        <li><strong></strong>pirata 1.16.100.53</li>
        <li><strong></strong>$USD 0.00</li>
        <li><strong>_________________</strong></li>
      </ul>
      <a href="http://www.mediafire.com/file/m4z2j9gyk36j824/minecraft-pe-1-16-100-53.rar/file" class="order-btn">Order Now</a>
    </div>

    <div class="pricing-card">
      <h3 class="pricing-card-header">Minecraft pe</h3>
      <div class="price"><sup>$</sup>0<span>/USD</span></div>
      <ul>
        <li><strong>_________________</strong></li>
        <li><strong></strong>minecraft pe</li>
        <li><strong>pirata ???</strong></li>
        <li><strong></strong>$USD 0.00</li>
        <li><strong>_________________</strong></li>
      </ul>
      <a href="#" class="order-btn">Order Now</a>
    </div>

    <div class="pricing-card">
      <h3 class="pricing-card-header">Minecraft pe</h3>
      <div class="price"><sup>$</sup>0<span>/USD</span></div>
      <ul>
        <li><strong>_________________</strong></li>
        <li><strong></strong>minecraft pe</li>
        <li><strong>pirata ???</strong></li>
        <li><strong></strong>$USD 0.00</li>
        <li><strong>_________________</strong></li>
      </ul>
      <a href="#" class="order-btn">Order Now</a>
    </div>
  </div>
</body>
</html>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Open Sans",sans-serif;
  text-decoration: none;
  list-style: none;
}

body{
  background-color: #0c0d22;
  min-height: 100vh;
  display: flex;
  align-items: center;
}

.pricing-table{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  width: min(1600px, 100%);
  margin: auto;
}

.pricing-card{
  flex: 1;
  max-width: 360px;
  background-color: #fff;
  margin: 20px 10px;
  text-align: center;
  cursor: pointer;
  overflow: hidden;
  color: #2d2d2d;
  transition: .3s linear;
}

.pricing-card-header{
  background-color: #0fbcf9;
  display: inline-block;
  color: #fff;
  padding: 12px 30px;
  border-radius: 0 0 20px 20px;
  font-size: 16px;
  text-transform: uppercase;
  font-weight: 600;
  transition: .4s linear;
}

.pricing-card:hover .pricing-card-header{
  box-shadow: 0 0 0 26em #0fbcf9;
}

.price{
  font-size: 70px;
  color: #010405;
  margin: 40px 0;
  transition: .2s linear;
}

.price sup, .price span{
  font-size: 22px;
  font-weight: 700;
}

.pricing-card:hover ,.pricing-card:hover .price{
  color: #fff;
}

.pricing-card li{
  font-size: 16px;
  padding: 10px 0;
  text-transform: uppercase;
}

.order-btn{
  display: inline-block;
  margin-bottom: 40px;
  margin-top: 80px;
  border: 2px solid #0fbcf9;
  color: #0fbcf9;
  padding: 18px 40px;
  border-radius: 8px;
  text-transform: uppercase;
  font-weight: 500;
  transition: .3s linear;
}

.order-btn:hover{
  background-color: #0fbcf9;
  color: #fff;
}

@media screen and (max-width:1100px){
  .pricing-card{
    flex: 50%;
  }
}
