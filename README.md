<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Portfolio | Vương Đức Đạt</title>
    <style>
        :root {
            --primary-color: #00ff88;
            --bg-color: #0a0a0a;
            --surface-color: #1a1a1a;
            --text-main: #f0f0f0;
            --text-muted: #a0a0a0;
            --font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: var(--font-family);
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
        }

        /* Container & Grid */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header Section */
        header {
            padding: 100px 0 50px;
            border-bottom: 1px solid #333;
            text-align: center;
        }

        h1 {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        .subtitle {
            font-size: 1.2rem;
            color: var(--text-muted);
            margin-bottom: 5px;
        }

        /* Section Styling */
        section {
            padding: 60px 0;
            border-bottom: 1px solid #222;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 30px;
            color: #fff;
            position: relative;
            display: inline-block;
        }

        h2::after {
            content: '';
            position: absolute;
            width: 50%;
            height: 3px;
            background: var(--primary-color);
            bottom: -10px;
            left: 0;
        }

        /* Flexbox for text areas */
        .content-flex {
            display: flex;
            gap: 40px;
            flex-wrap: wrap;
        }

        .content-box {
            flex: 1;
            min-width: 300px;
            background: var(--surface-color);
            padding: 30px;
            border-radius: 8px;
            border-left: 4px solid var(--primary-color);
            transition: transform 0.3s ease;
        }

        .content-box:hover {
            transform: translateY(-5px);
        }

        .content-box h3 {
            color: var(--primary-color);
            margin-bottom: 15px;
        }

        /* Timeline/Grid for Exercises */
        .grid-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 25px;
        }

        .card {
            background: var(--surface-color);
            padding: 25px;
            border-radius: 8px;
            border: 1px solid #333;
            transition: all 0.3s ease;
        }

        .card:hover {
            border-color: var(--primary-color);
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.1);
        }

        .card h4 {
            color: #fff;
            font-size: 1.2rem;
            margin-bottom: 10px;
        }

        .card p {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px;
            color: var(--text-muted);
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <!-- Header: Giới thiệu chung -->
    <header>
        <div class="container">
            <h1>Vương Đức Đạt</h1>
            <p class="subtitle">Khoa học Máy tính & Hệ thống Thông tin | MSSV: 25112239</p>
            <p class="subtitle">Trường Đại học Việt Nhật - Đại học Quốc gia Hà Nội</p>
        </div>
    </header>

    <!-- Section 1: Giới thiệu & Mục tiêu -->
    <section id="introduction">
        <div class="container">
            <h2>Tổng quan & Định hướng</h2>
            <br><br>
            <div class="content-flex">
                <div class="content-box">
                    <h3>Giới thiệu bản thân</h3>
                    <p>Đam mê sâu sắc với dữ liệu lớn và các hệ thống tự động hóa thông minh. Định hướng trở thành Kỹ sư Học máy (Machine Learning Engineer) để kiến tạo các giải pháp AI đột phá. Luôn đề cao tư duy tối ưu hóa quy trình và quản trị dữ liệu khoa học.</p>
                </div>
                <div class="content-box">
                    <h3>Mục tiêu học tập</h3>
                    <p><strong>Ngắn hạn:</strong> Làm chủ kỹ năng nền tảng số, tổ chức dữ liệu, và khai thác công cụ AI cho nghiên cứu học thuật.<br><br>
                    <strong>Dài hạn:</strong> Xây dựng tư duy phản biện công nghệ, thành thạo mô hình làm việc nhóm chuẩn Agile/Scrum, và định hình phong cách làm việc chuyên nghiệp quốc tế.</p>
                </div>
                <div class="content-box">
                    <h3>Mục tiêu Portfolio</h3>
                    <p>Hơn cả một kho lưu trữ bài tập, đây là <strong>Không gian tri thức cá nhân (Personal Knowledge Management)</strong> và <strong>Lý lịch năng lực số (Digital Resume)</strong>. Thiết kế tập trung vào trải nghiệm người dùng (UX/UI) nhằm khẳng định tư duy kiến trúc thông tin vượt trội.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Section 2: Hệ thống hóa bài tập -->
    <section id="portfolio">
        <div class="container">
            <h2>Hệ thống hóa Kết quả Bài tập Thành phần</h2>
            <p style="color: var(--text-muted); margin-bottom: 40px; margin-top: 10px;">Biên tập và trình bày lại sản phẩm cuối cùng từ Bài 1 đến Bài 6 để làm nổi bật quy trình thực hiện các kỹ năng số cốt lõi.</p>
            
            <div class="grid-cards">
                <!-- Bài 1 -->
                <div class="card">
                    <h4>Bài 1 (Mục 1.4): Thao tác cơ bản với tệp tin và thư mục</h4>
                    <p>Trình bày cấu trúc cây thư mục lưu trữ tối ưu theo nguyên lý khoa học và quy tắc đặt tên tệp (naming convention) đã thiết lập, kèm ảnh chụp minh họa thực tế.</p>
                </div>

                <!-- Bài 2 -->
                <div class="card">
                    <h4>Bài 2 (Mục 2.4): Tìm kiếm và đánh giá thông tin học thuật</h4>
                    <p>Trình bày kết quả nghiên cứu học thuật bằng cách kết hợp các toán tử tìm kiếm nâng cao (site, filetype, intitle...) và bảng đánh giá độ tin cậy của nguồn tin đã thực hiện.</p>
                </div>

                <!-- Bài 3 -->
                <div class="card">
                    <h4>Bài 3 (Mục 3.4): Viết Prompt hiệu quả cho học tập</h4>
                    <p>Trình bày ma trận so sánh chi tiết giữa Prompt ban đầu (Naïve) và Prompt cải tiến (Expert Prompt Engineering) cùng sự khác biệt trong kết quả đầu ra từ AI.</p>
                </div>

                <!-- Bài 4 -->
                <div class="card">
                    <h4>Bài 4 (Mục 4.4): Sử dụng công cụ hợp tác trực tuyến</h4>
                    <p>Trình bày minh chứng rõ nét về việc ứng dụng công cụ quản lý dự án nhóm (Notion, Trello) và cách thức thiết lập luồng phối hợp trực tuyến hiệu quả.</p>
                </div>

                <!-- Bài 5 -->
                <div class="card">
                    <h4>Bài 5 (Mục 5.4): Trí tuệ nhân tạo tạo sinh (Generative AI)</h4>
                    <p>Trưng bày các sản phẩm nội dung số hoàn thiện, bao gồm hình ảnh nghệ thuật, bài viết chuyên sâu hoặc video đã được hỗ trợ sáng tạo toàn diện bởi hệ sinh thái AI.</p>
                </div>

                <!-- Bài 6 -->
                <div class="card">
                    <h4>Bài 6 (Mục 6.4): Sử dụng AI có trách nhiệm</h4>
                    <p>Trình bày bộ nguyên tắc đạo đức cá nhân nghiêm ngặt về việc sử dụng AI dựa trên các nghiên cứu về liêm chính học thuật và trách nhiệm công nghệ đã thực hiện.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2026 Vương Đức Đạt. Bản quyền thuộc về tác giả.</p>
            <p>Môn học: Nhập môn Công nghệ số và Ứng dụng Trí tuệ Nhân tạo</p>
        </div>
    </footer>

</body>
</html>
