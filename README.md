<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>2 User Chat</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div id="usernameInput">
    <h2>Enter Username</h2>
    <input type="text" id="username" placeholder="Your name" />
    <input type="text" id="partner" placeholder="Partner's name" />
    <button onclick="startChat()">Start Chat</button>
  </div>

  <div id="chatRoom" style="display:none;">
    <div id="chatBox"></div>
    <input type="text" id="message" placeholder="Type a message..." />
    <button onclick="sendMessage()">Send</button>
  </div>

  <script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-app.js"></script>
  <script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-database.js"></script>
  <script src="firebase-config.js"></script>
  <script src="script.js"></script>
</body>
</html>
