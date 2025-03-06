# JuxxStores
# A fully responsive website that advertises Laptops to various clients professional specialists and students.
# Used inline presentation of both JS and CSS styling






# index.html code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Juxx STORES</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
    <script>  
document.addEventListener("DOMContentLoaded", function() {
    alert("Welcome at Juxx Stores!");
   
});

function toggleFAQ(faqID) {
    let answer = document.getElementById(faqID);
    answer.style.display = answer.style.display === "none" ? "block" : "none";
}

    </script>
    <style>
        body {font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    height: 150vh;
    width: 100vw;
    background-image: url('https://t3.ftcdn.net/jpg/02/90/89/76/360_F_290897614_7RdAsk2GmumcGWZ2qklmV74hKlNmznSx.jpg'); /* Replace with your image */
    background-size: cover; /* Make image fit the screen */
    background-position: center; /* Center the image */
    background-attachment: scroll; /* Keeps the background still when scrolling */
    background-repeat: no-repeat; /* Prevents image from repeating */
    text-align: center;
        }
        h1 {
           color: rgb(219, 122, 30);
           font-family: Georgia, 'Times New Roman', Times, serif;
        }
        h3 {
    cursor: pointer;
    color: rgb(255, 123, 0);
}nav ul {
    list-style-type: none;  /* Remove bullet points */
    padding: 0;
    margin: 0;
    display: flex; /* Arrange items in a row */
    justify-content: center; /* Center horizontally */
    gap: 15px; /* Space between links */
}

nav ul li {
    display: inline; /* Ensure items are inline */
}

nav ul li a {
    text-decoration: none;
    color: blue; /* Adjust link color */
    font-size: 18px;
    font-weight: bold;
}

nav ul li a:hover {
    color: orange; /* Change color on hover */
}

header {
    background: #3806ac;
    color: rgb(71, 15, 226);
    padding: 10px;
}

footer {
    margin-top: 20px;
    background: #080bb6;
    color: rgb(173, 11, 11);
    padding: 10px;
}

    </style>
    
</head>
<body>
    <header>
        <h1>JUXX Laptop Stores</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Juxx specials</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="reviews.html">Reviews</a></li>
                <li><a href="contact.html">Contact us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        
        <h2>Discover Amazing quality Laptops</h2>
        <p>Explore a wide range of quality laptops that meet all your needs at the best prices.</p>
        <p>From students', business and entrepreneurs, media specialists, scientists meteorologists and many more</p>
        <p>We got you all covered with various laptop specifications to boost your productivities.</p>
        <p>To access what we have in store for you, click <a href="products.html">laptops</a> to explore <b>magical laptops</b></p>
        <img src="https://www.techyshop.co.ke/wp-content/uploads/2021/10/Laptop-For-Sale-in-Nairobi-1.png" alt="Product Banner"width="400"height="300">
        <p>We also have quality accessories to better your experience with us.</p>
        <p>Depending on the laptop purchase, you are guaranteed of some free accessories</p>
        <img src="https://5.imimg.com/data5/SELLER/Default/2023/1/SM/GS/DW/44069440/acce.png"alt="Laptop accesories"width="500"height="300">
       <p>Get to know the frequently asked questions<b>(FAQs)</b></p>
        <div>
            <h3 onclick="toggleFAQ('faq1')">What is your return policy? ⬇</h3>
            <p id="faq1" style="display: none;">We accept returns within 60 days from day 1 of purchase.</p>
        </div>
        
        <div>
            <h3 onclick="toggleFAQ('faq2')">Do you ship worldwide? ⬇</h3>
            <p id="faq2" style="display: none;">Yes, we ship globally.</p>
        </div>
        
    </main>
</div>

    <footer>
        <p>&copy; <b>2025 Juxx Laptop Stores.</b> All rights reserved.</p>
    </footer>
</body>
</html>

# products.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laptop Prices</title>
    <link rel="stylesheet" href="css/styles.css">
    <style>
        body {font-family: Arial, sans-serif;
            margin: 0;
    padding:0;
    height: 100vh;
    width: 100vw;
    display: flex;
    flex-direction: column;
    background-image: url('https://t3.ftcdn.net/jpg/02/90/89/76/360_F_290897614_7RdAsk2GmumcGWZ2qklmV74hKlNmznSx.jpg'); /* Replace with your image */
    background-size: cover; /* Make image fit the screen */
    background-position: center; /* Center the image */
    background-attachment: fixed; /* Keeps the background still when scrolling */
    background-repeat: no-repeat; /* Prevents image from repeating */
    text-align: center;
        }

    </style>
</head>
<body>
    <header>
        <h1>Juxx Special offers</h1>
        <p><a href="index.html"><b>Back Home</b></a></p> 
    </header>
    <main>
        
        <table border="1"title="Juxx special offers"width="550"height="250">
            <p><b>...Offers Available...</b></p>
            <tr>
                <th>Laptop Model</th>
                <th>Was</th>
                <th>Now</th>
            </tr>
            <tr>
                <td>Dell XPS 15</td>
                <td><s>Ksh. 185,000</s></td>
                <td>Ksh.150,000</td>
            </tr>
            <tr>
                <td>MacBook Pro 14</td>
                <td><del>Ksh. 216,000</del></td>
                <td>Ksh.209,000</td>
            </tr>
            <tr>
                <td>HP Spectre x360</td>
                <td><del>Ksh. 159,000</del></td>
                <td>Ksh. 149,000</td>
            </tr>
            <tr>
                <td>Lenovo ThinkPad X1 Carbon</td>
                <td><del>Ksh. 179,000</del></td>
                <td>Ksh.165,000</td>
            </tr>
            <tr>
                <td>Asus ROG Zephyrus G14</td>
                <td><del>Ksh. 195,000</del></td>
                <td>Ksh.189,000</td>
            </tr>
        </table>
        <p>We give free shipping globally for <a href="https://www.pugetsystems.com/solutions/engineering-workstations/">Engineering Workstations</a></p>
        <p>This huge offer is accomplished by our colaboration with <b>PUGET SYSTEMS</b> </p>
        <img src="https://www.coreeducational.org.uk/wp-content/uploads/2020/01/Work-station-image-heading.jpg"alt="Engineering Workstations"width="500"height="200">
    <p><b>Click</b><a href="gallery.html"> Photos</a> to explore visuals </p>
    </main>
    <footer>
        <p>&copy; <b>2025 Juxx Laptop Stores.</b> All rights reserved.</p>
    </footer>
</body>
</html>


# gallery.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <link rel="stylesheet" href="css/styles.css">

      
        <style>
            body{
                background-image: url('https://t3.ftcdn.net/jpg/02/90/89/76/360_F_290897614_7RdAsk2GmumcGWZ2qklmV74hKlNmznSx.jpg');
                background-repeat: no-repeat;
                background-size: cover;
                background-position: center;
            }
.horizontal-container {
    display: flex; /* Enables horizontal layout */
    justify-content: center; /* Spreads items evenly */
    align-items: center; /* Aligns items vertically */
    gap: 20px; /* Adds space between images */
}

.horizontal-container div {
    text-align: center; /* Centers text below images */
}

.horizontal-container img {
    width: 300px; /* Adjust width as needed */
    height: auto; /* Maintains aspect ratio */
    border-radius: 10px; /* Optional: Adds rounded corners */
}
.horizontal-container1 {
    display: flex; /* Enables horizontal layout */
    justify-content: center; /* Spreads items evenly */
    align-items: center; /* Aligns items vertically */
    gap: 20px; /* Adds space between images */
}

.horizontal-container1 img {
    width: 300px; /* Adjust width as needed */
    height: auto; /* Maintains aspect ratio */
    border-radius: 10px;
}

.horizontal-container1 div {
    text-align: center;

}
    </style>
</head>
<body>
    <header>
        <h1>Product Gallery</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="reviews.html">Reviews</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
          <h2>Juxx Collection</h2>
       <div class="horizontal-container">
          <div>
            <h3>Dell XPS 15</h3>
            <img src="https://sm.pcmag.com/t/pcmag_uk/review/d/dell-xps-1/dell-xps-15-9530-2023_uxjn.1920.jpg" alt="Dell XPS 15"width="300" height="200">
          </div>
          <div>
            <h3>MacBook Pro 14</h3>
            <img src="https://www.macworld.com/wp-content/uploads/2024/11/M4-MacBook-Pros-right-angle.jpg?quality=50&strip=all" alt="MacBook Pro 14"width="300" height="200">
          </div>
          <div>
            <h3>HP Spectre x360</h3>
            <img src="https://media.wired.com/photos/59e94f9234ce5c0e0a752e11/master/w_1600%2Cc_limit/SphinxInline.jpg" alt="HP Spectre x360"width="300" height="200">
          </div>
        </div>
        <div class="horizontal-container1">
            <h3>Lenovo ThinkPad X1 Carbon</h3>
            <img src="https://evercomps.co.ke/wp-content/uploads/2023/07/lenovo-laptops-x1-carbon-6th-gen-hero.webp"alt="Lenovo ThinkPad X1 Carbon"width="300" height="200">
         
            <h3> Asus ROG Zephyrus G14</h3>
            <img src="https://1.img-dpreview.com/files/p/E~TS590x0~articles/6744764164/DLCS3134-Edit.jpeg"alt="Asus ROG Zephyrus G14"width="300" height="200">
            <h3>Acer Nitro 5</h3>
            <img src="https://static.toiimg.com/thumb/msid-68839314,width-1280,height-720,resizemode-4/68839314.jpg"width="300"height="200">
        </div>
    
    
   </main>
    <footer>
        <p>&copy; <b>2025 Juxx Laptop Stores.</b> All rights reserved.</p>
    </footer>
</body>
</html>


# reviews.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <link rel="stylesheet" href="css/styles.css">

      
        <style>
            body{
                background-image: url('https://t3.ftcdn.net/jpg/02/90/89/76/360_F_290897614_7RdAsk2GmumcGWZ2qklmV74hKlNmznSx.jpg');
                background-repeat: no-repeat;
                background-size: cover;
                background-position: center;
            }
.horizontal-container {
    display: flex; /* Enables horizontal layout */
    justify-content: center; /* Spreads items evenly */
    align-items: center; /* Aligns items vertically */
    gap: 20px; /* Adds space between images */
}

.horizontal-container div {
    text-align: center; /* Centers text below images */
}

.horizontal-container img {
    width: 300px; /* Adjust width as needed */
    height: auto; /* Maintains aspect ratio */
    border-radius: 10px; /* Optional: Adds rounded corners */
}
.horizontal-container1 {
    display: flex; /* Enables horizontal layout */
    justify-content: center; /* Spreads items evenly */
    align-items: center; /* Aligns items vertically */
    gap: 20px; /* Adds space between images */
}

.horizontal-container1 img {
    width: 300px; /* Adjust width as needed */
    height: auto; /* Maintains aspect ratio */
    border-radius: 10px;
}

.horizontal-container1 div {
    text-align: center;

}
    </style>
</head>
<body>
    <header>
        <h1>Product Gallery</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="reviews.html">Reviews</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
          <h2>Juxx Collection</h2>
       <div class="horizontal-container">
          <div>
            <h3>Dell XPS 15</h3>
            <img src="https://sm.pcmag.com/t/pcmag_uk/review/d/dell-xps-1/dell-xps-15-9530-2023_uxjn.1920.jpg" alt="Dell XPS 15"width="300" height="200">
          </div>
          <div>
            <h3>MacBook Pro 14</h3>
            <img src="https://www.macworld.com/wp-content/uploads/2024/11/M4-MacBook-Pros-right-angle.jpg?quality=50&strip=all" alt="MacBook Pro 14"width="300" height="200">
          </div>
          <div>
            <h3>HP Spectre x360</h3>
            <img src="https://media.wired.com/photos/59e94f9234ce5c0e0a752e11/master/w_1600%2Cc_limit/SphinxInline.jpg" alt="HP Spectre x360"width="300" height="200">
          </div>
        </div>
        <div class="horizontal-container1">
            <h3>Lenovo ThinkPad X1 Carbon</h3>
            <img src="https://evercomps.co.ke/wp-content/uploads/2023/07/lenovo-laptops-x1-carbon-6th-gen-hero.webp"alt="Lenovo ThinkPad X1 Carbon"width="300" height="200">
         
            <h3> Asus ROG Zephyrus G14</h3>
            <img src="https://1.img-dpreview.com/files/p/E~TS590x0~articles/6744764164/DLCS3134-Edit.jpeg"alt="Asus ROG Zephyrus G14"width="300" height="200">
            <h3>Acer Nitro 5</h3>
            <img src="https://static.toiimg.com/thumb/msid-68839314,width-1280,height-720,resizemode-4/68839314.jpg"width="300"height="200">
        </div>
    
    
   </main>
    <footer>
        <p>&copy; <b>2025 Juxx Laptop Stores.</b> All rights reserved.</p>
    </footer>
</body>
</html>


# contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <script>
document.addEventListener("DOMContentLoaded", function() {
    alert("Contact us here! THANK YOU");
   
});
function toggleForm() {
    let form = document.getElementById("contact-form");
    if (form.style.display === "none") {
        form.style.display = "block";
    } else {
        form.style.display = "none";
    }
 }
    </script>
    <style>
        body {font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    height: 100vh;
    width: 100vw;
    background-image: url('https://t3.ftcdn.net/jpg/02/90/89/76/360_F_290897614_7RdAsk2GmumcGWZ2qklmV74hKlNmznSx.jpg');
    background-size: cover; /* Make image fit the screen */
    background-position: center; /* Center the image */
    background-attachment: fixed; /* Keeps the background still when scrolling */
    background-repeat: no-repeat; /* Prevents image from repeating */
    text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Price List</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="reviews.html">Reviews</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Get in Touch</h2>
        <p>Click the button bellow to access all our handles</p>
        
    <button onclick="toggleForm()">Contact Us</button>
    <div id="contact-form" style="display: none;">
        <form>
            <p><input type="text" placeholder="Enter Name"required></p>
            <p><input type="email" placeholder=" Email"></p>
            <p><textarea placeholder="Your Message"></textarea></p>
            <button type="submit">Send</button>
        </form>
        <h3>Connect With Us</h3>
<a href="https://www.facebook.com/YourPage" target="_blank">
    <i class="fab fa-facebook fa-2x"></i>
</a>
<a href="https://www.twitter.com/YourHandle" target="_blank">
    <i class="fab fa-twitter fa-2x"></i>
</a>
<a href="https://www.instagram.com/YourProfile" target="_blank">
    <i class="fab fa-instagram fa-2x"></i>
</a>
<a href="https://www.linkedin.com/in/YourProfile" target="_blank">
    <i class="fab fa-linkedin fa-2x"></i>
</a>
<P><B>Call US: </B>0704225571</P>
    </main>
    <footer>
        <p>&copy; <b>2025 Juxx Laptop Stores.</b> All rights reserved.</p>
    </footer>
</body>
</html>




