This is my Assignment so for for the Master Course at the Swinburne University Creating Web Application.

You can get to the website by clicking on the link on the right handside of the about section.

So far I used HTML, CSS and JavaScript. PHP and MySQL will follow in the following weeks to create the Backend.

In the following I will briefly describe the interesting parts of the Website.

# Index.html
On the homepage of the website is a Menu which adapts to window width. This applies on the other pages as well.

On the bottom of the homepage there is an animation to figure out the delivery time.
When you hover with your moves over the states the "delivery box" in the top right corner will change it's content to the delivery time
and the box hovers in different velocities to the destination. The velocities are dependent on the delivery time.
At the time i created this animation only HTML and CSS was allowed and were used to build this animation.

# Product.html
On the Products side there are shown the products. When you make the window narrow the product will rearange. 
If the window becomse to small the form of displaying the products will change to an image slider.

Under the aside element on the right side, there is a button to get to the style checker where you can check the look of a VR Headset on my face.

In the style checker you can change the VR-Headset widths.

# Enquire.html
Here you can make an enquire the input is checked by HTML input attributes and JavaScript Code.
The Postcode input is crosschecked with the selected state to make sure the postcode is right if the input is invalid a message is displayed with details on the error.
The price can be calculated by selecting a product and entering a valid amount.
By clicking on Pay now button the input is stored in the SessionStorage transferred to the next page implied the input is valid.

# Payment
Here is a Timer running. After the timer runs out of time the sessionStorage is cleared and you are redirected to the homepage.
The Credit Card details input is checked by JavaScript code and prevents you from submitting invalid input. Credit Card number has 15-16 digits and starts with certain numbers depending on the Credit Card type.
