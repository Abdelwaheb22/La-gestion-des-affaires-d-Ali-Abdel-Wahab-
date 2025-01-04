# La-gestion-des-affaires-d-Ali-Abdel-Wahab-
Site de gestion d'entreprise 
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>إدارة أعمال علي عبد الوهاب</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>مرحبًا بك في إدارة الأعمال</h1>
    <nav>
      <ul>
        <li><a href="#services">الخدمات</a></li>
        <li><a href="#contact">اتصل بنا</a></li>
      </ul>
    </nav>
  </header>
  <section id="services">
    <h2>الخدمات</h2>
    <p>نقدم خدمات استشارية متكاملة.</p>
  </section>
  <footer>
    <p>© 2025 علي عبد الوهاب - جميع الحقوق محفوظة</p>
  </footer>
  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
header {
  background-color: #333;
  color: white;
  padding: 10px 20px;
}
nav ul {
  list-style: none;
  display: flex;
  justify-content: space-around;
  padding: 0;
}
nav a {
  color: white;
  text-decoration: none;
}
section {
  padding: 20px;
}
footer {
  text-align: center;
  background-color: #333;
  color: white;
  padding: 10px;
}
document.addEventListener("DOMContentLoaded", () => {
  console.log("الموقع جاهز للاستخدام!");
});
