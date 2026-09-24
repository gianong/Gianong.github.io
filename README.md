<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gia Nông - Vật tư nông nghiệp</title>

<style>
*{box-sizing:border-box}
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:#f5f7f3;
  color:#222;
}
header{
  background:#16833b;
  color:white;
  text-align:center;
  padding:22px 15px;
}
header h1{
  margin:0;
  font-size:34px;
}
header p{
  margin:8px 0 0;
  font-size:16px;
}
.hero{
  margin:15px;
  height:230px;
  border-radius:15px;
  background:linear-gradient(135deg,#1d963f,#79c957);
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:white;
}
.hero h2{
  font-size:30px;
  margin:0 0 8px;
}
.hero p{
  margin:0;
}
.container{
  max-width:1000px;
  margin:auto;
  padding:10px 15px 30px;
}
h2.title{
  text-align:center;
  color:#16833b;
  margin:25px 0 15px;
}
.categories{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:12px;
}
.category{
  background:white;
  padding:22px 10px;
  text-align:center;
  border-radius:12px;
  box-shadow:0 2px 8px #0001;
  font-weight:bold;
  font-size:17px;
}
.products{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:15px;
}
.product{
  background:white;
  border-radius:12px;
  padding:18px;
  box-shadow:0 2px 8px #0001;
}
.product h3{
  color:#16833b;
  margin-top:0;
}
.product p{
  line-height:1.5;
}
.contact{
  background:white;
  margin-top:25px;
  padding:22px;
  border-radius:15px;
  box-shadow:0 2px 8px #0001;
}
.contact p{
  font-size:17px;
  margin:12px 0;
}
footer{
  background:#126b31;
  color:white;
  text-align:center;
  padding:18px;
  margin-top:25px;
}

@media(max-width:700px){
  .categories,.products{
    grid-template-columns:1fr;
  }
  header h1{
    font-size:28px;
  }
  .hero{
    height:200px;
  }
}
</style>
</head>

<body>

<header>
  <h1>🌿 GIA NÔNG</h1>
  <p>Giải pháp đồng hành cùng nhà nông</p>
</header>

<section class="hero">
  <div>
    <h2>GIA NÔNG</h2>
    <p>Thuốc bảo vệ thực vật & Phân bón</p>
  </div>
</section>

<div class="container">

<h2 class="title">DANH MỤC SẢN PHẨM</h2>

<div class="categories">
  <div class="category">🦠<br>THUỐC BỆNH</div>
  <div class="category">🐛<br>THUỐC SÂU</div>
  <div class="category">🌾<br>PHÂN BÓN</div>
</div>

<h2 class="title">THÔNG TIN SẢN PHẨM</h2>

<div class="products">

  <div class="product">
    <h3>Thuốc bệnh</h3>
    <p>Thông tin sản phẩm, công dụng và hướng dẫn sử dụng.</p>
    <b>Liên hệ để biết giá</b>
  </div>

  <div class="product">
    <h3>Thuốc sâu</h3>
    <p>Thông tin sản phẩm, công dụng và hướng dẫn sử dụng.</p>
    <b>Liên hệ để biết giá</b>
  </div>

  <div class="product">
    <h3>Phân bón</h3>
    <p>Thông tin sản phẩm, thành phần và hướng dẫn sử dụng.</p>
    <b>Liên hệ để biết giá</b>
  </div>

</div>

<div class="contact">
  <h2 class="title">LIÊN HỆ GIA NÔNG</h2>

  <p>📞 <b>Điện thoại:</b> 0889 008 009</p>
  <p>📍 <b>Địa chỉ:</b> 163 Lạc Long Quân, Đức Trọng, Lâm Đồng</p>
  <p>📧 <b>Email:</b> xnkbvtvgianong@gmail.com</p>
</div>

</div>

<footer>
  © 2026 GIA NÔNG - Đồng hành cùng nhà nông
</footer>

</body>
</html>
