# Assignment 1

Design a simple web page that displays information about a fictional restaurant. The web page should include the following elements:

1. A header section including the restaurant name and a navigation menu with links to different website sections.
2. The main content section includes information about the restaurant's menu, specials, and hours of operation.
3. A footer section including contact information for the restaurant, such as the address, phone number, and email address.

## About Webpage
This is a simple static website for an Indian restaurant. This webpage is designed to showcase the menu of the Indian Express Restaurant, which serves Indian cuisine. It is designed using HTML and CSS and includes a navigation menu, a header, and four sections: Appetizers, Specials, Desserts, and Beverages. Each section contains an image, a title, a description, and a price of the food item.


### Features
##### Navigation bar
A fixed navigation bar is present at the top of the website that allows users to navigate to different sections of the website. The fixed property is utilized so the header is fixed when the user scrolls the web page.

```bash
<header>
        <div class="restaurant_header text-center">
            <h1>Indian Express Restaurant</h1>
            <p>Bringing class to cuisine</p>
        </div>
        <ul class="navigation_ul">
            <li class="navigation_li"><a href="#appetizers">Appetizers</a></li>
            <li class="navigation_li"><a href="#specials">Specials</a></li>
            <li class="navigation_li"><a href="#desserts">Desserts</a></li>
            <li class="navigation_li"><a href="#beverages">Beverages</a></li>
            <li class="logo"><a href="#appetizers"><strong>Indian Express Restaurant</strong></a></li>
        </ul>
</header>
```

```
<!-- To fix the header -->
position: fixed;
```

##### Appetizers
A section that displays two different types of appetizers and their description and price.
```
<main>
        <div id="appetizers">
            <h2>Appetizers</h2>
            <ul>


                <li>
                    <h3>Samosa</h3>
                    <p>A crispy pastry filled with spiced potatoes and peas.</p>
                    <p>Price: $5.99</p>
                    <img src="D:\cyber securitty course\course 4\GIT Exer\images\samosa.jpg" alt="Samosa">
                </li>
                <li>

                    <h3>Pakora</h3>
                    <p>Vegetables or chicken dipped in chickpea batter and fried.</p>
                    <p>Price: $6.99</p>
                    <img src="D:\cyber securitty course\course 4\GIT Exer\images\pakora.jpg" alt="Pakora">
                </li>
            </ul>
        </div>
```

##### Specials
A section that displays two different types of specials along with their description and price.
```
<div id="specials">
            <h2>Specials</h2>
            <ul>
                <li>

                    <h3>Shahi Paneer</h3>

                    <p> Shahi Paneer is a Mughlai dish where paneer is cooked in a creamy gravy made of onions, yogurt,
                        nut and seeds.</p>
                    <p>Price: $14.99</p>
                    <img src="D:\cyber securitty course\course 4\GIT Exer\New folder\shahipanner.jpg"
                        alt="Shahi paneer">
                </li>
                <li>

                    <h3>Kadhai Paneer</h3>
                    <p> Kadai Paneer is a spicy, warming, flavorful and super delicious dish made by cooking paneer &
                        bell peppers in a fragrant, fresh ground spice.</p>
                    <p>Price: $12.99</p>
                    <img src="D:\cyber securitty course\course 4\GIT Exer\kadaipanner.jpg" alt="Kadhai Paneer">
                </li>
            </ul>
        </div>
```
##### Desserts
A section that displays two different types of desserts along with their description and price.
```
 <div id="desserts">
            <h2>Desserts</h2>
            <ul>
                <li>

                    <h3>Gulab Jamun</h3>
                    <p>Fried dough balls soaked in a sweet syrup.</p>
                    <p>Price: $4.99</p>
                    <img src="D:\cyber securitty course\course 4\GIT Exer\images\gulab.jpg" alt="Gulab Jamun">
                </li>
                <li>

                    <h3>jalebi</h3>
                    <p>Jalebi is made by deep-frying maida flour batter in pretzel or circular shapes, which are then
                        soaked in sugar syrup..</p>
                    <p>Price: $3.99</p>
                    <img src="D:\cyber securitty course\course 4\GIT Exer\images\jalebi.jpg" alt="Jalebi">
                </li>
            </ul>
        </div>
```

##### Beverages
A section that displays a beverage along with their description and price.
```
<div id="beverages">
            <h2>Beverages</h2>
            <ul>
                <li>

                    <h3>Lassi</h3>
                    <p>A sweet or salty yogurt-based drink.</p>
                    <p>Price: $2.99</p>
                    <img src="D:\cyber securitty course\course 4\GIT Exer\images\lassi.jpg" alt="Lassi">
                </li>

        </div>
```

##### Footer
A footer section is present at the bottom of the website that contains the contact information for the restaurant.
```
 <footer>
            <p>Contact us:</p>
            <p>100 Markham, Toronto, ON</p>
            <p>Email: food@IE.com</p>
            <p>Phone: 000-000-0000</p>
        </footer>
```
### Usage
To use this webpage, open the Assignment_1_RichaDwivedi.html file in a web browser. The webpage should load and display correctly.


### Contributing
Contributions to this repository are welcome. You can contribute by creating a pull request. 
## License

This project is licensed under the terms of the MIT license.



[MIT](https://choosealicense.com/licenses/mit/)
