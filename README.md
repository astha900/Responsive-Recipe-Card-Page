# Responsive-Recipe-Card-Page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Delicious Recipes</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Delicious Recipes</h1>
    <p>Discover our collection of mouth-watering recipes from around the world. Perfect for any occasion!</p>
  </header>
  
  <div class="filter">
    <h3>Filter by Cuisine:</h3>
    <button class="filter-button">All</button>
    <button class="filter-button">Italian</button>
    <button class="filter-button">Mexican</button>
    <button class="filter-button">Asian</button>
    <button class="filter-button">Mediterranean</button>
  </div>

  <div class="recipe-cards">
    <div class="recipe-card">
      <img src="pizza.jpg" alt="Classic Margherita Pizza">
      <h2>Classic Margherita Pizza</h2>
      <p class="description">A traditional Italian pizza with fresh mozzarella, tomatoes, and basil.</p>
      <div class="rating">Rate this recipe: ★★★★☆</div>
    </div>
    
    <div class="recipe-card">
      <img src="tacos.jpg" alt="Beef Tacos">
      <h2>Beef Tacos</h2>
      <p class="description">Delicious and easy-to-make beef tacos with fresh toppings.</p>
      <div class="rating">Rate this recipe: ★★★★☆</div>
    </div>
    
    <div class="recipe-card">
      <img src="pad_thai.jpg" alt="Pad Thai">
      <h2>Pad Thai</h2>
      <p class="description">A stir-fried noodle dish with a perfect balance of sweet, sour, and savory flavors.</p>
      <div class="rating">Rate this recipe: ★★★★☆</div>
    </div>
    <!-- Add more recipe cards here -->
  </div>

  <footer>
    <p>&copy; 2025 Delicious Recipes. All rights reserved.</p>
  </footer>
</body>
</html>


/* Reset some default styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* General styles */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  color: #333;
}

header {
  text-align: center;
  padding: 20px;
  background-color: #ffcc00;
}

h1 {
  margin-bottom: 10px;
}

.filter {
  text-align: center;
  margin: 20px 0;
}

.filter-button {
  background-color: #fff;
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 10px 15px;
  margin: 0 5px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.filter-button:hover {
  background-color: #ffcc00;
}

/* Recipe card styles */
.recipe-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 20px;
}

.recipe-card {
  background-color: white;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  padding: 20px;
  width: 300px;
  text-align: center;
}

.recipe-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 5px;
  margin-bottom: 10px;
}

.recipe-card h2 {
  font-size: 18px;
  margin-bottom: 10px;
}

.recipe-card .description {
  font-size: 14px;
  color: #666;
  margin-bottom: 15px;
}

.rating {
  font-size:
  14px;
  color: #ffcc00; /* Gold color for stars */
}

/* Footer styles */
footer {
  text-align: center;
  padding: 20px;
  background-color: #ffcc00;
  position: relative;
  bottom: 0;
  width
