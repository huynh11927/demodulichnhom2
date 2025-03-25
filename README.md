<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Du Lịch cùng CBT</title>
  <style>
    /* Định dạng nền với hiệu ứng chuyển màu */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #74ABE2, #5563DE);
      animation: bgAnimation 10s infinite alternate;
    }
    @keyframes bgAnimation {
      from { filter: brightness(1); }
      to { filter: brightness(1.1); }
    }

    /* Định dạng khung chứa form */
    .container {
      width: 400px;
      margin: 50px auto;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
      overflow: hidden;
    }

    /* Đầu trang */
    .header {
      background: #5563DE;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 24px;
      letter-spacing: 1px;
    }

    /* Phần thân chứa form */
    .form-container {
      padding: 20px;
    }
    .form-container input,
    .form-container select {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ddd;
      border-radius: 5px;
      transition: border-color 0.3s;
    }
    .form-container input:focus,
    .form-container select:focus {
      border-color: #5563DE;
      outline: none;
    }

    /* Nút đăng nhập */
    .btn {
      width: 100%;
      padding: 10px;
      background: #5563DE;
      border: none;
      color: #fff;
      font-size: 18px;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #3c45a3;
    }

    /* Phần chân trang thông tin bổ sung */
    .footer {
      padding: 20px;
      background: #f9f9f9;
      font-size: 14px;
      line-height: 1.6;
      color: #333;
    }
    .footer p {
      margin: 10px 0;
    }
    .footer a {
      color: #5563DE;
      text-decoration: none;
    }
    .footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      Du Lịch cùng CBT
    </div>
    <div class="form-container">
      <form action="#" method="post">
        <input type="text" name="hoten" placeholder="Họ tên" required>
        <input type="text" name="diachi" placeholder="Địa chỉ nhà" required>
        <input type="tel" name="sdt" placeholder="Số điện thoại" required>
        <input type="email" name="email" placeholder="Địa chỉ Email" required>
        <input type="number" name="soluong" placeholder="Số lượng người tham gia" required min="1">
        <input type="text" name="diemden" placeholder="Chỗ bạn muốn đến" required>
        <select name="phuongtien" required>
          <option value="">Chọn phương tiện đi chuyển</option>
          <option value="maybay">Máy bay</option>
<option value="oto">Ô tô</option>
          <option value="tauhoa">Tàu hỏa</option>
          <option value="xechuyen">Xe khách</option>
        </select>
        <select name="thanhtoan" required>
          <option value="">Chọn phương thức thanh toán</option>
          <option value="tienmat">Tiền mặt</option>
          <option value="visa">Visa/MasterCard</option>
          <option value="chuyenkhoan">Chuyển khoản</option>
          <option value="paypal">PayPal</option>
        </select>
        <button type="submit" class="btn">Đăng nhập</button>
      </form>
    </div>
    <div class="footer">
      <p>Chân thành cảm ơn quý khách đã tin tưởng, lựa chọn dịch vụ của chúng tôi. Chúc quý khách có một chuyến du lịch thật tuyệt vời.</p>
      <p>Thông tin đăng ký sẽ gửi đến mail của bạn sau khi được lập hồ sơ.</p>
      <p>Mọi thắc mắc xin vui lòng liên hệ:<br>
         Sđt: 0853534500<br>
         Email: phamtruchuynh11927@gmail.com<br>
         Facebook: <a href="https://www.facebook.com/share/1QQto817UR/" target="_blank">Phạm Trúc Huỳnh</a>
      </p>
    </div>
  </div>
</body>
</html>
