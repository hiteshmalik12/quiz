<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Know You Better Quiz</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #fbc2eb, #a6c1ee);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .quiz-box {
      background: #fff;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      max-width: 400px;
      width: 90%;
      text-align: center;
    }

    h2 {
      color: #6a1b9a;
      margin-bottom: 20px;
    }

    label {
      display: block;
      text-align: left;
      margin: 10px 0 5px;
      font-weight: bold;
      color: #333;
    }

    select, input[type="text"], textarea {
      width: 100%;
      padding: 10px;
      border-radius: 10px;
      border: 1px solid #ccc;
      margin-bottom: 15px;
      font-size: 1em;
    }

    .btn {
      padding: 10px 25px;
      background: #8e24aa;
      color: white;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      font-size: 1em;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background: #6a1b9a;
    }
  </style>
</head>
<body>
  <form class="quiz-box" action="https://formsubmit.co/puneetkhanna1921@gmail.com" method="POST">
    <h2>Know You Better 😇</h2>

    <label for="name">Your Name</label>
    <input type="text" name="Name" id="name" required />

    <label for="color">Favorite Color?</label>
    <select name="Favorite Color" id="color">
      <option>Pink</option>
      <option>Blue</option>
      <option>Black</option>
      <option>Green</option>
    </select>

    <label for="vacay">Ideal Vacation Spot?</label>
    <select name="Vacation Spot" id="vacay">
      <option>Mountains</option>
      <option>Beach</option>
      <option>City</option>
      <option>Countryside</option>
    </select>

    <label for="food">Comfort Food</label>
    <input type="text" name="Comfort Food" id="food" placeholder="Pizza? Chocolate? Momos?" />

    <label for="movie">All-time Favorite Movie or Series?</label>
    <input type="text" name="Favorite Movie or Series" id="movie" />

    <label for="dream">What's your dream in one line?</label>
    <textarea name="Dream" rows="2" placeholder="Be real ✨"></textarea>

    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_subject" value="New Quiz Response!">
    <input type="hidden" name="_template" value="table">

    <button type="submit" class="btn">Submit</button>
  </form>
</body>
</html>
