<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Siddesh Metal Industries - Requirement Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      padding: 20px;
    }
    .container {
      background: #fff;
      padding: 25px;
      max-width: 600px;
      margin: auto;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      margin-top: 0;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, select, button {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    button {
      margin-top: 20px;
      background-color: #28a745;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>Siddesh Metal Industries</h2>
    <p><strong>About Us:</strong> We supply high-quality metal products including MS (Mild Steel), SS (Stainless Steel), GI (Galvanized Iron), Aluminum, and Copper. We are committed to delivering precision-cut metal as per customer requirements.</p>
    <p><strong>Address:</strong> Plot No. 45, Industrial Area, Pune, Maharashtra, India</p>
    <p><strong>Email:</strong> siddeshjb4@gmail.com</p>

    <form action="https://formsubmit.co/siddeshjb4@gmail.com" method="POST">
      <!-- FormSubmit Settings -->
      <input type="hidden" name="_subject" value="New Metal Requirement from Customer">
      <input type="hidden" name="_template" value="table">
      <input type="hidden" name="_captcha" value="false">

      <!-- Customer Inputs -->
      <label for="size">Size (in cm):</label>
      <input type="text" id="size" name="Size" required>

      <label for="thickness">Thickness (in mm):</label>
      <input type="text" id="thickness" name="Thickness" required>

      <label for="metal">Metal Type:</label>
      <select id="metal" name="Metal Type" required>
        <option value="">--Select Metal--</option>
        <option value="MS">MS (Mild Steel)</option>
        <option value="SS">SS (Stainless Steel)</option>
        <option value="GI">GI (Galvanized Iron)</option>
        <option value="Aluminium">Aluminium</option>
        <option value="Copper">Copper</option>
      </select>

      <label for="contact">Contact Number:</label>
      <input type="text" id="contact" name="Contact Number" required>

      <button type="submit">Submit Requirement</button>
    </form>
  </div>

</body>
</html>
