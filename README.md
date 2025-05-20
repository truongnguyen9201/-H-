<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Chúc mừng Đại hội Đảng bộ TCT lần thứ II</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f8fb;
            color: #333;
            padding: 40px;
        }
        h1 {
            color: #c62828;
        }
        .message {
            margin: 10px 0;
        }
        .highlight {
            font-weight: bold;
            color: #1565c0;
        }
    </style>
</head>
<body>
    <h1>Chúc mừng Đại hội Đảng bộ TCT lần thứ II!</h1>
    <div id="messages"></div>

    <script>
        const messages = [
            "Đảng bộ vững mạnh",
            "Hệ sinh thái tài chính toàn cầu",
            "Đổi mới sáng tạo"
        ];

        const container = document.getElementById("messages");

        // Hiển thị mục tiêu
        messages.forEach(goal => {
            const p = document.createElement("p");
            p.className = "message highlight";
            p.textContent = goal;
            container.appendChild(p);
        });

        // Hiển thị theo từng năm
        for (let year = 2025; year < 2030; year++) {
            const p = document.createElement("p");
            p.className = "message";
            p.textContent = `${year}: Nhanh hơn - Mạnh hơn - Hiệu quả hơn!`;
            container.appendChild(p);
        }

        // Thông điệp kết
        const finalMessages = [
            "VDS - Tiên phong, chủ lực kiến tạo xã hội số",
            "Chúc Đại hội thành công rực rỡ!"
        ];

        finalMessages.forEach(msg => {
            const p = document.createElement("p");
            p.className = "message highlight";
            p.textContent = msg;
            container.appendChild(p);
        });
    </script>
</body>
</html>
