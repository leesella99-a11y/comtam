<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Vietnamese Culinary Art - Com Tam</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">

<style>
body{
margin:0;
background:#f5f5f5;
font-family:'Montserrat', sans-serif;
color:#222;
}

/* HEADER */
.header{
background:url("https://i-giadinh.vnecdn.net/2024/03/07/7-Hoan-thien-thanh-pham-1-6244-1709800134.jpg") no-repeat center;
background-size:cover;
height:500px;
position:relative;
}
.header::after{
content:"";
position:absolute;
width:100%;
height:100%;
background:rgba(0,0,0,0.6);
}
.header-content{
position:absolute;
top:50%;
left:50%;
transform:translate(-50%,-50%);
text-align:center;
z-index:2;
color:white;
}
.header-content h1{
font-family:'Playfair Display', serif;
font-size:60px;
letter-spacing:4px;
color:#d4af37;
}
.header-content p{
font-style:italic;
letter-spacing:2px;
}

/* SECTION */
.section{
padding:80px 12%;
background:white;
}
.section.dark{
background:#111;
color:white;
}
.section h2{
font-family:'Playfair Display', serif;
font-size:34px;
margin-bottom:25px;
color:#bfa046;
}
.section.dark h2{
color:#d4af37;
}
.section p{
line-height:1.8;
font-size:17px;
}

/* Ảnh chính */
.main-img{
width:100%;
border-radius:15px;
margin-top:40px;
transition:0.4s;
}
.main-img:hover{
transform:scale(1.03);
}

/* GRID NGUYÊN LIỆU */
.grid{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:30px;
margin-top:50px;
}
.card{
background:#1c1c1c;
padding:20px;
text-align:center;
border-radius:15px;
color:white;
transition:0.4s;
}
.card:hover{
transform:translateY(-10px);
box-shadow:0 15px 35px rgba(0,0,0,0.6);
}
.card img{
width:100%;
border-radius:12px;
height:180px;
object-fit:cover;
transition:0.4s;
}
.card:hover img{
transform:scale(1.05);
}
.card p{
margin-top:15px;
font-weight:600;
color:#d4af37;
letter-spacing:1px;
}

/* Hình trang trí mờ */
.decor{
background:url("https://cdn11.dienmaycholon.vn/filewebdmclnew/DMCL21/Picture/News/News_expe_15324/15324.png?version=151846") no-repeat center;
background-size:cover;
height:280px;
opacity:0.12;
}

/* FOOTER */
footer{
background:#111;
color:#d4af37;
text-align:center;
padding:40px;
font-size:14px;
letter-spacing:2px;
}
</style>
</head>

<body>

<div class="header">
<div class="header-content">
<h1>COM TAM</h1>
<p>The Soul of Southern Vietnamese Cuisine</p>
</div>
</div>

<div class="section">
<h2>Giá trị văn hoá & bản sắc miền Nam</h2>
<p>
Cơm tấm là biểu tượng đặc trưng của ẩm thực miền Nam Việt Nam,
đặc biệt phổ biến tại Thành phố Hồ Chí Minh.
Từ những hạt gạo tấm giản dị,
món ăn đã phát triển thành một biểu tượng văn hóa đường phố đầy sức sống.
Sự kết hợp giữa cơm trắng mềm,
sườn nướng thơm lừng và nước mắm pha tinh tế
tạo nên một tổng thể hài hòa giữa vị ngọt, mặn và béo.
</p>

<img class="main-img"
src="https://i-giadinh.vnecdn.net/2024/03/07/7-Hoan-thien-thanh-pham-1-6244-1709800134.jpg">
</div>

<div class="section dark">
<h2>Nguyên liệu tinh chọn</h2>

<div class="grid">

<div class="card">
<img src="https://cdn.tgdd.vn/Files/2020/02/28/1239092/gao-tam-la-gao-gi-loi-ich-cua-gao-tam-trong-cuoc-song-202211191612574731.jpg">
<p>Gạo tấm truyền thống</p>
</div>

<div class="card">
<img src="https://beptruong.edu.vn/wp-content/uploads/2013/01/suon-nuong-muoi-ot.jpg">
<p>Sườn nướng than hoa</p>
</div>

<div class="card">
<img src="https://s1.media.ngoisao.vn/news/2024/11/13/trung-op-gndg-ngoisaovn-w1200-h720.jpg">
<p>Trứng ốp la béo nhẹ</p>
</div>

<div class="card">
<img src="https://haiphu.vn/web/image/3165-e38187fb/1-cach-lam-nuoc-mam-ngon.png">
<p>Nước mắm pha chua ngọt</p>
</div>

</div>
</div>

<div class="section">
<h2>Nghệ thuật chế biến</h2>
<p>
Sườn heo được ướp cùng nước mắm, tỏi và đường
trong nhiều giờ để thấm vị trước khi nướng trên than hồng.
Quá trình nướng tạo nên lớp caramel vàng óng đặc trưng.
Gạo tấm được nấu vừa chín tới để giữ độ mềm mà không khô.
Nước mắm pha đóng vai trò quan trọng,
giúp cân bằng tổng thể hương vị của món ăn.
</p>
</div>

<div class="section dark">
<h2>Đánh giá phong vị</h2>
<p>
Cơm tấm gây ấn tượng bởi sự phong phú trong kết cấu:
mềm của cơm, đậm đà của sườn,
vị béo nhẹ của trứng và độ thanh của đồ chua.
Tổng thể món ăn mang lại cảm giác gần gũi,
nhưng vẫn đủ tinh tế để chinh phục thực khách quốc tế.
</p>
</div>

<div class="decor"></div>

<footer>
Vietnamese Culinary Art © 2026
</footer>

</body>
</html>
