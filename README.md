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

### Layout.css
~~~
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
  font-family: 'Times New Roman', Times, serif;
  background-image: url("/static/img/prana4.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #ffffff;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bc3ff;
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
  color: #b0aeb4;
}

.menuitem a {
  text-decoration: none;
  color: #ffffff;
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
  background-color: #0c0c0c;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #fcf7f7;
}

~~~

### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title> SAW Secutiry Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">S.A.W Security Ltd.,</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/pran.jpg" alt="Building" />
          <div class="contenttext">
            Public statement about information security at S.A.W Access

 
 
            S.A.W is committed to protecting its information assets to satisfy the company business objectives and meet the information security requirements of its customers while maintaining the safety of individuals and protecting their right to privacy. The Information Security Policy expresses the company intentions and commitment towards these goals.
            This Statement complements S.A.W Information Security Policy and provides a summary of the company internal security policies and procedures which constitute the security baseline that governs the company Software as a Service (SaaS) Platform. The Statement aim is to provide assurance to interested parties about the security of the SaaS applications, as well as the data contained within them.
                 
            
            
            The Principle of Least Privilege (POLP) is enshrined at S.A.W in policy and in culture.
            
            Access is granted on a Need to Know or Need to Use basis only.
            
           . If you have any questions about the below, please contact us at 
            
           
            <ul>
              <li>S.A.W closely manages suppliers using risk management principles.</li>
              <li>S.A.W hardens all network services and firewalls.</li>
              <li>AES-256 is used to protect data at rest.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 SAW Secutiry Ltd., Developed by Pranave B.
      </div>
    </div>
  </body>
</html>

~~~
### Products Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SAW Secutiry Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">SAW Secutiry Ltd.,</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/s1.jpg" alt="product image">
                  </div>
                  <div class="itemname">AVG antivirus</div>
                  <div class="itemprice">Price: Rs.500 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/s2.png"  alt="product image">
                  </div>
                  <div class="itemname">Avast antivirus</div>
                  <div class="itemprice">Price: Rs.1000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s3.jpeg"  alt="product image">
                </div>
                <div class="itemname">Kapersky</div>
                <div class="itemprice">Price: Rs.650 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s4.png"  alt="product image">
                </div>
                <div class="itemname">Web Titan</div>
                <div class="itemprice">Price: Rs.1200.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s5.jpg"  alt="product image">
                </div>
                <div class="itemname">Web Root</div>
                <div class="itemprice">Price: Rs.1350 </div>
              </div>
              <div class="productitem">
                <div class="itemimage">
                <img src="/static/img/s6.png"  alt="product image">
                </div>
                <div class="itemname">Teramind</div>
                <div class="itemprice">Price: Rs.1780 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s7.png"  alt="product image">
                </div>
                <div class="itemname">Zone Alarm</div>
                <div class="itemprice">Price: Rs.850.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s8.png"  alt="product image">
                </div>
                <div class="itemname">Barracuda</div>
                <div class="itemprice">Price: Rs.1800</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s9.png"  alt="product image">
                </div>
                <div class="itemname">Turbo VPN</div>
                <div class="itemprice">Price: Rs.500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s10.jpeg"  alt="product image">
                </div>
                <div class="itemname">Tunnel Bear</div>
                <div class="itemprice">Price: Rs.2800.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s11.png"  alt="product image">
                </div>
                <div class="itemname">Solar Winds</div>
                <div class="itemprice">Price: Rs.2500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s12.png"  alt="product image">
                </div>
                <div class="itemname">Acunetix</div>
                <div class="itemprice">Price: Rs.1,799.00 </div>
              </div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 SAW Secutiry Ltd., Developed by Pranave B.
      </div>
    </div>
  </body>
</html>
~~~
### People page:
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>SAW Secutiry Ltd.</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/icon.png" type="image/x-icon" />
    </head>
    <body>
        <div class="container">
            <div class="banner">SAW Secutiry Ltd.,</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>
                <div class="menuitem"><a href="/static/products.html">Products</a></div>
                <div class="menuitemselected"><a href='/static/people.html'>people</a></div>
                <div class="menuitem"><a href='/static/contact Us.html'>contact Us</a></div>
            </div>
            <div class="content">
                <div class="productcontent">
                    <h1>Our Crew Welcomes You All</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/P1.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Executive Officer</div>
                            <div class="itemprice">alexa</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/P2.jpeg" alt="people image">
                            </div>
                            <div class="itemname">Chief Financial Officer</div>
                            <div class="itemprice">kim</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/P3.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Operating Officer</div>
                            <div class="itemprice">srisha</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/P41.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Marketing Officer</div>
                            <div class="itemprice">asifa</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/P5.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Technology Officer</div>
                            <div class="itemprice">Rohit</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/P6.jpg" alt="people image">
                            </div>
                            <div class="itemname">President</div>
                            <div class="itemprice">sahaa</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 SAW Secutiry Ltd., Developed by Pranave B.
            </div>
            </div>
        </div>
    </body>
</html>
~~~
### Contact Us page:
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>SAW Secutiry Ltd.,</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/icon.png" type="image/x-icon" />
    </head>

    <body>
        <div class="container">
            <div class="banner">SAW Secutiry Ltd.,</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>
                <div class="menuitem"><a href="/static/products.html">Products</a></div>
                <div class="menuitem"><a href='/static/people.html'>People</a></div>
                <div class="menuitemselected"><a href='/static/contact Us.html'>About</a></div>
            </div>
            <div class="content">
                <div class="Peoplecontent">
                    <h1>FEEL FREE TO CONTACT US</h1> 
                    <div class="Peopleitems">
                        <h2>For Enquiry:</h2>
                        <h3>E-Mail : sawautomobi02@gmail.com</h3><br>
                        <h3>NUMBER: +91 9345572665, +91 6865824832</h3><br>
                        <h3>ADDRESS: 12B,Richie street,Chennai.</h3><br>
                    </div>
                </div>
            </div>
            <div class="footer">
            Copyright &#169; 2021 SAW Secutiry Ltd., Developed by Pranave B.
        </div>
            </div>
        </div>
    </body>
</html>
~~~

## OUTPUT:

### Home Page:

![output](./images/homepage.png)

### Products Page:

![output](./images/products.png) 

### People page:

![output](./images/people.png)

### Contact Us page:

![output](./images/about.png)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
