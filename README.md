# stephenfreshsalsa
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Fresh Salsa by Stephen</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #fffaf5;
  color: #333;
}
header {
  background: linear-gradient(135deg, #ff4e00, #ffb347);
  color: white;
  padding: 60px 20px;
  text-align: center;
}
section {
  padding: 50px 20px;
  max-width: 1000px;
  margin: auto;
}
h2 {
  color: #ff4e00;
}
.pricing {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}
.price-box {
  background: #ffe6d5;
  padding: 20px;
  border-radius: 10px;
  flex: 1;
  min-width: 200px;
  text-align: center;
}
.flavors {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
.flavor-box {
  background: #f9f9f9;
  padding: 20px;
  border-left: 6px solid #ff4e00;
  border-radius: 8px;
}
footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 30px 20px;
}
</style>
</head>
<body>

<header>
  <h1>Fresh Salsa by Stephen</h1>
  <p>Bold flavors. Fresh ingredients. Made with love.</p>
</header>

<section>
  <h2>About Us</h2>
  <p>
    Fresh Salsa by Stephen is a small-batch salsa business operated under Sasha LLC,
    offering over 23 handcrafted flavors ranging from sweet and mild to extreme heat.
    Every batch is made fresh using quality ingredients.
  </p>
</section>

<section>
  <h2>Pricing</h2>
  <div class="pricing">
    <div class="price-box">
      <h3>$6</h3>
      <p>Single Jar</p>
    </div>
    <div class="price-box">
      <h3>$15</h3>
      <p>Three Jars</p>
    </div>
  </div>
</section>

<section>
  <h2>Our Flavors (23+)</h2>
  <div class="flavors">

    <div class="flavor-box"><strong>Sweet & Tropical</strong><br>
    Tropical Mango, Strawberry, Cherry, Raspberry, Peach, Watermelon</div>

    <div class="flavor-box"><strong>Sweet Heat</strong><br>
    Mango Habanero, Cherry Habanero, Pineapple Jalapeño</div>

    <div class="flavor-box"><strong>Creamy & Savory</strong><br>
    Creamy Cucumber Curry, Guacamole, Spicy Guacamole</div>

    <div class="flavor-box"><strong>Classic & Bold</strong><br>
    Cilantro Mild, Tangy Garlic & Lime, Roasted Garlic & Olives, Black Bean & Corn,
    Spicy Black Bean & Corn, Smokin’ Chipotle</div>

    <div class="flavor-box"><strong>Hot & Extreme</strong><br>
    Cilantro Hot, Cilantro Hot XX, Verde Mild, Verde XX, Super Nova XXX</div>

  </div>
</section>

<section>
  <h2>Location</h2>
  <p>
    8110 E. Court Street<br>
    Davison, Michigan 48423
  </p>
</section>

<footer>
  <p>Fresh Salsa by Stephen © 2026</p>
  <p>Online ordering coming soon 🌶️</p>
</footer>

</body>
</html>
