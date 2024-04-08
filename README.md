# Main Page Code 
### Home Page in index.html
### You Can See Live Demo Here [Hotel Demo Website]  (https://hotel-demo-website.netlify.app/)

``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Hotel Website</title>
    <link rel="stylesheet" href="css/styles.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  </head>
  <body>
    <header>
      <nav id="navbar">
        <div class="container">
          <h1>HOTEL<a href="index.html"></a></h1>
          <ul>
            <li><a href="index.html" class="current">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
          </ul>
        </div>
      </nav>
      <div id="showcase">
        <div class="container">
            <div class="show-content">
                <h1><span class="text-primary">Enjoy</span> Your Stay</h1>
                <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse provident impedit iste suscipit doloribus quia eos recusandae soluta perspiciatis officiis ipsam ipsum necessitatibus, nihil beatae est a repellendus libero deserunt.</p>
                <a href="#" class="btn">About Our Hotel</a>
            </div>

        </div>
    </header>
    <section id="home-info"class="bf-dark">
        <div class="info-img">
            </div>
        <div class="info-content">
            <h2><span class="text-primary">The History</span>of our hotel</h2>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Reprehenderit maiores quisquam est quia facilis maxime corrupti laudantium esse fuga. Beatae nam ab ipsam quae perferendis reiciendis dolore totam autem repellat!</p>
            <a href="#" class="btn">Read More</a>
            </div>
        </section>
        <section id="features">
            <div class="box">
                <i class="fa-solid fa-filter"></i>
                <h3>Good Rooms</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Suscipit, laudantium.</p>
                </div>
                 <div class="box">
                    <i class="fa-solid fa-terminal"></i>
                     <h3>Good Rooms</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Suscipit, laudantium.</p>
                </div>
                 <div class="box">
                    <i class="fa-solid fa-bath"></i>
                     <h3>Good Rooms</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Suscipit, laudantium.</p>
                </div>
            </section>
            <div class="cls"></div>
            <footer id="main-footer">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error, odit.&copy;</p>
                </footer>
  </body>
</html>
``````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
# CSS Stying Code Here
### Style.css Code here

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
/* Main Styling */
html,
body {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
a {
  text-decoration: none;
  color: #333;
}
h1,
h2,
h3 {
  padding-bottom: 10px;
}
p {
  margin: 10px 0;
}
/* Utility */
.container {
  max-width: 900px;
  margin: auto;
  padding: 0 20px;
  overflow: auto;
}
/* Navbar */
#navbar {
  background-color: #333;
  color: white;
  overflow: auto;
}
#navbar a {
  color: #fff;
}
#navbar h1 {
  float: left;
  padding: 20px;
}
#navbar ul {
  float: right;
  list-style: none;
}
#navbar ul li {
  float: left;
}
#navbar ul li a {
  display: block;
  padding: 20px;
  text-align: center;
}
#navbar ul li a:hover,
#navbar ul li a.current {
  background-color: #444;
  color: orange;
}

/* Home Styling */
#showcase {
  background: url("../images/showcase.jpg");
  height: 600px;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
#showcase .show-content {
  color: white;
  text-align: center;
  padding-top: 140px;
}
#showcase .show-content h1 {
  font-size: 54px;
  line-height: 1.8;
}
.show-content span {
  color: orange;
}
.show-content p {
  padding-bottom: 30px;
  line-height: 1.2;
}
.btn {
  background-color: #333;
  color: white;
  padding: 10px 16px;
  display: inline-block;
  border: none;
  border-radius: 3px;
}
.text-primary {
  color: orange;
}
#home-info {
  height: 400px;
}
#home-info .info-img {
  background: url("../images/test-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  width: 50%;
  float: left;
  min-height: 100%;
}
#home-info .info-content {
  background-color: #333;
  width: 50%;
  text-align: center;
  float: right;
  padding: 50px 30px;
  height: 100%;
  overflow: hidden;
}
.box {
  width: 33%;
  float: left;
  padding: 30px;
  text-align: center;
  border-bottom: 1px solid #ddd;
}
.box i {
  font-size: 45px;
  margin-bottom: 10px;
}
.box i {
  color: orange;
}
#main-footer {
  background-color: #333;
  padding: 20px;
  color: white;
  text-align: center;
}
.cls {
  clear: both;
}

#about-info .info-left {
  float: left;
  width: 50%;
  min-height: 100%;
}

#about-info .info-right {
  float: right;
  width: 50%;
  min-height: 100%;
}
#about-info .info-right {
  display: block;
  margin: auto;
  width: 70%;
}

.bg-primary {
  background-color: orange;
}
#testimonials {
  background: url("../images/showcase.jpg") no-repeat center center/cover;
  height: 400px;
  padding: 40px;
}

#testimonials .testimonial {
  padding: 20px;
  margin-bottom: 30px;
  border-radius: 20px;
  opacity: 0.7;
}
#testimonials .testimonial img {
  float: left;
  margin-right: 20px;
  width: 100px;
  border-radius: 50%;
}

#contact-form .form-group {
  margin-bottom: 20px;
}
#contact-form label {
  margin-bottom: 10px;
  display: block;
}
#contact-form input,
#contact-form textarea {
  width: 100%;
  padding: 20px;
  border: none;
  border-radius: 5px;
  border: 2px solid #ddd;
}
#contact-form textarea {
  height: 200px;
}
#contact-form input:focus,
#contact-form textarea:focus {
  outline: none;
  border: 2px solid orange;
}
#contact-form h1 {
  text-align: center;
}
.fill-form {
  text-align: center;
}
