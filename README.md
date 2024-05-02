<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Web AI App</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div id = "loader" class="overlay">
      <span class="loader"></span>
    </div>
    <div class="container">
      <div class="left-box">
        <!-- Logo Container -->
        <div class="logo">
          <img
            src="AI.gif"
          />
          <p style="margin-top: 20px">AI WebApp</p>
        </div>

        <!-- Title Container -->
        <div>
          <h3>AI-Powered Fun with Web App</h3>
          <p style="margin-top: -10px; font-size: 14px; color: gray">
            Let's Play Together
          </p>
        </div>

        <!-- File Select Container -->
        <div class="mydrop-zone">
          <input id="file" type="file" hidden />
          <label for="file">Choose Your Image</label>
        </div>

        <!-- Service Container -->
        <div class="service-container">
          <div class="ai-service-item">
            <input class="ai-service-item-input" value="ObjectDetection" id="object-detection" name="service" type="radio" />
            <label for="object-detection">Object Detection</label>
          </div>

          <div class="ai-service-item">
            <input class="ai-service-item-input" value="FaceDetection" id="face-detection" name="service" type="radio" />
            <label for="face-detection">Face Detection</label>
          </div>

          <div class="ai-service-item">
            <input class="ai-service-item-input" value="CelebrityDetection" id="celebrity-detection" name="service" type="radio" />
            <label for="celebrity-detection">Celebrity Detection</label>
          </div>
        </div>
        <div id = "magic-btn" class="magic-btn">See The Magic</div>
      </div>
      <div class="right-box">
        <img id = "right-img" class="right-img" src="th.jpeg" />
      </div>
    </div>

    <div id="myModal" class="modal">

      <!-- Modal content -->
      <div class="modal-content">
        <img id = "result-image" />
      </div>
    
    </div>

    <script src="./script.js"></script>
  </body>
</html>

