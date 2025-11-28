<html>
<head>
    <meta charset="UTF-8">
    <title>thực hành </title>
        <style>
        .container {
             max-width:1100px;
             margin:28px auto;
             padding:16px;
             border: 15px;
        }
            .img {
                width:100%;
                height:100%;
                object-fit:cover;
                display:block
            }
            .editable {
                width: 100%;
                height: 200px;
                border: 3px solid black;
                padding: 8px;
                border-radius: 8px;
        }
    .topbar{
      background:#0d74b8;
      color:#fff;
      padding:12px 16px;
      border-radius:4px;
      display:flex;
      align-items:center;
      gap:12px;
    }
    .hamburger{
      width:26px;height:18px;display:inline-block;
    }
    .hamburger span{display:block;height:3px;background:#fff;margin:3px 0;border-radius:2px}
    .topbar h1{
      font-size:18px;
      letter-spacing:0.5px;
    }
    .layout{
      display:grid;
      grid-template-columns: 1fr 320px;
      gap:24px;
      margin-top:18px;
    }
            .layout1{
      display:grid;
      width:320px;
      grid-template-columns: 1fr 320px;
      gap:24px;
      margin-top:18px;
    }
    .main{
      background:#fff;
      padding:12px;
      border-radius:6px;
      box-shadow:0 1px 3px rgba(0,0,0,0.06);
    }
    .hero{
      width:100%;
      height:220px;
      overflow:hidden;
      border-radius:4px;
      background:#eee;
    }
    .hero img{width:100%;height:100%;object-fit:cover;display:block}
    .title{
      color:green;
      font-weight:700;
      font-size:20px;
      margin:14px 0 8px;
    }
    .meta{
      display:flex;
      gap:12px;
      align-items:center;
      color:#666;
      font-size:13px;
      margin-bottom:10px;
    }
    .meta .author{display:flex;align-items:center;gap:6px}
    .meta .author i{width:14px;height:14px;background: #f6a623;border-radius:50%;display:inline-block}
    .excerpt{color:#444;line-height:1.6;font-size:15px; font-weight: bold;}
        .sidebar{
      background:#fff;
      padding:10px;
      border-radius:6px;
      box-shadow:0 1px 3px rgba(0,0,0,0.06);
        border: 4px solid transparent;
      background: 
        linear-gradient(white, white) padding-box,
        linear-gradient(90deg, #ff7a18, #af002d, #319197) border-box;
    }
    .sidebar .item{
      display:flex;
      gap:10px;
      padding:10px 8px;
      border-bottom:1px solid #eee;
      align-items:flex-start;
      line-height: 1.5;
    }
    .sidebar .item:last-child{border-bottom:0}
    .checkbox{
      width:18px;height:18px;border:2px solid #3fa9f5;border-radius:3px;flex-shrink:0;background:#fff;display:inline-block;position:relative;
    }
    .sidebar .item:last-child{border-bottom:0}
    .checkbox{
      width:18px;height:18px;border:2px solid #3fa9f5;border-radius:3px;flex-shrink:0;background:#fff;display:inline-block;position:relative;
    }
    .checkbox:after{
      content:"";
      position:absolute;
      left:3px;top:1px;
      width:6px;height:10px;border-right:2px solid #0b72b1;border-bottom:2px solid #0b72b1;
      transform:rotate(45deg);
      opacity:1;
    }
    .item a{color:#0b72b1;font-size:14px;font-weight:600;border: 15px;}
    .item a:hover{text-decoration:underline}
    @media (max-width:880px){
      .layout{grid-template-columns:1fr;gap:12px}
      .hero{height:180px}
    .sidebar{order:2}
    }
    .task{
      margin-top:28px;
      font-size:20px;
      letter-spacing:0.5px;
      font-weight:600;
      color:#111;
      line-height:1.4;
    }
    </style>
</head>
<body>
    <div style="text-align: center;">
  <img src="https://c3easup.daklak.edu.vn/wp-content/uploads/banner-easup.png" width="1480" height="auto" style="text-align: center;">
    </div>
   <div class="container">
    <div class="topbar" role="banner">
      <div class="hamburger" aria-hidden="true">
        <span></span><span></span><span></span>
      </div>
      <h1>TIN TỨC - SỰ KIỆN</h1>
    </div>
<div class="container">
        </div>
            <div class="layout" role="main">
      <article class="main">
        <div class="hero">
          <img src="https://c3easup.daklak.edu.vn/wp-content/uploads/z7256103726607_79fe63e266c38bc191b57485784eaa3b.jpg" alt="hình sự kiện trường">
      </div>
        <h2 class="title">SINH HOẠT DƯỚI CỜ TUẦN 13 – TRƯỜNG THPT EA SÚP</h2>
        <div class="meta">
          <div class="author"><i></i><span>.....</span></div>
          <div>24/11/2025</div>
          <div>• Lượt xem: <strong>....</strong></div>
        </div>
        <p class="excerpt">
          Sáng ngày 24/11/2025, trong buổi sinh hoạt dưới cờ tuần 13, toàn thể cán bộ, giáo viên và học sinh trường THPT Ea Súp đã tham gia các hoạt động văn nghệ, tuyên dương và chia sẻ những thành tích nổi bật trong học tập và phong trào.
        </p>
</article>
    <aside class="sidebar" aria-label="tin liên quan">
        <div class="item"><span class="checkbox" aria-hidden="true"></span><a href="https://c3easup.daklak.edu.vn/sinh-hoat-duoi-co-tuan-13-truong-thpt-ea-sup.html">SINH HOẠT DƯỚI CỜ TUẦN 13 – TRƯỜNG THPT EA SÚP</a></div>
        <div class="item"><span class="checkbox"></span><a href="https://c3easup.daklak.edu.vn/doan-vien-thanh-nien-truong-thpt-ea-sup-tham-gia-ngay-chu-nhat-xanh-lan-thu-viii.html">ĐOÀN VIÊN THANH NIÊN TRƯỜNG THPT EA SÚP THAM GIA NGÀY CHỦ NHẬT XANH</a></div>
        <div class="item"><span class="checkbox"></span><a href="https://c3easup.daklak.edu.vn/tang-cuong-kiem-tra-co-so-vat-chat-trong-thoi-diem-mua-lon.html">TĂNG CƯỜNG KIỂM TRA CƠ SỞ VẬT CHẤT TRONG THỜI ĐIỂM MƯA LỚN</a></div>
                <div class="item"><span class="checkbox"></span><a href="https://c3easup.daklak.edu.vn/ke-hoach-ung-pho-voi-mua-lon-lu-ngap-lut-truong-thpt-ea-sup-nam-hoc-2025-2026.html">KẾ HOẠCH ỨNG PHÓ VỚI MƯA LỚN, LŨ NGẬP, LỤT NĂM HỌC 2025-2026</a></div>
        <div class="item"><span class="checkbox"></span><a href="https://c3easup.daklak.edu.vn/quyet-dinh-cong-khai-theo-thong-tu-092025tt-bgddt.html">QUYẾT ĐỊNH CÔNG KHAI THEO THÔNG TƯ 09/2025/TT-BGDĐT</a></div>
        <div class="item"><span class="checkbox"></span><a href="https://c3easup.daklak.edu.vn/ke-hoat-hoat-dong-tuan-tu-tuan-12.html">KẾ HOẠCH HOẠT ĐỘNG TUẦN NĂM HỌC 2025-2026</a></div>
        <div class="item"><span class="checkbox"></span><a href="https://c3easup.daklak.edu.vn/ke-hoach-trien-khai-nhiem-vu-phan-cong-thanh-vien-to-tu-van-hoc-duong-va-cong-tac-xa-hoi-nam-hoc-2025-2026.html">KẾ HOẠCH TRIỂN KHAI PHÂN CÔNG TƯ VẤN HỌC ĐƯỜNG VÀ CÔNG TÁC XÃ HỘI</a></div>

      </aside>
    </div>
    </div>
<footer style="text-align: center;">Thiết kế Website: <b>Phong – Khôi</b></footer>





