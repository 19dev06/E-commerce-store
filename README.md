<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>My Online Store</title>
<style>
  /* Minimal CSS — keeps layout like the screenshot */
  body{font-family:"Times New Roman",serif;margin:16px;color:#111}
  .wrap{max-width:960px;margin:0 auto}
  header{text-align:center}
  h1{font-size:22px;margin:0}
  p.lead{margin:6px 0 12px;color:#444;font-size:14px}
  nav{text-align:center;margin-bottom:8px}
  nav button{font-size:12px;padding:4px 8px;margin:0 4px}
  hr{border:0;height:1px;background:#ddd;margin:12px 0}
  h2{font-size:18px;margin:12px 0 6px}
  table{width:100%;border-collapse:collapse;font-size:14px;margin-bottom:12px}
  th,td{border:1px solid #333;padding:6px;text-align:left}
  th{background:#f4f4f4}
  label{display:block;margin-top:8px;font-size:14px}
  input,select,textarea{width:260px;max-width:100%;padding:6px;border:1px solid #bbb;box-sizing:border-box}
  textarea{height:70px;display:block}
  .small{font-size:13px;color:#333}
  button.action{padding:6px 10px;margin-top:8px}
  footer{text-align:center;margin-top:18px;font-size:12px;color:#666}
  @media(max-width:520px){input,select,textarea{width:100%}}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <h1>My Online Store</h1>
    <p class="lead">Welcome to our small online shop for clothes, electronics and crafts!</p>
  </header>

  <nav>
    <button>PRODUCTS</button>
    <button>CART</button>
    <button>CHECKOUT</button>
  </nav>

  <hr>

  <h2>Our Products</h2>
  <table>
    <thead>
      <tr><th>Product Name</th><th>Description</th><th>Category</th><th>Price</th><th>Add to Cart</th></tr>
    </thead>
    <tbody>
      <tr>
        <td>Cotton T-Shirt</td>
        <td>Comfortable cotton t-shirt for all seasons</td>
        <td>Clothing</td>
        <td>₹1,499</td>
        <td><input type="checkbox" disabled></td>
      </tr>
      <tr>
        <td>Wireless Headphones</td>
        <td>Bluetooth headphones with long battery life</td>
        <td>Electronics</td>
        <td>₹1,499</td>
        <td><input type="checkbox" disabled></td>
      </tr>
      <tr>
        <td>Handmade Clay Pot</td>
        <td>Beautiful handmade pot by local artists</td>
        <td>Crafts</td>
        <td>₹1,799</td>
        <td><input type="checkbox" disabled></td>
      </tr>
      <tr>
        <td>Smart Watch</td>
        <td>Tracks your steps and health activity</td>
        <td>Electronics</td>
        <td>₹2,499</td>
        <td><input type="checkbox" disabled></td>
      </tr>
    </tbody>
  </table>

  <h2>Shopping Cart (static)</h2>
  <!-- This cart is static HTML (no JS). Update values here when needed. -->
  <table>
    <thead>
      <tr><th>Product</th><th>Price</th><th>Quantity</th><th>Total</th></tr>
    </thead>
    <tbody>
      <tr><td>Cotton T-Shirt</td><td>₹1,499</td><td>1</td><td>₹1,499</td></tr>
      <tr><td>Wireless Headphones</td><td>₹1,499</td><td>1</td><td>₹1,499</td></tr>
    </tbody>
    <tfoot>
      <tr>
        <td colspan="3" style="text-align:right"><strong>Grand Total:</strong></td>
        <td><strong>₹2,998</strong></td>
      </tr>
    </tfoot>
  </table>

  <h2>Checkout</h2>
  <form onsubmit="return false;">
    <label>Full Name:
      <input type="text" name="fullname" placeholder="Your name">
    </label>
    <label>Email:
      <input type="email" name="email" value="dev069975@gmail.com">
    </label>
    <label>Shipping Address:
      <textarea name="address">Ghaziabad, India</textarea>
    </label>
    <label>Payment Method:
      <select name="payment">
        <option>Credit Card</option>
        <option>UPI</option>
        <option>Cash on Delivery</option>
      </select>
    </label>
    <button class="action" type="submit">Place Order</button>
  </form>

  <hr>

  <section class="contact small">
    <strong>Contact Us</strong><br>
    My E-Store, Main Road<br>
    <strong>Phone:</strong> 7982737536<br>
    <strong>Email:</strong> <a href="mailto:dev069975@gmail.com">dev069975@gmail.com</a>
  </section>

  <footer>© 2025 My E-Commerce Store | Created by Dev Sharma</footer>
</div>
</body>
</html>
