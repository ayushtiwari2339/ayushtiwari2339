<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
  body {
    font-family: 'Boogaloo Regular', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-align: center;
    background-image: url('background.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
    color: #fff; /* Lighter text */
  }
  .letter-icon {
    font-size: 120px; /* Larger icon size */
    animation: pulse 1.5s ease-in-out infinite;
    cursor: pointer;
    position: relative;
  }
  .letter-icon::after {
    content: "Click Me 👉👈🎀";
    font-size: 18px; /* Larger font size */
    color: #000; /* Black color */
    font-weight: bold; /* Bold text */
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%); /* Center align */
  }
  #hidden-message {
    display: none;
    margin-top: 30px;
    animation: slideIn 1s forwards;
    text-align: left;
    padding: 20px;
  }
  .photo-frame {
    display: inline-block;
    margin: 10px;
    padding: 5px;
    background-color: rgba(255, 255, 255, 0.7);
    animation: slideInPhotos 1.5s forwards;
  }
  .heart-frame {
    border: 5px solid red;
    border-radius: 50%;
  }
  
  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.1); }
    100% { transform: scale(1); }
  }
  
  @keyframes slideIn {
    from { opacity: 0; transform: translateY(-50px); }
    to { opacity: 1; transform: translateY(0); }
  }
  
  @keyframes slideInPhotos {
    from { opacity: 0; transform: translateY(50px); }
    to { opacity: 1; transform: translateY(0); }
  }
</style>
</head>
<body>
  <div style="margin-bottom: 30px;">
    <div class="letter-icon" onclick="showMessage()">💌</div> 
  </div>
  <div id="hidden-message">
    <h2 style="margin-bottom: 20px;">Happy Birthday!</h2>
    <p style="font-size: 16px; margin-bottom: 20px; font-weight: bold;">
      Dear Vandana,
    </p>
    <p style="font-size: 16px; margin-bottom: 20px; font-weight: bold; text-decoration: underline;">
      Happie Bday, bbg! 🎉🎂 You're getting hotter with each candle you blow! Wish I could be there with you. Love you to the moon and back! 
    </p>
    <div style="display: flex; align-items: center; justify-content: center; margin-bottom: 20px;">
      <div style="margin-right: 20px;">
        <img src="photo1.jpg" alt="Photo 1" width="100" class="photo-frame">
      </div>
      <div style="margin-right: 20px;">
        <img src="photo2.jpg" alt="Photo 2" width="100" class="photo-frame">
      </div>
    </div>
    <p style="font-size: 18px; margin-bottom: 10px; font-weight: bold; text-decoration: underline;">With all my love - Ayush<3🎀</p>
  </div>

<script>
  function showMessage() {
    var hiddenMessage = document.getElementById("hidden-message");
    hiddenMessage.style.display = "block";
    document.querySelector(".letter-icon").style.display = "none";
  }
</script>
</body>
</html>![photo1](https://github.com/ayushtiwari2339/ayushtiwari2339/assets/85986263/34b1ff41-f67a-4001-98d8-3d78d40c5c14)
![background](https://github.com/ayushtiwari2339/ayushtiwari2339/assets/85986263/d5ebb4bb-79f1-46b5-9a7d-a14675cd9662)
![photo2](https://github.com/ayushtiwari2339/ayushtiwari2339/assets/85986263/36a1c4b1-45e1-4742-bdd3-b88e88db685d)
