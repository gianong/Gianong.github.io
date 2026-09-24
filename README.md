
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Công ty TNHH Xuất Nhập Khẩu Gia Nông</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, sans-serif;
    background:#f7faf7;
    color:#222;
    line-height:1.6;
}

header{
    background:#ffffff;
    padding:18px 6%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    box-shadow:0 2px 10px rgba(0,0,0,.08);
    position:sticky;
    top:0;
    z-index:100;
}

.logo{
    color:#16833c;
    font-size:22px;
    font-weight:bold;
}

.logo span{
    display:block;
    color:#777;
    font-size:12px;
    font-weight:normal;
}

nav a{
    color:#333;
    text-decoration:none;
    margin-left:25px;
    font-weight:bold;
}

nav a:hover{
    color:#16833c;
}

/* BANNER */

.hero{
    min-height:520px;
    background:
    linear-gradient(rgba(0,70,25,.45),rgba(0,70,25,.45)),
    url("https://images.unsplash.com/photo-1500937386664-56d1dfef3854?auto=format&fit=crop&w=1800&q=85")
    center/cover;
    
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
    padding:30px;
}

.hero-content{
    max-width:850px;
}

.hero h1{
    font-size:48px;
    margin-bottom:15px;
    text-transform:uppercase;
}

.hero p{
    font-size:22px;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    background:#f4b400;
    color:#fff;
    padding:14px 28px;
    border-radius:30px;
    text-decoration:none;
    font-weight:bold;
    margin:5px;
}

.btn.green{
    background:#16833c;
}

/* SECTIONS */

section{
    padding:70px 6%;
}

.section-title{
    text-align:center;
    color:#16833c;
    font-size:32px;
    margin-bottom:15px;
}

.section-subtitle{
    text-align:center;
    color:#666;
    max-width:700px;
    margin:0 auto 40px;
}

/* ABOUT */

.about{
    background:white;
}

.about-box{
    max-width:1000px;
    margin:auto;
    text-align:center;
}

.about-box p{
    font-size:18px;
    color:#555;
}

/* VALUES */

.values{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:20px;
    max-width:1100px;
    margin:auto;
}

.value{
    background:white;
    padding:30px 20px;
    text-align:center;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.value .icon{
    font-size:42px;
    margin-bottom:15px;
}

.value h3{
    color:#16833c;
    margin-bottom:8px;
}

/* IMAGE */

.gallery{
    background:#f1f6f1;
}

.gallery-box{
    max-width:1100px;
    margin:auto;
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.gallery-item{
    height:230px;
    border-radius:15px;
    overflow:hidden;
    background:#ddd;
}

.gallery-item img{
    width:100%;
    height:100%;
    object-fit:cover;
    transition:.3s;
}

.gallery-item img:hover{
    transform:scale(1.05);
}

/* CONTACT */

.contact{
    background:white;
}

.contact-box{
    max-width:900px;
    margin:auto;
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.contact-item{
    background:#f5f8f5;
    padding:25px;
    text-align:center;
    border-radius:15px;
}

.contact-item .icon{
    font-size:35px;
}

.contact-item h3{
    color:#16833c;
    margin:10px 0;
}

.contact-item a{
    color:#16833c;
    text-decoration:none;
    font-weight:bold;
}

/* FOOTER */

footer{
    background:#075b2a;
    color:white;
    text-align:center;
    padding:35px 20px;
}

footer h2{
    margin-bottom:10px;
}

footer p{
    margin:5px;
}

/* MOBILE */

@media(max-width:800px){

    header{
        flex-direction:column;
        gap:12px;
    }

    nav a{
        margin:0 7px;
        font-size:14px;
    }

    .hero{
        min-height:450px;
    }

    .hero h1{
        font-size:32px;
    }

    .hero p{
        font-size:18px;
    }

    .values{
        grid-template-columns:repeat(2,1fr);
    }

    .gallery-box{
        grid-template-columns:1fr;
    }

    .contact-box{
        grid-template-columns:1fr;
    }
}

@media(max-width:500px){

    .values{
        grid-template-columns:1fr;
    }

    section{
        padding:50px 20px;
    }

    .hero h1{
        font-size:28px;
    }
}
</style>
</head>

<body>

<!-- HEADER -->

<header>

    <div class="logo">
        GIA NÔNG
        <span>Xuất Nhập Khẩu</span>
    </div>

    <nav>
        <a href="#home">Trang chủ</a>
        <a href="#about">Giới thiệu</a>
        <a href="#gallery">Hình ảnh</a>
        <a href="#contact">Liên hệ</a>
    </nav>

</header>


<!-- HERO -->

<section class="hero" id="home">

    <div class="hero-content">

        <h1>GIA NÔNG</h1>

        <p>
            CÔNG TY TNHH XUẤT NHẬP KHẨU GIA NÔNG
        </p>

        <p>
            Đồng hành cùng nông nghiệp Việt Nam
        </p>

        <a class="btn" href="tel:0889008009">
            📞 Gọi ngay
        </a>

        <a class="btn green" href="#contact">
            Liên hệ
        </a>

    </div>

</section>


<!-- ABOUT -->

<section class="about" id="about">

    <h2 class="section-title">
        VỀ GIA NÔNG
    </h2>

    <p class="section-subtitle">
        Đơn vị hoạt động trong lĩnh vực xuất nhập khẩu và
        đồng hành cùng người nông dân.
    </p>

    <div class="about-box">

        <p>
            <strong>CÔNG TY TNHH XUẤT NHẬP KHẨU GIA NÔNG</strong>
            hướng đến việc cung cấp những giải pháp phù hợp
            cho sản xuất nông nghiệp, lấy chất lượng và uy tín
            làm nền tảng phát triển lâu dài.
        </p>

    </div>

</section>


<!-- VALUES -->

<section>

    <h2 class="section-title">
        GIÁ TRỊ CỦA GIA NÔNG
    </h2>

    <p class="section-subtitle">
        Uy tín – Chất lượng – Tận tâm – Đồng hành
    </p>

    <div class="values">

        <div class="value">
            <div class="icon">🌱</div>
            <h3>Nông nghiệp</h3>
            <p>Đồng hành cùng sự phát triển của cây trồng.</p>
        </div>

        <div class="value">
            <div class="icon">⭐</div>
            <h3>Uy tín</h3>
            <p>Lấy uy tín làm nền tảng trong kinh doanh.</p>
        </div>

        <div class="value">
            <div class="icon">🤝</div>
            <h3>Tận tâm</h3>
            <p>Luôn lắng nghe và hỗ trợ khách hàng.</p>
        </div>

        <div class="value">
            <div class="icon">🚚</div>
            <h3>Đồng hành</h3>
            <p>Cùng khách hàng hướng tới hiệu quả lâu dài.</p>
        </div>

    </div>

</section>


<!-- GALLERY -->

<section class="gallery" id="gallery">

    <h2 class="section-title">
        HÌNH ẢNH
    </h2>

    <p class="section-subtitle">
        Hình ảnh hoạt động của Công ty Gia Nông
    </p>

    <div class="gallery-box">

        <div class="gallery-item">
            <img src="https://images.unsplash.com/photo-1499529112087-3cb3b73cec95?auto=format&fit=crop&w=900&q=80">
        </div>

        <div class="gallery-item">
            <img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399?auto=format&fit=crop&w=900&q=80">
        </div>

        <div class="gallery-item">
            <img src="https://images.unsplash.com/photo-1500076656116-558758c991c1?auto=format&fit=crop&w=900&q=80">
        </div>

    </div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

    <h2 class="section-title">
        LIÊN HỆ GIA NÔNG
    </h2>

    <p class="section-subtitle">
        Chúng tôi luôn sẵn sàng kết nối và hỗ trợ quý khách.
    </p>

    <div class="contact-box">

        <div class="contact-item">

            <div class="icon">📞</div>

            <h3>Điện thoại</h3>

            <a href="tel:0889008009">
                0889.008.009
            </a>

        </div>


        <div class="contact-item">

            <div class="icon">📍</div>

            <h3>Địa chỉ</h3>

            <p>
                163 Lạc Long Quân,<br>
                Đức Trọng, Lâm Đồng
            </p>

        </div>


        <div class="contact-item">

            <div class="icon">✉️</div>

            <h3>Email</h3>

            <a href="mailto:xnkbvtvgianong@gmail.com">
                xnkbvtvgianong@gmail.com
            </a>

        </div>

    </div>

</section>


<!-- FOOTER -->

<footer>

    <h2>GIA NÔNG</h2>

    <p>
        CÔNG TY TNHH XUẤT NHẬP KHẨU GIA NÔNG
    </p>

    <p>
        163 Lạc Long Quân, Đức Trọng, Lâm Đồng
    </p>

    <p>
        ☎ 0889.008.009
    </p>

    <p>
        © 2026 Gia Nông. All Rights Reserved.
    </p>

</footer>

</body>
</html>
