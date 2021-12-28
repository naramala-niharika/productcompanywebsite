# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
Layout CSS
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/u2.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```
home
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/u1.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Naramala Niharika
      </div>
    </div>
  </body>
</html>
```
products
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/n1.png" alt="product image">
                  </div>
                  <div class="itemname">GoogleDrive</div>
                  <div class="itemprice">Price: Rs.10,000 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/n2.png"  alt="product image">
                  </div>
                  <div class="itemname">Gmail</div>
                  <div class="itemprice">Price: Rs.7,000 </div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/n3.png"  alt="product image">
                </div>
                <div class="itemname">GooglePhotos</div>
                <div class="itemprice">Price: Rs.5,500 </div>
          </div>

           <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n4.jpg"  alt="product image">
            </div>
            <div class="itemname">Google Play Movies and Tv</div>
            <div class="itemprice">Price: Rs.9,000 </div>
          </div> 

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n5.png"  alt="product image">
            </div>
            <div class="itemname">Google meet</div>
            <div class="itemprice">Price: Rs.6,300 </div>  
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n6.png"  alt="product image">
            </div>
            <div class="itemname">Google Play games</div>
            <div class="itemprice">Price: Rs.10,000</div>
          </div>

            <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n7.jpg"  alt="product image">
            </div>
            <div class="itemname">Google play store</div>
            <div class="itemprice">Price: Rs.10,000</div>
          </div>  

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n8.png"  alt="product image">
            </div>
            <div class="itemname">Google Maps</div>
            <div class="itemprice">Price: Rs.5,000</div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n9.png"  alt="product image">
            </div>
            <div class="itemname">GooglePay</div>
            <div class="itemprice">Price: Rs.6,300</div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n10.png"  alt="product image">
            </div>
            <div class="itemname">Google Voice</div>
            <div class="itemprice">Price: Rs.2,800</div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n11.jpg"  alt="product image">
            </div>
            <div class="itemname">chrome</div>
            <div class="itemprice">Price: Rs.4,700</div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n12.jpg"  alt="product image">
            </div>
            <div class="itemname">Google classroom</div>
            <div class="itemprice">Price: Rs.3,100</div>
          </div>

      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Naramala Niharika
      </div>
    </div>
  </body>
</html>
```
people
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Google</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/my pic.jpeg" alt="product image">
                </div>
                <div class="itemname">Naramala Niharika</div>
                <div class="itemprice">CEO</div>

            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/d1.jpg"  alt="product image">
                </div>
                <div class="itemname">Shaheer</div>
                <div class="itemprice">DSM</div>
            </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/d2.jpg"  alt="product image">
              </div>
              <div class="itemname">Junkook</div>
              <div class="itemprice">Assistant HR </div>
            </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/d3.jpg"  alt="product image">
              </div>
              <div class="itemname">Arjun</div>
              <div class="itemprice">HR </div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/d4.jpg"  alt="product image">
            </div>
            <div class="itemname">Siddharth shukla</div>
            <div class="itemprice">RSM </div>
        </div> 
        
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/d5.jpg"  alt="product image">
          </div>
          <div class="itemname">Karan Mehra</div>
          <div class="itemprice">senior manager</div>
      </div>

          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Vasu health Care Private Limited, Developed by Naramala Niharika
    </div>
  </div>
</body>
</html>
```
contactus
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Google Company</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address: Flat no-502,Mokshitha Enlave,Bhanu nagar,MK Naidu colony,Tirupati <br></li>
              <li>Contact:9391547681;<br></li>
              <li>E-mail:niharika.naramala@gmail.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 bakers ltd, Developed by:Naramala Niharika
      </div>
    </div>
  </body>
</html>
```


## OUTPUT:

### Home Page:

![output](https://github.com/naramala-niharika/productcompanywebsite/blob/main/Home.PNG?raw=true)
### products
![output](https://github.com/naramala-niharika/productcompanywebsite/blob/main/products.PNG?raw=true)
### people
![output](https://github.com/naramala-niharika/productcompanywebsite/blob/main/people.PNG?raw=true)
### contactus
![output](https://github.com/naramala-niharika/productcompanywebsite/blob/main/contact%20us.PNG?raw=true)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
