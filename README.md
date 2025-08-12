<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Traplol - Buy Script</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

  body {
    margin: 0;
    background: #121214;
    color: #e1e1e6;
    font-family: 'Poppins', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    padding: 20px;
  }

  .container {
    background: #1e1e1e;
    border-radius: 12px;
    padding: 30px 40px;
    max-width: 400px;
    width: 100%;
    box-shadow: 0 0 15px rgba(0,255,128,0.3);
    text-align: center;
  }

  .logo {
    font-weight: 700;
    font-size: 2.5rem;
    color: #00ff87;
    margin-bottom: 15px;
    letter-spacing: 2px;
  }

  .product-title {
    font-weight: 600;
    font-size: 1.3rem;
    margin-bottom: 30px;
  }

  .price-option {
    background: #272729;
    border-radius: 8px;
    margin-bottom: 20px;
    padding: 20px;
  }

  .price {
    font-weight: 700;
    font-size: 2rem;
    color: #00ff87;
    margin-bottom: 5px;
  }

  .desc {
    color: #a1a1aa;
    margin-bottom: 15px;
    font-size: 1rem;
  }

  .buy-btn {
    background: #00ff87;
    border: none;
    color: #121214;
    font-weight: 700;
    font-size: 1rem;
    padding: 12px 25px;
    border-radius: 8px;
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
    transition: background 0.3s ease;
  }

  .buy-btn:hover {
    background: #00cc6a;
  }

  @media (max-width: 480px) {
    .container {
      padding: 25px 20px;
    }
  }
</style>
</head>
<body>
  <div class="container">
    <div class="logo">Traplol</div>
    <div class="product-title">Choose your Script Plan</div>

    <div class="price-option">
      <div class="price">$9.99</div>
      <div class="desc">Lifetime Script</div>
      <a href="https://cash.app/$dealerplug" target="_blank" rel="noopener" class="buy-btn">Buy Now</a>
    </div>

    <div class="price-option">
      <div class="price">$5.99</div>
      <div class="desc">Monthly Script</div>
      <a href="https://cash.app/$dealerplug" target="_blank" rel="noopener" class="buy-btn">Buy Now</a>
    </div>
  </div>
</body>
</html>
