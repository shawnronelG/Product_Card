# Product Card Design with Hover Effect using CSS
## Date:
09/03/2026
## AIM:
To design a Product Card for an E-commerce website using HTML and CSS and apply hover effects, transitions, and styling techniques to create an interactive user interface.

## DESIGN STEPS:

### Step 1:
Create a basic HTML structure using ```<!DOCTYPE html>, <html>, <head>, and <body>```.

### Step 2:
Add a container div for the product card.

### Step 3:
Insert the product image using the ```<img>``` tag.

### Step 4:
Add product name, description, and price using ```<h3>``` and ```<p>``` tags.

### Step 5:
Create an Add to Cart button using the ```<button>``` tag.

### Step 6:
Style the product card using CSS by applying:
<ul>
  <li>width</li>
  <li>padding</li>
  <li>border-radius</li>
  <li>box-shadow</li>
</ul>

### Step 7:
Align the card content using text-align and spacing properties.

### Step 8:
Add hover effects using :hover selector.

### Step 9:
Apply transform: translateY() to move the card slightly upward on hover.

### Step 10:
Increase the box-shadow to create a lifting effect.

### Step 11:
Add transform: scale() to slightly zoom the product image on hover.

### Step 12:
Apply transition property to make the hover animation smooth.

### Step 13:
Create a footer section at the bottom of the page.

### Step 14:
Display Learner Name and Register Number inside the footer.

### Step 15:
Style the footer using background color and center alignment.

### Step 10:
Test your webpage in a browser.

## PROGRAM:
```
<style>

body{
    font-family: Arial, sans-serif;
    background-color:#f5f5f5;
    margin:0;
    display:flex;
    flex-direction:column;
    min-height:100vh;
}

.container{
    flex:1;
    display:flex;
    justify-content:center;
    align-items:center;
}

.product-card{
    width:300px;
    background:white;
    border-radius:15px;
    text-align:center;
    padding:20px;
    box-shadow:0 6px 12px rgba(0,0,0,0.2);
    transition:0.3s;
}

.product-card img{
    width:100%;
    border-radius:10px;
    transition:0.3s;
}

.product-card h2{
    margin:15px 0 10px;
}

.product-card p{
    font-size:14px;
    color:#555;
}

.price{
    font-size:20px;
    font-weight:bold;
    margin:10px 0;
}

button{
    padding:10px 20px;
    border:none;
    border-radius:8px;
    background:#007BFF;
    color:white;
    cursor:pointer;
    transition:0.3s;
}

.product-card:hover{
    transform:translateY(-10px);
    box-shadow:0 15px 25px rgba(0,0,0,0.3);
}

.product-card:hover img{
    transform:scale(1.1);
}

.product-card:hover button{
    background:#ff4d4d;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
}

</style>
</head>

<body>

<div class="container">

<div class="product-card">

<img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e" alt="Wireless Headphones">

<h2>Wireless Headphones</h2>

<p>Premium noise-cancelling wireless headphones with long battery life.</p>

<div class="price">₹2999</div>

<button>Add to Cart</button>

</div>

</div>

<footer>
Learner Name: G SHAWN RONEL <br>
Register Number: 25005544
</footer>

</body>
</html>
```

## OUTPUT:
<img width="1916" height="1068" alt="image" src="https://github.com/user-attachments/assets/44a812a3-d3c8-49c2-8a40-47acb0971db8" />

## RESULT:
The Product Card with Hover Effect was successfully designed using HTML and CSS.
