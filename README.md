# Ex.07 Software Product Company Website
## Date:29.11.2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<html>
    <head>
        <link rel="stylesheet" href="stylehome.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./comp.png" alt="logo" height="60px"></div>
            <li><a href="./home.html" class="color">Home</a></li>
            <li><a href="peroson.html"class="color">People</a></li>
            <li><a href="./products.html"class="color">Products</a></li>
            <li><a href="./contact.html"class="color">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div class="home">
        <div class="head">
        <h1>A Software Agency shaping</br>ideas into </br>Products</h1>
        <p class="quote">"People who are really in serious about Software </br>should make their hardware"- Alan key </p>
        <button class="join">Join us</button>
    </div>
    <div class="login">
        <h2 class="log">login Here</h2> 
        <div class="logbox">
        <input type="text" placeholder="username or email" class="but"></input></br></br>
        <input type="text"  placeholder="password" class="but"> </input></br></br>
        <button type="submit" class="bute">Login</button></br></br>
        <hr id="loge">
        </div>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;Don't have an account </br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>Sign up</u> here.</p>

    </div>
    </div>
    <footer>
        <div  class="colored-line">
            <h5>Design and developed by Mr.Iyalarasu.C &copy;2023</h5>
        </div>
    </footer>

    
    
    </body>
</html>
<html>
    <head>
        <link rel="stylesheet" href="./personstyle.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./comp.png" alt="logo" height="60px"></div>
            <li><a href="./home.html" class="color">Home</a></li>
            <li><a href="peroson.html"class="color">People</a></li>
            <li><a href="./products.html"class="color">Products</a></li>
            <li><a href="./contact.html"class="color">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div class="person">
        <li> <img src="./Images/iyal.jpg" class="bod"></br><span> &nbsp;&nbsp;&nbsp;Iyalarasu</span><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CEO</p></li>
        <li> <img src="./Images/bhim1.jpg"  class="bod"></br><span>&nbsp;&nbsp;&nbsp;Bheem</span><P>&nbsp;&nbsp;&nbsp;&nbsp;Founder</P></li>
        <li> <img src="./Images/hatori.jpg" class="bod"></br><span>&nbsp;&nbsp;&nbsp;Hatori</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Co-Founder</li>
        <li> <img src="./Images/doramen1.jpg"class="bod" ></br><span>&nbsp;&nbsp;&nbsp;Doramen</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Director</p></li>
        <li> <img src="./Images/motu.jpeg" class="bod"></br><span>&nbsp;&nbsp;&nbsp;Motu</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Assi Director</p></li>
        <li> <img src="./Images/jake.jpg" class="bod"></br><span>&nbsp;&nbsp;&nbsp;jackie chan</span><P>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MD</P></li>
    </div>
    <footer>
    <div  class="colored-line">
        <h5>Design and developed by Mr.Iyalarasu.C &copy;2023</h5>
    </div>
</footer>
    
    
    </body>
</html>
<html>
    <head>
        <link rel="stylesheet" href="styleproduct.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./comp.png" alt="logo" height="60px"></div>
            <li><a href="./home.html" class="color">Home</a></li>
            <li><a href="peroson.html"class="color">People</a></li>
            <li><a href="./products.html"class="color">Products</a></li>
            <li><a href="./contact.html"class="color">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div>
        <img src="./Images/product.jpg" alt="product" class="imge">
    </div>
    <footer>
        <div  class="colored-line">
            <h5>Design and developed by Mr.Iyalarasu.C &copy;2023</h5>
        </div>
    </footer>
    <html>
    <head>
        <link rel="stylesheet" href="stylecontact.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./comp.png" alt="logo" height="60px"></div>
            <li><a href="./home.html" class="color">Home</a></li>
            <li><a href="peroson.html"class="color">People</a></li>
            <li><a href="./products.html"class="color">Products</a></li>
            <li><a href="./contact.html"class="color">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" class="button">
            <button type="submit" class="submit" >search</button>
                
    </div>
</div>
<div class="contact">
    <div class="detail">
    <h1> Contact Us</h1>
    <br>
    <input type="text" placeholder="Your Name"></inupt> 
    <br><br>
    <input type="text" placeholder="Your Email"></inupt>
    <br><br>
    <input type="text" placeholder="Your Message" class="comment"></inupt>
    <br><br>
    <button type="submit" class="submit">Submit</button>

</div>
<div class="info">
    <h1>Contact information</h1>
    <br>
    <span><strong>Address:</strong></span>    Church street,kommedu,gingee,villupuram-604205.</p>
    <span><strong>Email:</strong></span>    cris.jpt@gmail.com</p>
    <span><strong>Phone: </strong></span> 044-46055</p>

</div>
</div>
<footer>
    <div  class="colored-line">
        <h5>Design and developed by Mr.Iyalarasu.C &copy;2023</h5>
    </div>
</footer>
    
  
    
    
    </body>
</html>
    
    
    </body>
</html>

```


## OUTPUT:
![Alt text](<Screenshot (42).png>)
![Alt text](<Screenshot (43).png>)
![Alt text](<Screenshot (44).png>)
![Alt text](<Screenshot (45).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
