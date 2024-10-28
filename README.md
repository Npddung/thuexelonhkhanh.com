# thuexelonhkhanh.com
thuexelongkhanh
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thành Tâm - Dịch Vụ Cho Thuê Xe 4-7 Chỗ</title>
    <style>
        /* Reset mặc định */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Định dạng body và header */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(to right, #3a6186, #89253e);
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 2rem;
            margin-bottom: 5px;
        }
        header p {
            font-size: 1.1rem;
            font-style: italic;
        }

        /* Thiết kế phần hero */
        .hero {
            background: url('path-to-hero-image.jpg') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
            margin-top: 80px;
            position: relative;
            animation: fadeIn 2s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .hero h1 {
            font-size: 3rem;
            font-weight: bold;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.8);
        }

        /* Phần container và các mục */
        .container {
            width: 80%;
            max-width: 1200px;
            margin: 20px auto;
        }
        h2 {
            text-align: center;
            font-size: 2.2rem;
            color: #333;
            margin: 40px 0 20px;
            position: relative;
        }
        h2::after {
            content: '';
            width: 50px;
            height: 4px;
            background: #89253e;
            display: block;
            margin: 10px auto;
        }

        /* Phần dịch vụ */
        .services {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .service-item {
            background: #fff;
            padding: 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            width: calc(50% - 10px);
            transition: transform 0.3s ease;
            text-align: center;
        }
        .service-item:hover {
            transform: translateY(-10px);
        }
        .service-item h3 {
            color: #89253e;
            margin-bottom: 10px;
        }

        /* Phần liên hệ */
        .contact ul {
            list-style-type: none;
            padding: 0;
            font-size: 1.1rem;
        }
        .contact ul li {
            margin-bottom: 10px;
        }
        .contact ul li a {
            color: #333;
            text-decoration: none;
            transition: color 0.3s;
        }
        .contact ul li a:hover {
            color: #89253e;
        }

        /* Phần footer */
        .footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }

        /* Hiệu ứng cuộn mượt */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>

    <!-- Phần tiêu đề và slogan -->
    <header>
        <h1>Thành Tâm - Cho Thuê Xe Tự Lái 4-7 Chỗ</h1>
        <p>Phục vụ tận tâm</p>
    </header>

    <!-- Phần banner chính -->
    <section class="hero">
        <h1>Khám Phá Hành Trình Cùng Thành Tâm</h1>
    </section>

    <!-- Phần giới thiệu dịch vụ -->
    <section class="services container" id="services">
        <h2>Dịch Vụ Cho Thuê Xe</h2>
        <div class="service-item">
            <h3>Xe 4 Chỗ</h3>
            <p>Phù hợp cho gia đình nhỏ hoặc các chuyến đi công tác ngắn ngày. Xe 4 chỗ tiện nghi, tiết kiệm nhiên liệu và dễ di chuyển trong thành phố.</p>
        </div>
        <div class="service-item">
            <h3>Xe 7 Chỗ</h3>
            <p>Thích hợp cho các nhóm bạn hoặc gia đình lớn. Xe 7 chỗ rộng rãi, thoải mái cho hành trình dài và có không gian chứa đồ rộng rãi.</p>
        </div>
    </section>

    <!-- Phần liên hệ -->
    <section class="contact container" id="contact">
        <h2>Liên Hệ</h2>
        <p>Để biết thêm thông tin chi tiết về các gói thuê xe và đặt xe, vui lòng liên hệ chúng tôi:</p>
        <ul>
            <li>Email: <a href="mailto:info@thanhtamcar.com">info@thanhtamcar.com</a></li>
            <li>Điện thoại: <a href="tel:+84987654321">+84 987 654 321</a></li>
            <li>Địa chỉ: 123 Đường Lý Thái Tổ, Quận 10, TP. Hồ Chí Minh</li>
        </ul>
    </section>

    <!-- Phần chân trang -->
    <footer class="footer">
        <p>&copy; 2024 Thành Tâm Car Rental - Phục vụ tận tâm</p>
    </footer>

    <!-- JavaScript thêm hiệu ứng cuộn lên đầu trang -->
    <script>
        // Tạo nút cuộn lên đầu trang
        const scrollToTopButton = document.createElement("button");
        scrollToTopButton.innerText = "⬆️";
        scrollToTopButton.style.position = "fixed";
        scrollToTopButton.style.bottom = "20px";
        scrollToTopButton.style.right = "20px";
        scrollToTopButton.style.padding = "10px";
        scrollToTopButton.style.fontSize = "20px";
        scrollToTopButton.style.display = "none";
        scrollToTopButton.style.backgroundColor = "#89253e";
        scrollToTopButton.style.color = "#fff";
        scrollToTopButton.style.border = "none";
        scrollToTopButton.style.borderRadius = "5px";
        scrollToTopButton.style.cursor = "pointer";
        document.body.appendChild(scrollToTopButton);

        // Hiển thị nút khi cuộn xuống
        window.addEventListener("scroll", () => {
            if (window.pageYOffset > 200) {
                scrollToTopButton.style.display = "block";
            } else {
                scrollToTopButton.style.display = "none";
            }
        });

        // Cuộn lên đầu trang khi nhấn nút
        scrollToTopButton.addEventListener("click", () => {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
    </script>

</body>
</html>
