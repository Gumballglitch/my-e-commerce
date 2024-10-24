# my-e-commerce
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional E-commerce Platform</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to Your E-commerce Platform</h1>
            <p>Build your online store, integrate payments, and customize your brand.</p>
            <a href="login.html" class="btn">Get Started</a>
        </div>
    </header>

    <section id="features">
        <div class="feature">
            <h2>Store Creation</h2>
            <p>Create and customize your online store in minutes.</p>
        </div>
        <div class="feature">
            <h2>Payment Integration</h2>
            <p>Seamless payment options for your customers.</p>
        </div>
        <div class="feature">
            <h2>Complete Customization</h2>
            <p>Tailor your store’s look and feel with easy design tools.</p>
        </div>
    </section>

    <section id="pricing">
        <h2>Choose Your Plan</h2>
        <div class="plan">
            <h3>Basic</h3>
            <p>R100 / month</p>
        </div>
        <div class="plan">
            <h3>Pro</h3>
            <p>R250 / month</p>
        </div>
        <div class="plan">
            <h3>Enterprise</h3>
            <p>R500 / month</p>
        </div>
    </section>

    <footer>
        <ul>
            <li><a href="terms.html">Terms of Service</a></li>
            <li><a href="privacy.html">Privacy Policy</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </footer>
</body>
</html>
/* styles.css */
body {
    font-family: 'Roboto', sans-serif;
    background-color: #000;
    color: #fff;
    margin: 0;
    padding: 0;
}

header {
    background: #1c1c1c;
    text-align: center;
    padding: 50px;
}

h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

p {
    font-size: 1.2em;
    color: #ddd;
}

.btn {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

#features, #pricing {
    padding: 50px 20px;
    text-align: center;
}

.plan {
    background-color: #2c2c2c;
    color: #fff;
    padding: 20px;
    margin: 10px;
    display: inline-block;
    width: 200px;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - E-commerce Platform</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <h2>Login to Your Account</h2>
        <form id="loginForm" action="/login" method="POST">
            <input type="email" id="email" name="email" placeholder="Email" required>
            <input type="password" id="password" name="password" placeholder="Password" required>
            <button type="submit" class="btn">Login</button>
        </form>
        <p>Or log in with:</p>
        <div class="social-login">
            <button class="btn google-btn">Google</button>
            <button class="btn facebook-btn">Facebook</button>
            <button class="btn apple-btn">Apple</button>
        </div>
        <p>Don't have an account? <a href="register.html">Sign up</a></p>
    </div>
</body>
</html>
/* styles.css continued */
.login-container {
    max-width: 400px;
    margin: 100px auto;
    background-color: #1c1c1c;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

.login-container h2 {
    color: #fff;
    margin-bottom: 20px;
}

.login-container input {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    background-color: #333;
    border: none;
    border-radius: 5px;
    color: #fff;
}

.login-container .btn {
    width: 100%;
    padding: 10px;
    background-color: #555;
    border: none;
    color: #fff;
    margin-top: 10px;
    cursor: pointer;
    border-radius: 5px;
}

.social-login button {
    width: 32%;
    padding: 10px;
    margin: 5px;
    background-color: #444;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard - E-commerce Platform</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Store Dashboard</h1>
        <p>Welcome, [User's Name]</p>
    </header>

    <section id="dashboard">
        <div class="stats">
            <h3>Sales</h3>
            <p>R2000</p>
        </div>
        <div class="stats">
            <h3>Products</h3>
            <p>50</p>
        </div>
        <div class="stats">
            <h3>Visitors</h3>
            <p>300</p>
        </div>
    </section>

    <section id="manage-products">
        <h2>Manage Products</h2>
        <button class="btn">Add New Product</button>
        <button class="btn">View All Products</button>
    </section>
</body>
</html>
/* styles.css continued */
#dashboard {
    display: flex;
    justify-content: space-around;
    margin: 20px 0;
}

.stats {
    background-color: #2c2c2c;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

.stats h3 {
    color: #fff;
}

.stats p {
    font-size: 1.5em;
    color: #fff;
}

#manage-products {
    text-align: center;
}

#manage-products .btn {
    margin: 10px;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Setup Your Store - E-commerce Platform</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="setup-container">
        <h2>Set Up Your Store</h2>
        <form id="setupWizard" action="/setup-store" method="POST">
            <input type="text" id="storeName" name="storeName" placeholder="Store Name" required>
            <input type="text" id="storeDomain" name="storeDomain" placeholder="Store Domain" required>
            <select name="paymentMethod" id="paymentMethod" required>
                <option value="">Select Payment Method</option>
                <option value="paypal">PayPal</option>
                <option value="stripe">Stripe</option>
            </select>
            <button type="submit" class="btn">Complete Setup</button>
        </form>
    </div>
</body>
</html>
/* styles.css continued */
.setup-container {
    max-width: 500px;
    margin: 100px auto;
    background-color: #1c1c1c;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

.setup-container h2 {
    color: #fff;
    margin-bottom: 20px;
}

.setup-container input, .setup-container select {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    background-color: #333;
    border: none;
    border-radius: 5px;
    color: #fff;
}

.setup-container .btn {
    width: 100%;
    padding: 10px;
    background-color: #555;
    border: none;
    color: #fff;
    margin-top: 10px;
    cursor: pointer;
    border-radius: 5px;
}
<section id="products">
    <h2>Our Products</h2>
    <div class="product">
        <h3>Product Name</h3>
        <p>R100</p>
        <button class="btn">Add to Cart</button>
    </div>
    <div class="product">
        <h3>Product Name 2</h3>
        <p>R150</p>
        <button class="btn">Add to Cart</button>
    </div>
</section>
/* styles.css continued */
#products {
    text-align: center;
    padding: 50px 0;
}

.product {
    background-color: #2c2c2c;
    margin: 20px auto;
    padding: 20px;
    width: 250px;
    display: inline-block;
    border-radius: 10px;
}
/* Responsive CSS */
@media only screen and (max-width: 768px) {
    .container, .login-container, .setup-container {
        width: 90%;
        padding: 10px;
    }

    .product {
        width: 100%;
    }

    #dashboard {
        flex-direction: column;
        align-items: center;
    }
}
document.getElementById('loginForm').addEventListener('submit', function(event) {
    event.preventDefault();
    const email = document.getElementById('email').value;
    const password = document.getElementById('password').value;

    // Simulate server request
    if(email && password) {
        console.log('Logged in successfully');
        window.location.href = "dashboard.html";  // Redirect to dashboard
    } else {
        alert('Please enter valid credentials');
    }
});

// Social login (simulated)
document.querySelector('.google-btn').addEventListener('click', function() {
    alert('Logging in with Google');
    window.location.href = "dashboard.html";  // Redirect to dashboard
});

document.querySelector('.facebook-btn').addEventListener('click', function() {
    alert('Logging in with Facebook');
    window.location.href = "dashboard.html";  // Redirect to dashboard
});

document.querySelector('.apple-btn').addEventListener('click', function() {
    alert('Logging in with Apple');
    window.location.href = "dashboard.html";  // Redirect to dashboard
});
// Simulating product and sales data
const storeData = {
    sales: 2000,
    products: 50,
    visitors: 300
};

document.addEventListener('DOMContentLoaded', function() {
    // Update dashboard stats
    document.querySelector('.stats:nth-child(1) p').innerText = `R${storeData.sales}`;
    document.querySelector('.stats:nth-child(2) p').innerText = storeData.products;
    document.querySelector('.stats:nth-child(3) p').innerText = storeData.visitors;
});
document.getElementById('setupWizard').addEventListener('submit', function(event) {
    event.preventDefault();
    
    const storeName = document.getElementById('storeName').value;
    const storeDomain = document.getElementById('storeDomain').value;
    const paymentMethod = document.getElementById('paymentMethod').value;

    if(storeName && storeDomain && paymentMethod) {
        alert(`Store "${storeName}" setup complete!`);
        window.location.href = "dashboard.html";  // Redirect to dashboard
    } else {
        alert('Please complete all fields');
    }
});
let cart = [];

document.querySelectorAll('.product .btn').forEach(button => {
    button.addEventListener('click', function() {
        const productName = this.parentElement.querySelector('h3').innerText;
        const productPrice = this.parentElement.querySelector('p').innerText;

        // Add product to cart
        cart.push({ name: productName, price: productPrice });
        alert(`${productName} added to cart!`);
    });
});
