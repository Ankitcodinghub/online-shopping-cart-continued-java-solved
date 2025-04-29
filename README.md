# online-shopping-cart-continued-java-solved
**TO GET THIS SOLUTION VISIT:** [Online shopping cart (continued) (Java) Solved](https://www.ankitcodinghub.com/product/online-shopping-cart-continued-java-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;5857&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Online shopping cart (continued) (Java) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
This program extends the earlier “Online shopping cart” program. (Consider first saving your earlier program).

(1) Extend the ItemToPurchase class per the following specifications:

<ul>
<li>Private fieldsstring itemDescription – Initialized in default constructor to “none”</li>
<li>Parameterized constructor to assign item name, item description, item price, and item quantity (default values of 0). (1 pt)</li>
<li>Public member methodssetDescription() mutator &amp; getDescription() accessor (2 pts)</li>
<li>printItemCost() – Outputs the item name followed by the quantity, price, and subtotal</li>
<li>printItemDescription() – Outputs the item name and description</li>
</ul>
Ex. of printItemCost() output:

<pre class="ql-syntax ql-align-center"><span class="hljs-attribute">Bottled</span> Water <span class="hljs-number">10</span> @ <span class="hljs-variable">$1</span> = <span class="hljs-variable">$10</span>
</pre>
Ex. of printItemDescription() output:

<pre class="ql-syntax ql-align-center"><span class="hljs-attribute">Bottled</span> Water: Deer Park, <span class="hljs-number">12</span> oz.
</pre>
(2) Create two new files:

<ul>
<li>ShoppingCart.java – Class definition</li>
<li>ShoppingCartManager.java – Contains main() method</li>
</ul>
Build the ShoppingCart class with the following specifications. Note: Some can be method stubs (empty methods) initially, to be completed in later steps.

<ul>
<li>Private fieldsString customerName – Initialized in default constructor to “none”</li>
<li>String currentDate – Initialized in default constructor to “January 1, 2016”</li>
<li>ArrayList cartItems</li>
<li>Default constructor</li>
<li>Parameterized constructor which takes the customer name and date as parameters (1 pt)</li>
<li>Public member methods</li>
<li>getCustomerName() accessor (1 pt)</li>
<li>getDate() accessor (1 pt)</li>
<li>addItem()Adds an item to cartItems array. Has parameter ItemToPurchase. Does not return anything.</li>
<li>removeItem()Removes item from cartItems array. Has a string (an item’s name) parameter. Does not return anything.</li>
<li>If item name cannot be found, output this message:&nbsp;Item not found in cart. Nothing removed.</li>
<li>modifyItem()Modifies an item’s description, price, and/or quantity. Has parameter ItemToPurchase. Does not return anything.</li>
<li>If item can be found (by name) in cart, check if parameter has default values for description, price, and quantity. If not, modify item in cart.</li>
<li>If item cannot be found (by name) in cart, output this message:&nbsp;Item not found in cart. Nothing modified.</li>
<li>getNumItemsInCart() (2 pts)Returns quantity of all items in cart. Has no parameters.</li>
<li>getCostOfCart() (2 pts)Determines and returns the total cost of items in cart. Has no parameters.</li>
<li>printTotal()Outputs total of objects in cart.</li>
<li>If cart is empty, output this message:&nbsp;SHOPPING CART IS EMPTY</li>
<li>printDescriptions()Outputs each item’s description.</li>
</ul>
Ex. of printTotal() output:

<pre class="ql-syntax ql-align-center"><span class="hljs-attribute">John</span> Doe<span class="hljs-string">'s Shopping Cart - February 1, 2016
Number of Items: 8

Nike Romaleos 2 @ <span class="hljs-variable">$189</span> = <span class="hljs-variable">$378</span>
Chocolate Chips 5 @ <span class="hljs-variable">$3</span> = <span class="hljs-variable">$15</span>
Powerbeats 2 Headphones 1 @ <span class="hljs-variable">$128</span> = <span class="hljs-variable">$128</span>

Total: <span class="hljs-variable">$521</span>
</span></pre>
Ex. of printDescriptions() output:

<pre class="ql-syntax ql-align-center"><span class="hljs-attribute">John</span> Doe<span class="hljs-string">'s Shopping Cart - February 1, 2016

Item Descriptions
Nike Romaleos: Volt color, Weightlifting shoes
Chocolate Chips: Semi-sweet
Powerbeats 2 Headphones: Bluetooth headphones
</span></pre>
(3) In main(), prompt the user for a customer’s name and today’s date. Output the name and date. Create an object of type ShoppingCart. (1 pt)

Ex.

<pre class="ql-syntax ql-align-center"><span class="hljs-attribute">Enter</span> Customer<span class="hljs-string">'s Name:
John Doe
Enter Today'</span>s Date:
February <span class="hljs-number">1</span>, <span class="hljs-number">2016</span>

Customer Name: John Doe
Today<span class="hljs-string">'s Date: February 1, 2016
</span></pre>
(4) Implement the printMenu() method. printMenu() has a ShoppingCart parameter, and outputs a menu of options to manipulate the shopping cart. Each option is represented by a single character. Build and output the menu within the method.

If the an invalid character is entered, continue to prompt for a valid choice.&nbsp;<em>Hint: Implement Quit before implementing other options.</em>&nbsp;Call printMenu() in the main() method. Continue to execute the menu until the user enters q to Quit. (3 pts)

Ex:

<pre class="ql-syntax ql-align-center">MENU
a - Add item to cart
d - Remove item from cart
c - <span class="hljs-keyword">Change</span> item quantity
i - <span class="hljs-keyword">Output</span> items<span class="hljs-string">' descriptions
o - Output shopping cart
q - Quit

Choose an option: 
</span></pre>
(5) Implement Output shopping cart menu option. (3 pts)

Ex:

<pre class="ql-syntax ql-align-center"><span class="hljs-attribute">OUTPUT</span> SHOPPING CART
John Doe<span class="hljs-string">'s Shopping Cart - February 1, 2016
Number of Items: 8

Nike Romaleos 2 @ <span class="hljs-variable">$189</span> = <span class="hljs-variable">$378</span>
Chocolate Chips 5 @ <span class="hljs-variable">$3</span> = <span class="hljs-variable">$15</span>
Powerbeats 2 Headphones 1 @ <span class="hljs-variable">$128</span> = <span class="hljs-variable">$128</span>

Total: <span class="hljs-variable">$521</span>
</span></pre>
(6) Implement Output item’s description menu option. (2 pts)

Ex.

<pre class="ql-syntax ql-align-center"><span class="hljs-attribute">OUTPUT</span> ITEMS<span class="hljs-string">' DESCRIPTIONS
John Doe'</span>s Shopping Cart - February <span class="hljs-number">1</span>, <span class="hljs-number">2016</span>

Item Descriptions
Nike Romaleos: Volt color, Weightlifting shoes
Chocolate Chips: Semi-sweet
Powerbeats <span class="hljs-number">2</span> Headphones: Bluetooth headphones
</pre>
(7) Implement Add item to cart menu option. (3 pts)

Ex:

<pre class="ql-syntax ql-align-center"><span class="hljs-attribute">ADD</span> ITEM TO CART
Enter the item name:
Nike Romaleos
Enter the item description:
Volt color, Weightlifting shoes
Enter the item price:
<span class="hljs-number">189</span>
Enter the item quantity:
<span class="hljs-number">2</span>
</pre>
(8) Implement Remove item menu option. (4 pts)

Ex:

<pre class="ql-syntax ql-align-center">REMOVE ITEM FROM CART
Enter name <span class="hljs-keyword">of</span> item to remove:
Chocolate Chips
</pre>
(9) Implement Change item quantity menu option.&nbsp;<em>Hint: Make new ItemToPurchase object and use ItemToPurchase modifiers before using modifyItem() method.</em>&nbsp;(5 pts)

Ex:

<pre class="ql-syntax ql-align-center"><span class="hljs-keyword">CHANGE</span> ITEM QUANTITY
Enter the item <span class="hljs-keyword">name</span>:
Nike Romaleos
Enter the <span class="hljs-keyword">new</span> quantity:
<span class="hljs-number">3</span>
</pre>
