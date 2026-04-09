<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Đăng ký</title>
    <style>
        body {
            font-family: Arial;
            background-color: #000;
        }
        .container {
            width: 500px;
            margin: 50px auto;
            background: #eee;
            padding: 20px 40px;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .row {
            display: flex;
            margin-bottom: 10px;
            align-items: center;
        }
        .row label {
            width: 150px;
        }
        .row input[type="text"],
        .row input[type="password"],
        .row input[type="email"],
        .row select,
        textarea {
            flex: 1;
            padding: 5px;
        }
        .radio, .checkbox {
            display: flex;
            gap: 10px;
            align-items: center;
        }
        textarea {
            height: 60px;
        }
        .buttons {
            text-align: center;
            margin-top: 10px;
        }
        button {
            padding: 5px 15px;
            margin: 5px;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>ĐĂNG KÝ THÔNG TIN CÁ NHÂN</h2>

    <div class="row">
        <label>Tài khoản</label>
        <input type="text">
    </div>

    <div class="row">
        <label>Mật khẩu</label>
        <input type="password">
    </div>

    <div class="row">
        <label>Nhập lại mật khẩu</label>
        <input type="password">
    </div>

    <div class="row">
        <label>Email</label>
        <input type="email">
    </div>

    <div class="row">
        <label>Họ tên</label>
        <input type="text">
    </div>

    <div class="row">
        <label>Giới tính</label>
        <div class="radio">
            <input type="radio" name="gt" checked> Nam
            <input type="radio" name="gt"> Nữ
        </div>
    </div>

    <div class="row">
        <label>Quê quán</label>
        <select>
            <option>Cần Thơ</option>
            <option>Hà Nội</option>
            <option>TP.HCM</option>
        </select>
    </div>

    <div class="row">
        <label>Sở thích</label>
        <div class="checkbox">
            <input type="checkbox" checked> Điện ảnh
            <input type="checkbox"> Âm nhạc
            <input type="checkbox"> Thể thao
        </div>
    </div>

    <div class="row">
        <label>Ghi chú cá nhân</label>
        <textarea></textarea>
    </div>

    <div class="buttons">
        <button>Lưu</button>
        <button>Nhập lại</button>
    </div>

</div>

</body>
</html>
