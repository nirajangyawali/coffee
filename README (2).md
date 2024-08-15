
# Project Title

The "Cafe Harmony" project involves the creation of a simple yet attractive website for a fictional cafe. The goal of the project is to design a user-friendly interface that provides information about the cafe, its menu, and contact details. The website uses HTML for structure, CSS for styling, and integrates external resources such as font awesome for icons.

Errors Faced:
During the development process, several errors and challenges were encountered:
•	Image not loading: Some images didn’t appear due to incorrect file paths.
•	Responsive Design Issues: The website did not display correctly on mobile devices.
•	Styling Conflicts: There were conflicts between different CSS properties that affected the layout.

Solving the Errors
•	Image Loading: Corrected the file paths and ensured all images were in the proper directory.
•	Responsive Design: Used media queries to adjust the layout for different screen sizes.
•	Styling Conflicts: Reviewed the CSS to remove conflicts, ensuring consistent styling across all elements.

Results Achieved
The Cafe Harmony website was successfully developed with a user-friendly interface. The navigation is intuitive, and the website is responsive across different devices. All images and icons load correctly, and the overall design is visually appealing.


## Appendix

Any additional information goes here

#html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="hell.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css"
        integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Cafe Harmony</title>
</head>
<body>
    <header>
        <div class="logo">
            <a href="#">Cafe <span>Harmony</span></a>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="content">
        <h2>Cafe Harmony</h2>
        <p>Would you like to start the day with a nice coffee?</p>
    </div>

    <div class="menu" id="menu">
        <div class="menu-header">
            <h3>Menu</h3>
            <h4>Cafe Harmony</h4>
        </div>
        <div class="menu-content">
            <div class="hot-coffees">
                <div class="hot-coffees-image">
                    <img src="hot-coffees.jpg" alt="">
                </div>
                <div class="hot-coffees-body">
                    <h2>Hot Coffees</h2>
                    <label>Made by brewing ground coffee beans with hot water.</label>
                </div>
            </div>
            <div class="cold-coffees">
                <div class="cold-coffees-image">
                    <img src="cold-coffees.jpg" alt="">
                </div>
                <div class="cold-coffees-body">
                    <h2>Cold Coffees</h2>
                    <label>Brewed hot and then chilled, or brewed cold (cold brew).
                    </label>
                </div>
            </div>
            <div class="frappucino-coffees">
                <div class="frappucino-coffees-image">
                    <img src="frappuccino.jpg" alt="">
                </div>
                <div class="frappucino-coffees-body">
                    <h2>Frappucino Coffees</h2>
                    <label>Made with a base of coffee, milk, and ice, blended into a smooth, slushy consistency.</label>
                </div>
            </div>
        </div>
    </div>
    <div class="shop" id="shop">
        <div class="shop-header">
            <h3>Shop</h3>
            <h4>Cafe Harmony Drinks</h4>
        </div>
        <div class="shop-box">
            <div class="item-1">
                <div class="card">
                    <div class="card-image">
                        <img src="caramel-macchiato.jpg">
                    </div>
                    <div class="card-body">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star-half"></i>
                        <label class="cash">600</label>
                        <h3>Caramel Macchiato</h3>
                        <label>A delicious blend of steamed milk, vanilla syrup, and espresso, topped with caramel drizzle.</label>
                    </div>
                </div>
            </div>
            <div class="item-2">
                <div class="card">
                    <div class="card-image">
                        <img src="flat-white.png">
                    </div>
                    <div class="card-body">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <label class="cash">500</label>
                        <h3>Flat White</h3>
                        <label>A smooth and velvety drink made with espresso and steamed milk.</label>
                    </div>
                </div>
            </div>
            <div class="item-3">
                <div class="card">
                    <div class="card-image">
                        <img src="chocolate-frappuccino.png">
                    </div>
                    <div class="card-body">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star-half"></i>
                        <label class="cash">550</label>
                        <h3>Chocolate Frappucino</h3>
                        <label>A blended coffee drink with chocolate flavor, milk, and ice, topped with whipped cream. </label>
                    </div>
                </div>
            </div>
            <div class="item-4">
                <div class="card">
                    <div class="card-image">
                        <img src="frappe.jpg">
                    </div>
                    <div class="card-body">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <label class="cash">400</label>
                        <h3>Frappe</h3>
                        <label>Similar to a Frappuccino, a frappe is a cold blended coffee drink often mixed with milk and other flavors.</label>
                    </div>
                </div>
            </div>
            <div class="item-5">
                <div class="card">
                    <div class="card-image">
                        <img src="caffe-mocha.png">
                    </div>
                    <div class="card-body">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star-half"></i>
                        <label class="cash">460</label>
                        <h3>Caffe Mocha</h3>
                        <label> A mix of espresso, steamed milk, and chocolate syrup, topped with whipped cream.</label>
                    </div>
                </div>
            </div>
            <div class="item-6">
                <div class="card">
                    <div class="card-image">
                        <img src="vanilla-frappuccino.jpg">
                    </div>
                    <div class="card-body">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <label class="cash">440</label>
                        <h3>Vanilla Frappucino</h3>
                        <label>A blended coffee drink with vanilla flavor, milk, and ice, topped with whipped cream.</label>
                    </div>
                </div>
            </div>
            <div class="item-7">
                <div class="card">
                    <div class="card-image">
                        <img src="white-chocolate-mocha.jpg">
                    </div>
                    <div class="card-body">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star-half"></i>
                        <label class="cash">900</label>
                        <h3>White Chocolate Mocha</h3>
                        <label>Similar to a Caffe Mocha but with white chocolate syrup instead. </label>
                    </div>
                </div>
            </div>
            <div class="item-8"> 
                <div class="card">
                    <div class="card-image">
                        <img src="ice-latte.jpg">
                    </div>
                    <div class="card-body">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <label class="cash">700</label>
                        <h3>Ice Latte</h3>
                        <label> A cold coffee drink made with espresso and chilled milk, served over ice.</label>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="contact" id="contact">
        <div class="contact-box">
            <div class="contact-image">
                <img src="bg-image.jpeg">
            </div>
        </div>
        <div class="contact-box">
            <div class="contact-body">
                <form>
                    <h2>Contact Us</h2>
                    <div class="form-content">
                        <input type="text" required>
                        <span></span>
                        <label>Username</label>
                    </div>
                    <div class="form-content">
                        <input type="email" required>
                        <span></span>
                        <label>Email</label>
                    </div>
                    <button type="submit">Send</button>
                </form>
            </div>
        </div>
    </div>
    <div class="footer">
        <div class="footer-box">
            <div class="social-media">
                <a href="#"><i class="fa-brands fa-facebook"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
                <a href="#"><i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-youtube"></i></a>
            </div>
            <div class="copyright">
                <label>Copyright &copy; 2024.All rights reserved</label>
            </div>
            <div class="brand">
                <label>Cafe <span> Harmony</span></label>
            </div>
        </div>
    </div>
</body>
</html>



#css

style.css
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
}

html {
    font-family: 'Open Sans', sans-serif;
    scroll-behavior: smooth;
}

img {
    width: 100%;
}

header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 50px;
    width: 90%;
    height: 70px;
    position: absolute;
    z-index: 1;
}

header .logo a {
    font-size: 30px;
    color: white;
    padding: 15px 30px;
}

header .logo a span {
    color: orange;
}

header nav ul {
    display: flex;
}

header nav ul li a {
    margin: 30px 15px;
    font-size: 18px;
    color: white;
    padding: 10px 10px;
}
header nav ul li a:hover {
    border-bottom: 2px solid white;
}
/* Content */
.content {
    display: flex;
    flex-direction: column;style.css
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        text-decoration: none;
        list-style: none;
    }
    html {
        font-family: 'Open Sans', sans-serif;
        scroll-behavior: smooth;
    }
    img {
        width: 100%;
    }
    header {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 40px;
        width: 0;
        height: 100px;
        position: absolute;
        z-index: 1;
    }
    
    header .logo a {
        font-size: 30px;
        color: white;
        padding: 15px 30px;
    }
    
    header .logo a span {
        color: orange;
    }
    
    header nav ul {
        display: flex;
    }
    
    header nav ul li a {
        margin: 5px 20px;
        font-size: 18px;
        color: white;
        padding: 10px 10px;
    }
    
    header nav ul li a:hover {
        border-bottom: 2px solid white;
    }
    
    /* Content */
    
    .content {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
        position: relative;
        min-height: 100vh;
        width: 100%;
        background-image: linear-gradient(to bottom right, rgba(96, 76, 76, .6), rgba(96, 76, 76, .6)), url("bg-image.jpeg");
        background-position: center bottom;
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
    }
    
    .content h2 {
        font-size: 32px;
        padding: 5px;
        color: white;
    }
    
    .content p {
        font-size: 22px;
        color: white;
    }
    
    
    /* Menu */
    
    .menu {
        background-color: #333333;
        width: 100%;
    }
    
    .menu .menu-header {
        display: flex;
        padding: 10px;
        align-items: center;
        justify-content: space-between;
    }
    
    .menu-header h3 {
        color: orange;
        padding: 10px 30px;
    }
    
    .menu-header h4 {
        color: orange;
        padding: 10px 20px;
    }
    
    .menu .menu-content {
        display: flex;
        align-items: center;
        justify-content: space-evenly;
        padding: 50px 0;
        flex-wrap: wrap;
        background-color: #404040;
    }
    
    .menu .menu-content .hot-coffees,
    .cold-coffees,
    .frappucino-coffees {
        width: 250px;
    }
    
    .menu .menu-content .hot-coffees .hot-coffees-image img {
        border-radius: 50%;
    }
    
    .menu .menu-content .cold-coffees .cold-coffees-image img {
        border-radius: 50%;
    }
    
    .menu .menu-content .frappucino-coffees .frappucino-coffees-image img {
        border-radius: 50%;
    }
    
    .menu .menu-content .hot-coffees-body,
    .cold-coffees-body,
    .frappucino-coffees-body {
        text-align: center;
        margin-top: 10px;
    }
    
    .menu .menu-content .hot-coffees-body h2,
    .cold-coffees-body h2,
    .frappucino-coffees-body h2 {
        color: orange;
    }
    
    .menu .menu-content .hot-coffees-body label,
    .cold-coffees-body label,
    .frappucino-coffees-body label {
        margin-top: 10px;
        color: white;
    }
    
    
    
    /* Shop */
    
    .shop {
        background-color: #333333;
        width: 100%;
    }
    
    .shop .shop-header {
        display: flex;
        padding: 10px;
        align-items: center;
        justify-content: space-between;
    }
    
    .shop-header h3 {
        color: orange;
        padding: 10px 30px;
    }
    
    .shop-header h4 {
        color: orange;
        padding: 10px 20px;
    }
    
    .shop-box {
        display: flex;
        align-items: center;
        justify-content: space-evenly;
        background-color: #404040;
        padding: 50px 0;
        flex-wrap: wrap;
    }
    
    .shop-box .card {
        width: 280px;
        margin: 20px;
    }
    
    .shop-box .card-image {
        width: 100%;
        height: 280px;
        overflow: hidden;
    }
    
    .shop-box .card-image img:hover {
        transform: scale(1.1);
        transition: transform .4s ease-in-out;
    }
    
    .shop-box .card-body {
        padding: 20px;
        color: white;
        border: 3px solid #3B3B3B;
    }
    
    .shop-box .card-body h3 {
        padding: 10px 0;
    }
    
    .shop-box .card-body i {
        color: yellow;
        font-size: 10px;
        position: relative;
        bottom: 5px;
    }
    
    .shop-box .card-body .cash {
        font-size: 22px;
        margin-left: 90px;
    }
    
    
    /* Contact */
    
    .contact {
        display: flex;
        flex-wrap: wrap;
        width: 100%;
        border-top: 2px solid #333333;
    }
    
    .contact .contact-box {
        flex: 1;
    }
    
    .contact .contact-box .contact-image,
    .contact .contact-box .contact-body {
        height: 100%;
    }
    
    .contact img {
        width: 100%;
        height: 100%;
    }
    
    .contact-image img {
        opacity: .9;
    }
    
    .contact-body {
        background-color: #404040;
        height: 100%;
        border-left: 2px solid #333333;
    }
    
    .contact-body form {
        padding: 50px 40px;
        box-sizing: border-box;
    }
    
    .contact-body h2 {
        color: orange;
    }
    
    form .form-content {
        position: relative;
        margin: 30px 0;
        border-bottom: 2px solid lightgray;
    }
    
    form .form-content input {
        width: 100%;
        height: 40px;
        padding: 0 5px;
        font-size: 17px;
        border: none;
        background: none;
        outline: none;
        color: white;
    }
    
    form .form-content label {
        position: absolute;
        top: 50%;
        left: 5px;
        color: gray;
        transform: translateY(-50%);
        font-size: 17px;
        transition: .5s;
        pointer-events: none;
    }
    
    form .form-content span::before {
        content: '';
        position: absolute;
        top: 40px;
        left: 0;
        width: 0%;
        height: 2px;
        background: orange;
        transform: .4s;
    }
    
    form .form-content input:focus~label,
    form .form-content input:valid~label {
        top: -5px;
        color: orange;
    }
    
    form .form-content input:focus~span::before,
    form .form-content input:valid~span::before {
        width: 100%;
    }
    
    .contact-body form button {
        padding: 10px 20px;
        font-size: 17px;
        border: none;
        background-color: #ff6600;
        color: white;
        border: 5px;
        cursor: pointer;
        transition: all .4s ease-in;
    }
    
    .contact-body form button:hover {
        background-color: #ff6681;
    }
    
    
    /* Footer */
    
    
    .footer {
        background-color: #404040;
        border-top: 2px solid #333333;
    }
    
    .footer .footer-box {
        padding: 30px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    
    .footer .footer-box .social-media a {
        color: white;
        background-color: #333333;
        border-radius: 50%;
        font-size: 17px;
        padding: 10px;
        margin: 5px;
    }
    
    .footer .footer-box .social-media a:hover {
        opacity: .7;
        transition: .5s all ease-in-out;
    }
    
    .footer .footer-box .copyright {
        color: white;
        font-size: 20px;
    }
    
    .footer .footer-box .brand {
        color: white;
        font-size: 20px;
    }
    
    .footer .footer-box .brand span {
        color: orange;
    }
    
    /* Responsive */
    
    @media(max-width: 992px) {
    
        /* Header */
    
        header {
            flex-direction: column;
            height: 150px;
            background: linear-gradient(rgba(0, 0, 0, .2), rgba(0, 0, 0, .2));
        }
    
        .menu-header .logo a {
            font-size: 25px;
        }
    
        header nav ul li a {
            font-size: 16px;
            flex-direction: column;
            display: inline-block;
            margin-top: 10px;
        }
    
        header nav {
            display: flex;
            flex-direction: column;
        }
    
        .content h2 {
            font-size: 28px;
        }
    
        .content p {
            font-size: 18px;
        }
    }
    
    
    @media(max-width: 950px) {
        .contact .contact-box {
            flex: 100%;
        }
    }
    
    @media(max-width: 800px) {
    
        .menu .menu-content .hot-coffees,
        .cold-coffees,
        .frappucino-coffees {
            margin: 20px;
        }
    }
    
    @media(max-width: 700px) {
        .footer .footer-box .social-media a {
            color: white;
            background-color: #333333;
            border-radius: 50%;
            font-size: 16px;
            padding: 5px;
        }
    
        .footer .footer-box .copyright {
            color: white;
            font-size: 15px;
        }
    
        .footer .footer-box .brand {
            color: white;
            font-size: 18px;
        }
    }
    
    @media(max-width: 500px) {
    
        /* header */
    
        header {
            height: 130px;
        }
    
        header .logo a {
            font-size: 23px;
        }
    
        header nav ul li a {
            font-size: 13px;
            flex-direction: column;
            display: inline-block;
            margin-top: 10px;
        }
    
        header nav {
            display: flex;
            flex-direction: column;
        }
    
    
        /* Content */
    
        .content h2 {
            font-size: 23px;
        }
    
        .content p {
            font-size: 16px;
        }
    
    
        /* footer */
    
        .footer .footer-box {
            flex-direction: column;
        }
    
        .footer .footer-box .social-media a {
            color: white;
            background-color: #333333;
            border-radius: 50%;
            font-size: 16px;
            padding: 10px;
            margin-top: 10px;
            display: inline-block;
        }
    
        .footer .footer-box .copyright {
            color: white;
            font-size: 15px;
            margin-top: 10px;
        }
    
        .footer .footer-box .brand {
            color: white;
            font-size: 18px;
            margin-top: 10px;
        }
    
    }
    
    
    @media(max-width: 410px) {
    
        /* header */
    
        header {
            height: 120px;
        }
    
        header .logo a {
            font-size: 20px;
            color: white;
            padding: 15px 30px;
        }
    
        header nav ul li a {
            font-size: 12px;
            flex-direction: column;
            display: inline-block;
            margin-top: 10px;
            color: white;
            padding: 5px 5px;
        }
    
        header nav {
            display: flex;
            flex-direction: column;
        }
    
        /* content */
    
        .content h2 {
            font-size: 20px;
        }
    
        .content p {
            font-size: 13px;
        }
    
    }
    align-items: center;
    justify-content: center;
    text-align: center;
    position: relative;
    min-height: 100vh;
    width: 100%;
    background-image: linear-gradient(to bottom right, rgba(96, 76, 76, .6), rgba(96, 76, 76, .6)), url("bg-image.jpeg");
    background-position: center bottom;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
}

.content h2 {
    font-size: 32px;
    padding: 5px;
    color: white;
}

.content p {
    font-size: 22px;
    color: white;
}


/* Menu */

.menu {
    background-color: #333333;
    width: 100%;
}

.menu .menu-header {
    display: flex;
    padding: 10px;
    align-items: center;
    justify-content: space-between;
}

.menu-header h3 {
    color: orange;
    padding: 10px 30px;
}

.menu-header h4 {
    color: orange;
    padding: 10px 20px;
}

.menu .menu-content {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    padding: 50px 0;
    flex-wrap: wrap;
    background-color: #404040;
}

.menu .menu-content .hot-coffees,
.cold-coffees,
.frappucino-coffees {
    width: 250px;
}

.menu .menu-content .hot-coffees .hot-coffees-image img {
    border-radius: 50%;
}

.menu .menu-content .cold-coffees .cold-coffees-image img {
    border-radius: 50%;
}

.menu .menu-content .frappucino-coffees .frappucino-coffees-image img {
    border-radius: 50%;
}

.menu .menu-content .hot-coffees-body,
.cold-coffees-body,
.frappucino-coffees-body {
    text-align: center;
    margin-top: 10px;
}

.menu .menu-content .hot-coffees-body h2,
.cold-coffees-body h2,
.frappucino-coffees-body h2 {
    color: orange;
}

.menu .menu-content .hot-coffees-body label,
.cold-coffees-body label,
.frappucino-coffees-body label {
    margin-top: 10px;
    color: white;
}



/* Shop */

.shop {
    background-color: #333333;
    width: 100%;
}

.shop .shop-header {
    display: flex;
    padding: 10px;
    align-items: center;
    justify-content: space-between;
}

.shop-header h3 {
    color: orange;
    padding: 10px 30px;
}

.shop-header h4 {
    color: orange;
    padding: 10px 20px;
}

.shop-box {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background-color: #404040;
    padding: 50px 0;
    flex-wrap: wrap;
}

.shop-box .card {
    width: 280px;
    margin: 20px;
}

.shop-box .card-image {
    width: 100%;
    height: 280px;
    overflow: hidden;
}

.shop-box .card-image img:hover {
    transform: scale(1.1);
    transition: transform .4s ease-in-out;
}

.shop-box .card-body {
    padding: 20px;
    color: white;
    border: 3px solid #3B3B3B;
}

.shop-box .card-body h3 {
    padding: 10px 0;
}

.shop-box .card-body i {
    color: yellow;
    font-size: 10px;
    position: relative;
    bottom: 5px;
}

.shop-box .card-body .cash {
    font-size: 22px;
    margin-left: 90px;
}


/* Contact */

.contact {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    border-top: 2px solid #333333;
}

.contact .contact-box {
    flex: 1;
}

.contact .contact-box .contact-image,
.contact .contact-box .contact-body {
    height: 100%;
}

.contact img {
    width: 100%;
    height: 100%;
}

.contact-image img {
    opacity: .9;
}

.contact-body {
    background-color: #404040;
    height: 100%;
    border-left: 2px solid #333333;
}

.contact-body form {
    padding: 50px 40px;
    box-sizing: border-box;
}

.contact-body h2 {
    color: orange;
}

form .form-content {
    position: relative;
    margin: 30px 0;
    border-bottom: 2px solid lightgray;
}

form .form-content input {
    width: 100%;
    height: 40px;
    padding: 0 5px;
    font-size: 17px;
    border: none;
    background: none;
    outline: none;
    color: white;
}

form .form-content label {
    position: absolute;
    top: 50%;
    left: 5px;
    color: gray;
    transform: translateY(-50%);
    font-size: 17px;
    transition: .5s;
    pointer-events: none;
}

form .form-content span::before {
    content: '';
    position: absolute;
    top: 40px;
    left: 0;
    width: 0%;
    height: 2px;
    background: orange;
    transform: .4s;
}

form .form-content input:focus~label,
form .form-content input:valid~label {
    top: -5px;
    color: orange;
}

form .form-content input:focus~span::before,
form .form-content input:valid~span::before {
    width: 100%;
}

.contact-body form button {
    padding: 10px 20px;
    font-size: 17px;
    border: none;
    background-color: #ff6600;
    color: white;
    border: 5px;
    cursor: pointer;
    transition: all .4s ease-in;
}

.contact-body form button:hover {
    background-color: #ff6681;
}


/* Footer */


.footer {
    background-color: #404040;
    border-top: 2px solid #333333;
}

.footer .footer-box {
    padding: 30px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.footer .footer-box .social-media a {
    color: white;
    background-color: #333333;
    border-radius: 50%;
    font-size: 17px;
    padding: 10px;
    margin: 5px;
}

.footer .footer-box .social-media a:hover {
    opacity: .7;
    transition: .5s all ease-in-out;
}

.footer .footer-box .copyright {
    color: white;
    font-size: 20px;
}

.footer .footer-box .brand {
    color: white;
    font-size: 20px;
}

.footer .footer-box .brand span {
    color: orange;
}

/* Responsive */

@media(max-width: 992px) {

    /* Header */

    header {
        flex-direction: column;
        height: 150px;
        background: linear-gradient(rgba(0, 0, 0, .2), rgba(0, 0, 0, .2));
    }

    .menu-header .logo a {
        font-size: 25px;
    }

    header nav ul li a {
        font-size: 16px;
        flex-direction: column;
        display: inline-block;
        margin-top: 10px;
    }

    header nav {
        display: flex;
        flex-direction: column;
    }

    .content h2 {
        font-size: 28px;
    }

    .content p {
        font-size: 18px;
    }
}


@media(max-width: 950px) {
    .contact .contact-box {
        flex: 100%;
    }
}

@media(max-width: 800px) {

    .menu .menu-content .hot-coffees,
    .cold-coffees,
    .frappucino-coffees {
        margin: 20px;
    }
}

@media(max-width: 700px) {
    .footer .footer-box .social-media a {
        color: white;
        background-color: #333333;
        border-radius: 50%;
        font-size: 16px;
        padding: 5px;
    }

    .footer .footer-box .copyright {
        color: white;
        font-size: 15px;
    }

    .footer .footer-box .brand {
        color: white;
        font-size: 18px;
    }
}

@media(max-width: 500px) {

    /* header */

    header {
        height: 130px;
    }

    header .logo a {
        font-size: 23px;
    }

    header nav ul li a {
        font-size: 13px;
        flex-direction: column;
        display: inline-block;
        margin-top: 10px;
    }

    header nav {
        display: flex;
        flex-direction: column;
    }


    /* Content */

    .content h2 {
        font-size: 23px;
    }

    .content p {
        font-size: 16px;
    }


    /* footer */

    .footer .footer-box {
        flex-direction: column;
    }

    .footer .footer-box .social-media a {
        color: white;
        background-color: #333333;
        border-radius: 50%;
        font-size: 16px;
        padding: 10px;
        margin-top: 10px;
        display: inline-block;
    }

    .footer .footer-box .copyright {
        color: white;
        font-size: 15px;
        margin-top: 10px;
    }

    .footer .footer-box .brand {
        color: white;
        font-size: 18px;
        margin-top: 10px;
    }

}


@media(max-width: 410px) {

    /* header */

    header {
        height: 120px;
    }

    header .logo a {
        font-size: 20px;
        color: white;
        padding: 15px 30px;
    }

    header nav ul li a {
        font-size: 12px;
        flex-direction: column;
        display: inline-block;
        margin-top: 10px;
        color: white;
        padding: 5px 5px;
    }

    header nav {
        display: flex;
        flex-direction: column;
    }

    /* content */

    .content h2 {
        font-size: 20px;
    }

    .content p {
        font-size: 13px;
    }

}