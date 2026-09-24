<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gia Nông</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f7f5;
  color: #222;
}

header {
  background: #16823b;
  color: white;
  text-align: center;
  padding: 28px 15px;
}

header h1 {
  margin: 0;
  font-size: 34px;
}

header p {
  margin: 8px 0 0;
  font-size: 16px;
}

.container {
  max-width: 1100px;
  margin: auto;
  padding: 25px 15px;
}

.intro {
  background: white;
  border-radius: 15px;
  padding: 25px;
  text-align: center;
  margin-bottom: 25px;
}

.intro h2 {
  color: #16823b;
}

.groups {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
}

.group {
  background: white;
  border-radius: 15px;
  padding: 25px 15px;
  text-align: center;
  box-shadow: 0 3px 12px rgba(0,0,0,0.08);
}

.icon {
  font-size: 45px;
}

.group h3 {
  color: #16823b;
  font-size: 21px;
}

.group button {
  background: #16823b;
  color: white;
  border: 0;
  padding: 11px 22px;
  border-radius: 8px;
  cursor: pointer;
}

.contact {
  margin-top: 25px;
  background: #16823b;
  color: white;
  padding: 25px;
  border-radius: 15px;
  text-align: center;
}

.contact a {
  color: white;
  font-weight: bold;
}

footer {
  text-align: center;
  padding: 20px;
  color: #666;
}

@media (max-width: 700px) {
  .groups {
    grid-template-columns: 1fr;
  }
}
</style>
</head>

<body>

<header>
  <h1>GIA NÔNG</h1>
  <p>Đồng hành cùng nhà nông</p>
</header>

<div class="container">

  <section class="intro">
    <h2>Chào mừng đến với Gia Nông</h2>
    <p>
      Gia Nông cung cấp các sản phẩm và giải pháp
      phục vụ chăm sóc, bảo vệ cây trồng.
    </p>
  </section>

  <h2 style="text-align:center;">NHÓM SẢN PHẨM</h2>

  <section class="groups">

    <div class="group">
      <div class="icon">🦠</div>
      <h3>THUỐC BỆNH</h3>
      <p>
        Sản phẩm hỗ trợ phòng và xử lý các bệnh
        thường gặp trên cây trồng.
      </p>
      <button>Xem sản phẩm</button>
    </div>

    <div class="group">
      <div class="icon">🐛</div>
      <h3>THUỐC SÂU</h3>
      <p>
        Sản phẩm hỗ trợ quản lý và phòng trừ
        sâu, côn trùng gây hại.
      </p>
      <button>Xem sản phẩm</button>
    </div>

    <div class="group">
      <div class="icon">🌿</div>
      <h3>PHÂN BÓN</h3>
      <p>
        Các sản phẩm phân bón phục vụ nhu cầu
        dinh dưỡng của cây trồng.
      </p>
      <button>Xem sản phẩm</button>
    </div>

  </section>

  <section class="contact">
    <h2>LIÊN HỆ GIA NÔNG</h2>
    <p>Cần tư vấn sản phẩm? Hãy liên hệ với Gia Nông.</p>
    <p>
      📧 Email:
      <a href="mailto:xnkbvtvgianong@gmail.com">
        xnkbvtvgianong@gmail.com
      </a>
    </p>
  </section>

</div>

<footer>
  © 2026 Gia Nông – Đồng hành cùng nhà nông
</footer>

</body>
</html>
