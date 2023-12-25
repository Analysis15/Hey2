<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link rel="stylesheet" href="styles.css">

  <title>Cute Animation</title>

</head>

<body>

  <div class="container">

    <div class="animation-figure"></div>

    <p class="question">Do you want to go out with me?</p>

    <button id="yesButton" onclick="alert('Yay! Let's go!')">Yes</button>

    <button id="noButton" onclick="changeButtonText()">No</button>

  </div>



  <script src="script.js"></script>

</body>

</html>intro
function changeButtonText() {

  const noButton = document.getElementById('noButton');

  noButton.innerHTML = 'Yes';

  noButton.onclick = function() {

    alert("Yay! Let's go!");

  };

}
body {
  margin: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: #f8f8f8;
}

.container {
  text-align: center;
}

.animation-figure {
  width: 100px;
  height: 100px;
  background-color: pink; /* or your desired color */
  border-radius: 50%;
  margin: 20px auto;
  /* Add your animation styles here */
}

.question {
  font-size: 18px;
  margin-bottom: 20px;
}

button {
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
}
