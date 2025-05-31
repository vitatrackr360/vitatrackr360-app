# vitatrackr360-app
a modern app to track meal, groceries, and work out.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VitaTrackr360 – All-in-One Health Tracker</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    header p {
      font-size: 1rem;
      margin-top: 0.5rem;
    }
    .container {
      max-width: 600px;
      margin: 2rem auto;
      padding: 1rem;
      text-align: center;
    }
    .features {
      margin: 2rem 0;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    .feature {
      background-color: white;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    form {
      margin-top: 2rem;
    }
    input[type="email"] {
      padding: 0.75rem;
      width: 70%;
      max-width: 300px;
      border: 1px solid #ccc;
      border-radius: 4px;
      margin-bottom: 1rem;
    }
    button {
      padding: 0.75rem 1.5rem;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1rem;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: #777;
    }
    @media (min-width: 600px) {
      .features {
        flex-direction: row;
        justify-content: space-between;
      }
      .feature {
        flex: 1;
        margin: 0 0.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>VitaTrackr360</h1>
    <p>Track your meals, groceries, and workouts – all in one app.</p>
  </header>

  <div class="container">
    <div class="features">
      <div class="feature">
        <h3>🍽 Meal Tracker</h3>
        <p>Log meals, view nutrition, and stay on top of your health goals.</p>
      </div>
      <div class="feature">
        <h3>🛒 Grocery List</h3>
        <p>Plan smarter shopping based on your meals and pantry stock.</p>
      </div>
      <div class="feature">
        <h3>💪 Workout Log</h3>
        <p>Track sets, reps, and progress for every workout session.</p>
      </div>
    </div>

    <form name="waitlist" method="POST" data-netlify="true">
      <input type="hidden" name="form-name" value="waitlist" />
      <h2>Join Our Waitlist</h2>
      <input type="email" name="email" placeholder="Enter your email" required />
      <br />
      <button type="submit">Notify Me</button>
    </form>
  </div>

  <footer>
    &copy; 2025 VitaTrackr360. All rights reserved.
  </footer>
</body>
</html>
