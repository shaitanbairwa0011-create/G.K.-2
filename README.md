<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>मेरी पहली वेबसाइट</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #74ebd5, #9face6);
      text-align: center;
      color: #222;
    }
    header {
      background: #333;
      color: white;
      padding: 15px;
    }
    header h1 {
      margin: 0;
    }
    nav {
      margin: 10px 0;
    }
    nav a {
      text-decoration: none;
      color: white;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      color: yellow;
    }
    section {
      padding: 30px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      background: darkblue;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
    button:hover {
      background: navy;
    }
    footer {
      background: #333;
      color: white;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>🌐 मेरी पहली वेबसाइट</h1>
    <nav>
      <a href="#home">होम</a>
      <a href="#about">मेरे बारे में</a>
      <a href="#contact">संपर्क</a>
    </nav>
  </header>

  <section id="home">
    <h2>स्वागत है 🙏</h2>
    <p>यह मेरी पहली वेबसाइट है जो GitHub Pages पर Live होगी।</p>
    <button onclick="sayHello()">मुझ पर क्लिक करें</button>
  </section>

  <section id="about">
    <h2>मेरे बारे में</h2>
    <p>मैं वेब डेवलपमेंट सीख रहा हूँ। यह मेरा पहला प्रोजेक्ट है।</p>
  </section>

  <section id="contact">
    <h2>संपर्क करें</h2>
    <p>Email: demo@example.com</p>
  </section>

  <footer>
    <p>© 2025 मेरी वेबसाइट | सभी अधिकार सुरक्षित</p>
  </footer>

  <script>
    function sayHello() {
      alert("नमस्ते! आपने बटन दबाया ✅");
    }
  </script>

</body>
</html>
