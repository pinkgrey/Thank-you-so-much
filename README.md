<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Thank You</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@700&display=swap" rel="stylesheet">
<style>
body {
  margin: 0;
  height: 100vh;
  display: flex;
  flex-direction: column; /* смайлик сверху, текст снизу */
  justify-content: center; /* по вертикали */
  align-items: center;     /* по горизонтали */
  background: #ffffff;
  font-family: 'Inter', sans-serif;
}

h1 {
  font-size: 96px;
  font-weight: 700;
  text-align: center;
  background: linear-gradient(90deg, #4285F4, #34A853, #FBBC05, #EA4335); /* градиент Google */
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-shadow: 2px 2px 0 rgba(0,0,0,0.2),
               4px 4px 0 rgba(0,0,0,0.15),
               6px 6px 0 rgba(0,0,0,0.1);
  margin: 20px 0 0 0;
}

.smile {
  width: 150px;
  height: 150px;
}
</style>
</head>
<body>

<!-- Встроенный SVG смайлик -->
<svg class="smile" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
  <circle cx="32" cy="32" r="30" fill="#FFEB3B" stroke="#FBC02D" stroke-width="2"/>
  <circle cx="22" cy="24" r="5" fill="#000"/>
  <circle cx="42" cy="24" r="5" fill="#000"/>
  <path d="M20 40 C28 50, 36 50, 44 40" stroke="#000" stroke-width="3" fill="transparent" stroke-linecap="round"/>
</svg>

<h1>Thank You</h1>

</body>
</html>
