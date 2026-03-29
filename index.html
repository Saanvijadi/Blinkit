<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blinkit Recruitment Form</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    .container {
      background: #fff;
      padding: 20px;
      max-width: 400px;
      margin: 30px auto;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
      text-align: center;
    }

    .logo {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
    }

    h2 {
      margin-bottom: 15px;
    }

    input, select {
      width: 100%;
      padding: 12px;
      margin: 8px 0;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 14px;
      box-sizing: border-box;
    }

    .checkbox-container {
      display: flex;
      align-items: flex-start;
      text-align: left;
      margin-top: 10px;
      font-size: 13px;
    }

    .checkbox-container input {
      margin-right: 8px;
      margin-top: 3px;
    }

    button {
      background: green;
      color: white;
      padding: 12px;
      border: none;
      width: 100%;
      margin-top: 15px;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }

    .greeting {
      display: none;
      margin-top: 20px;
      font-size: 16px;
      color: green;
      font-weight: bold;
    }

    @media (max-width: 480px) {
      .container {
        margin: 15px;
        padding: 15px;
      }
    }
  </style>
</head>

<body>

<div class="container">

  <!-- LOGO -->
  <img src="https://via.placeholder.com/100" class="logo" alt="Logo">

  <h2>Blinkit Hiring Form</h2>

  <form id="leadForm">

    <input type="text" name="name" placeholder="Full Name of Candidate" required>

    <input type="tel" name="phone" placeholder="Mobile Number" required>

    <input type="email" name="email" placeholder="Email Address" required>

    <input type="number" name="age" placeholder="Age Of Candidate" required>

    <input type="text" name="qualification" placeholder="Highest Qualification" required>

    <select name="location" required>
      <option value="">Select Location</option>
      <option>Hyderabad</option>
      <option>Andhra Pradesh</option>
    </select>

    <select name="role" required>
      <option value="">Select Role</option>
      <option>Picker</option>
      <option>Packer</option>
    </select>

    <!-- CHECKBOX -->
    <div class="checkbox-container">
      <input type="checkbox" id="consent" required>
      <label for="consent">
        I agree to share my details with the Blinkit recruitment processing team.
      </label>
    </div>

    <button type="submit">Apply Now</button>

  </form>

  <div class="greeting" id="greetingMessage"></div>

</div>

<script>
const scriptURL = "https://script.google.com/macros/s/AKfycbxD4RSei59IX2IFIeb8k1bXjUGvK1AL2iqZT_YEBp6phM46L5UbWdo--eScg5MVu2gkag/exec";

document.getElementById("leadForm").addEventListener("submit", function(e) {
  e.preventDefault();

  const formData = {
    name: this.name.value,
    phone: this.phone.value,
    email: this.email.value,
    age: this.age.value,
    qualification: this.qualification.value,
    location: this.location.value,
    role: this.role.value
  };

  // Send to Google Sheets
  fetch(scriptURL, {
    method: "POST",
    body: JSON.stringify(formData)
  })
  .then(() => {

    // WhatsApp Message
    let message = `Hi, I am ${formData.name}.
I am interested in Blinkit job.

Phone: ${formData.phone}
Email: ${formData.email}
Age: ${formData.age}
Qualification: ${formData.qualification}
Location: ${formData.location}
Role: ${formData.role}`;

    let whatsappURL = `https://wa.me/918106404858?text=${encodeURIComponent(message)}`;

    // Open WhatsApp in new tab/window
    window.open(whatsappURL, "_blank");

    // Show greeting to candidate
    const greeting = document.getElementById("greetingMessage");
    greeting.innerText = `Thank you, ${formData.name}! Your application has been submitted successfully. You can apply again if needed.`;
    greeting.style.display = "block";

    // Reset the form for next submission
    this.reset();

  })
  .catch(() => alert("Error submitting form"));
});
</script>

</body>
</html>
