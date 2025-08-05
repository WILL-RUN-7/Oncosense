<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OncoSense - Early Cancer Detection Wearable</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
  <style>
    body {
      background-color: #f0f8ff;
    }
    .primary-bg {
      background-color: #2563eb;
    }
    .primary-hover:hover {
      background-color: #1d4ed8;
    }
    .primary-text {
      color: #2563eb;
    }
    .primary-border {
      border-color: #2563eb;
    }
  </style>
  <script>
    let cart = [];

    function handleAddToCart(product, price) {
      cart.push({ product, price });
      alert(`${product} added to cart. Total items: ${cart.length}`);
      updateCartUI();
    }

    function removeFromCart(index) {
      cart.splice(index, 1);
      updateCartUI();
    }

    function updateCartUI() {
      const cartList = document.getElementById("cartList");
      const cartSummary = document.getElementById("cartSummary");
      cartList.innerHTML = "";
      let subtotal = 0;
      cart.forEach((item, index) => {
        const li = document.createElement("li");
        li.className = "flex justify-between items-center px-4 py-2 bg-white border rounded shadow-sm";
        li.innerHTML = `<span>${item.product} - ₹${item.price}</span><button onclick="removeFromCart(${index})" class="text-red-500 hover:text-red-700">Remove</button>`;
        cartList.appendChild(li);
        subtotal += item.price;
      });
      const gst = subtotal * 0.18;
      const tax = subtotal * 0.05;
      const total = subtotal + gst + tax;
      cartSummary.innerHTML = `
        <p class='mb-1'>Subtotal: ₹${subtotal.toFixed(2)}</p>
        <p class='mb-1'>GST (18%): ₹${gst.toFixed(2)}</p>
        <p class='mb-1'>Tax (5%): ₹${tax.toFixed(2)}</p>
        <p class='font-bold text-lg'>Total: ₹${total.toFixed(2)}</p>
        <button onclick="checkout()" class="mt-4 bg-green-600 text-white px-4 py-2 rounded hover:bg-green-700">Proceed to Checkout</button>
      `;
    }

    function handleDoctorSearch(event) {
      event.preventDefault();
      const location = document.getElementById("doctorLocation").value;
      const mapFrame = document.getElementById("mapFrame");
      mapFrame.src = `https://www.google.com/maps?q=oncologist+near+${location}&output=embed`;
    }

    function handleContactForm(event) {
      event.preventDefault();
      const name = document.getElementById("contactName").value;
      alert(`Thank you, ${name}! Your message has been sent successfully.`);
      window.location.href = "thankyou.html";
    }

    function checkout() {
      window.location.href = "checkout.html";
    }
  </script>
</head>
<body class="text-gray-800">
  <section class="py-12 text-center bg-white">
    <h1 class="text-4xl font-bold primary-text mb-4">OncoSense™</h1>
    <p class="text-lg">Early Cancer Detection Wearable Patch & Band</p>
  </section>

  <section class="py-8 px-4 bg-blue-100">
    <div class="max-w-4xl mx-auto text-center">
      <p class="text-lg text-gray-700 mb-4">
        In 2022, there were nearly 20 million new cancer cases and 9.7 million deaths worldwide.<br>
        Early detection of cancer can be cured at a faster rate than the later stages. Early cancer detection is crucial because it significantly increases the chances of successful treatment, improves survival rates, and enhances the overall quality of life for patients.<br>
        <span class="font-semibold text-blue-700">That's where OncoSense comes in.</span>
      </p>
      <p class="text-lg font-bold text-gray-800">
        OncoSense is a smart wearable solution – available as a patch or band – that continuously monitors cellular anomalies, providing early alerts to potential cancer developments. Our technology bridges cutting-edge biosensing with user-friendly digital reporting to help individuals detect abnormalities early.
      </p>
    </div>
  </section>

  <section class="py-12 bg-white">
    <div class="max-w-6xl mx-auto px-4 grid grid-cols-1 md:grid-cols-2 gap-8">
      <div class="border p-6 rounded shadow">
        <h2 class="text-xl font-bold mb-2">OncoSense™ Patch</h2>
        <p class="mb-4">₹2,999 - A smart patch that detects abnormal cellular activity.</p>
        <button onclick="handleAddToCart('OncoSense™ Patch', 2999)" class="primary-bg text-white px-4 py-2 rounded primary-hover">Add to Cart</button>
      </div>
      <div class="border p-6 rounded shadow">
        <h2 class="text-xl font-bold mb-2">OncoSense™ Band</h2>
        <p class="mb-4">₹5,999 - Wrist wearable with real-time alerts and analysis.</p>
        <button onclick="handleAddToCart('OncoSense™ Band', 5999)" class="primary-bg text-white px-4 py-2 rounded primary-hover">Add to Cart</button>
      </div>
    </div>
  </section>

  <section class="py-12 bg-gray-100">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-2xl font-bold mb-6">Find an Oncologist Near You</h2>
      <form onsubmit="handleDoctorSearch(event)" class="mb-4">
        <input type="text" id="doctorLocation" class="border p-2 w-2/3 rounded" placeholder="Enter your city or pincode" required>
        <button type="submit" class="primary-bg text-white px-4 py-2 rounded ml-2 primary-hover">Search</button>
      </form>
      <iframe id="mapFrame" class="w-full h-64 rounded border" src="https://www.google.com/maps?q=oncologist+near+india&output=embed"></iframe>
    </div>
  </section>

  <section class="py-12 bg-white">
    <div class="max-w-4xl mx-auto px-4">
      <h2 class="text-2xl font-bold text-center mb-6">Contact Us</h2>
      <form onsubmit="handleContactForm(event)" class="space-y-4">
        <input type="text" id="contactName" class="border p-2 w-full rounded" placeholder="Your Name" required>
        <input type="email" class="border p-2 w-full rounded" placeholder="Your Email" required>
        <textarea class="border p-2 w-full rounded" placeholder="Your Message" rows="4" required></textarea>
        <button type="submit" class="primary-bg text-white px-4 py-2 rounded primary-hover">Send Message</button>
      </form>
    </div>
  </section>

  <section class="py-12 bg-gray-50">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl font-bold text-center mb-6 primary-text">🛒 Your Cart</h2>
      <ul id="cartList" class="text-center text-lg space-y-2"></ul>
      <div id="cartSummary" class="text-center mt-4"></div>
      <div class="text-center mt-6">
        <p class="text-lg font-semibold mb-2">Pay via UPI</p>
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/71/UPI-Logo-vector.svg" alt="UPI" class="mx-auto w-32 mb-2">
        <p>Scan UPI QR or pay to: <strong>oncosense@upi</strong></p>
      </div>
    </div>
  </section>
</body>
</html>
