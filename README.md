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
HOME PAGE:
```

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SOFTWARE ISLAND</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">SOFTWARE ISLAND</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/image.png" alt="Image" />
          <div class="contenttext">
            Welcome to SOFTWARE ISLAND!
             There are many types of software that people and businesses use for purposes like 
             organization, entertainment and file management on a variety of devices,including
             computers,tablets and mobile phones.If you developed software that can benefit people 
             or businesses,learning how to market and sell your product is essential to gaining
             users and earning a profit. 
            <br />
            A Cloud based IT process management solution designed to help businesses automate
            requirements collection to project planning,tracking and quality management on a 
            unified platform.
           
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Note worthy software </li>
              <li>Anywhere, anytime access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EDUSOFT PRIVATE LIMITED, Developed by NAVEEN
      </div>
    </div>
  </body>
</html>
```
PEOPLE PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SOFTWARE ISLAND</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">SOFTWARE ISLAND</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/BLAKE ROSS.png"  alt="product image">
      </div>
         <div class="itemname">Head of the company
           <br>
           (BLAKE ROSS)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/PABLO PICASSO.png"  alt="product image">
      </div>
         <div class="itemname">Manager
           <br>
           (PABLO PICASSO)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/SUNDAR PICHAI.png"  alt="product image">
      </div>
         <div class="itemname">Assistant class <br>(SUNDAR PICHAI)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/SIMON WILLISON.png"  alt="product image">
      </div>
         <div class="itemname">Product Department Head <br> (SIMON WILLISON))</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/J.R.SMITH RESIGNS.png"  alt="product image">
      </div>
         <div class="itemname">Deliver Department Head <br>(J.R.SMITH RESIGNS)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/THOMAS REARDON.png"  alt="product image">
      </div>
         <div class="itemname">Chennai Branch Head <br> (THOMAS REARDON)</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EDUSOFT PRIVATE LIMITED, Developed by NAVEEN
      </div>
    </div>
  </body>
</html>
```
PRODUCT PAGE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SOFTWARE ISLAND</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">SOFTWARE ISLAND</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/PICASSO.png" alt="product image">
                  </div>
                  <div class="itemname">PICASSO</div>
                  <div class="itemprice">Price:Rs.10,000</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/PYTHON.png"  alt="product image">
                  </div>
                  <div class="itemname">PYTHON</div>
                  <div class="itemprice">Price:Rs.8999</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ANACONDA.png"  alt="product image">
                  </div>
                  <div class="itemname">ANACONDA</div>
                  <div class="itemprice">Price: Rs.7599 </div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/INTERNET EXPLORER.png"  alt="product image">
                </div>
                <div class="itemname">INTERNET EXPLORER</div>
                <div class="itemprice">Price: 5599 </div>
            </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/GOOGLE.png"  alt="product image">
              </div>
              <div class="itemname">GOOGLE</div>
              <div class="itemprice">Price: Rs.15,000 </div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/SKYPE.png"  alt="product image">
            </div>
            <div class="itemname">SKYPE</div>
            <div class="itemprice">Price: Rs.12,000 </div>
        </div>

        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/MICROSOFT SILVERLIGHT.png"  alt="product image">
          </div>
          <div class="itemname">MICROSOFT SILVERLIGHT</div>
          <div class="itemprice">Price: Rs.5,000.00 </div>
      </div>

      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/MANGO.png"  alt="product image">
        </div>
        <div class="itemname"></div>
        <div class="itemprice">Price: Rs.1,200 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/FUSION360.png"  alt="product image">
      </div>
      <div class="itemname">FUSION360</div>
      <div class="itemprice">Price: Rs.1999 </div>
    </div>

    <div class="productitem"> 
       <div class="itemimage">
       <img src="/static/img/FIRE FOX.png"  alt="product image">
       </div>
       <div class="itemname">FIRE FOX</div>
       <div class="itemprice">Price: Rs.2229.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/DJANGO.png"  alt="product image">
    </div>
       <div class="itemname">DJANGO</div>
       <div class="itemprice">Price: Rs.15,000 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/AVG.png"  alt="product image">
     </div>
        <div class="itemname">AVG</div>
        <div class="itemprice">Price: Rs.2559 </div>
      </div>
    </div>
  </div>        
  </div>
    <div class="footer">
      Copyright &#169; 2021 EDUSOFT PRIVATE LIMITED, Developed by NAVEEN
    </div>
  </div>
 </body>
</html>
```
CONTACT PAGE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SOFTWARE ISLAND</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">SOFTWARE ISLAND</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address:CHENNAI<br></li>
              <li>Contact:975321460;<br></li>
        
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 SOFTWARE ISLAND DEVELOPED BY NAVEEN
      </div>
    </div>
  </body>
</html> 
```
CSS LAYOUT
```
* {
  box-sizing: border-box;
  font-family:emoji;
}
body {
  background-color: #fefeff;
  color: #070707;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px #afbae0;
}

.banner {
  display: block;
  width: 100%;
  height: 500px;
  text-align: right;
  font-size: 65px;
  background-image: url("/static/img/background1.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 230px;
  color: #0a090a;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #afbae0;
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
  color: #080808;
}

.menuitem a {
  text-decoration: none;
  color: #080808;
}

.content {
  display: block;
  width: 100%;
  background-color: #afbae0;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: #afbae0;
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
  background-color: #afbae0;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #000000;
}
```
## OUTPUT:
![](home.png)
![](people.png)
![](product.png)
![](contact.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
