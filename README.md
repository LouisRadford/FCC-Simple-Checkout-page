# FCC-Simple-Checkout-page
Simple HTML5 Checkout page 


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
</head>
<body>
<h1>Checkout</h1>
<section>
    <h2>Your Cart</h2>
    <img src='https://cdn.freecodecamp.org/curriculum/labs/cube.jpg'alt='an image of a rubics cube'></img>
    <p>A rubics cube</p>
    <p>£12.99</p>
</section>
<section>
    <h2>Payment Information</h2>
    <form>
    <label for='card-name'>Cardholder name</label>
        <input aria-required='true'
        id='card-name'
        type='card-name'
        name='card-name'
        placeholder='Mr. John Doe'
        required='true'
        >
       <label for='card-number'>Card Number</label>
       <input aria-required='true'
       id='card-number'
       type='card-number'
       name='card-number'
       required='true'
       >
       <label for='expiry-date'>Expiry Date</label>
       <input aria-required='true'
       id='expiry-date'
       type='expiry-date'
       name='expiry-date'
       placeholder='MM/YY'
       required='true'
       >
       <label for='CVV'>CVV</label>
       <input aria-required='true'
       id='CVV'
       name='CVV'
       placeholder='666'
       required='true'
       >
       <br></br>
      <button id='submit'>Submit</button>
    </form>
</section>
</body>
</html>
