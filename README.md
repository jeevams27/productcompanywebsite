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


### Home Page:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MJ TECHNOLOGIES PVT.LTD</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./ourlogo.jpg" type="image/x-icon" />
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
          <h1>About</h1>
          <img src="./img/mjco.jpg" alt="MJ" />
          <div class="contenttext">
            We beleive every person has the right to participate fully in th global economy.
            <h1>Who We Are</h1>A global community working together to make financial services and commerce more convenient,affordable and secure.
            <h1>How we work</h1>Our values ae the foundation for how we conduct business every day.
            <h1>Values in Action</h1>We leverage our platform and resources to support our employees,customers and communities.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 MJ Technologies, Developed by Jeeva.M.S
      </div>
    </div>
  </body>
</html>


### PRODUCT PAGE:


<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MJ TECHNOLOGIES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ourlogo.jpg" type="image/x-icon" />
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
          <h1>Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/p1.jpg" alt="product image">
                  </div>
                  <div class="itemname">MJ Connected Intelligence Platform</div>
                  </div>
                  <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/p2.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">MJ Intelligent Urban Exchange</div>
                  </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/p3.png"  alt="product image">
                    </div>
                    <div class="itemname">MJ Salesloft</div>  
                  </div>
                  <div class="productitems">
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/p4.jpeg" alt="product image">
                        </div>
                        <div class="itemname">MJ Awardco</div>
                        </div>
                        <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/p5.png"  alt="product image">
                        </div>
                        <div class="itemname">MJ Spiff</div>
                        </div>
                        <div class="productitem"> 
                          <div class="itemimage">
                          <img src="/static/img/p6.png"  alt="product image">
                          </div>
                          <div class="itemname">MJ Zoho Social</div>  
                        </div>
                        <div class="productitems">
                          <div class="productitem"> 
                              <div class="itemimage">
                              <img src="/static/img/p7.jpeg" alt="product image">
                              </div>
                              <div class="itemname">MJ Jira</div>
                              </div>
                              <div class="productitem"> 
                              <div class="itemimage">
                              <img src="/static/img/p8.png"  alt="product image">
                              </div>
                              <div class="itemname">MJ Chargebee</div>
                              </div>
                              <div class="productitem"> 
                                <div class="itemimage">
                                <img src="/static/img/p9.png"  alt="product image">
                                </div>
                                <div class="itemname">MJ Mindtickle</div>  
                              </div>
                              <div class="productitems">
                                <div class="productitem"> 
                                    <div class="itemimage">
                                    <img src="/static/img/p10.png" alt="product image">
                                    </div>
                                    <div class="itemname">MJ Saleshub</div>
                                    </div>
                                    <div class="productitem"> 
                                    <div class="itemimage">
                                    <img src="/static/img/p11.png"  alt="product image">
                                    </div>
                                    <div class="itemname">MJ Interform</div>
                                    </div>
                                    <div class="productitem"> 
                                      <div class="itemimage">
                                      <img src="/static/img/p12.png"  alt="product image">
                                      </div>
                                      <div class="itemname">MJ Marketing Hub</div>  
                                    </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 MJ Technologies, Developed by Jeeva.M.S
      </div>
    </div>
  </body>
</html>



### PEOPLE PAGE:



<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MJ TECHNOLOGIES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ourlogo.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/Products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"> <a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Employees</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ms1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Dhoni MS</div>
                  <div class="itemname">Chief Executive officer(CEO)</div>
                  </div>
                  <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/kL1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Rahul KL</div>
                  <div class="itemname">Chief Operating officer(COO)</div>
                  </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/ra.jpg"  alt="product image">
                    </div>
                    <div class="itemname">Suresh Rain</div>  
                    <div class="itemname">Chief Financial officer(CFO)</div>
                  </div>
                  <div class="productitems">
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/sam.jpg" alt="product image">
                        </div>
                        <div class="itemname">samantha</div>
                        <div class="itemname">Chief Techanical officer(CTO)</div>
                        </div>
                        <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/PRO1.jpg"  alt="product image">
                        </div>
                        <div class="itemname">Paul Andrew</div>
                        <div class="itemname">chief Legial officer(CLO)</div>
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="/static/img/TOK.jpg"  alt="product image">
                            </div>
                            <div class="itemname">Tokyo</div>
                            <div class="itemname">General Manager(GM)</div>
                            </div>



### CONTACT US PAGE:


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
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href='/static/people.html'>People</a></div>
        <div class="menuitemselected">
            <a href='/static/contactus.html'>Contact Us</a>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Contact Details</h1>
          <div class="productitems">
            <h2>MJ Technologies</h2>
            <h3> Old Mahabalipuram Rd, Industrial Estate,</h3>
            <h3>Thiruvanmiyur, Chennai, </h3>
            <h3>Tamil Nadu-600041</h3>
          </br>
            <h3>EMAIL : mjtech73@gmail.com</h3>
          </br>
            <h3>NUMBER: +91 9456709987s</h3>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 MJ Technologies, Developed by Jeeva.M.S.
      </div>
    </div>
  </body>
</html>

## OUTPUT:


![output](./images/home1.png)

![output](./images/product1.png)

![output](./images/people1.png)

![output](./images/cont.png)

### HTML VALIDATOR:

![output](./images/VALI.png)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
