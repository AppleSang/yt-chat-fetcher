<div align="center">
  <img width="280" height="160" alt="Logo YouTube Chat Fetcher" src="https://github.com/user-attachments/assets/15444b70-0bea-4452-b90a-ec972d8a8ddc" align="right" />
  <h1>YouTube Chat Fetcher</h1>
  <p>Thiết lập nhanh · Dễ sử dụng · Ổn định</p>
</div>

<p align="center">
  <a href="readme.md">Read in English</a>
</p>

## Tính năng

- Tự động tải khung chat của buổi phát trực tiếp.
- Tự thử lại đến khi tìm thấy khung chat.
- Hỗ trợ CSS tùy chỉnh để bạn thiết kế giao diện chat theo ý muốn.

## Video hướng dẫn

[![Xem video hướng dẫn thiết lập](https://github.com/user-attachments/assets/15444b70-0bea-4452-b90a-ec972d8a8ddc)](https://www.youtube.com/watch?v=-6NTKx266-Q)

## Cài đặt

1. Mở đường dẫn của công cụ: [https://applesang.github.io/yt-chat-fetcher/?id=](https://applesang.github.io/yt-chat-fetcher/?id=). Bạn sẽ thêm handle kênh YouTube vào sau `?id=` ở bước dưới.
2. Mở [YouTube](https://www.youtube.com/) rồi nhấn vào ảnh đại diện của bạn.

   <img src="https://github.com/user-attachments/assets/70c84828-ea46-497e-875f-25c6dfe558aa" alt="Menu ảnh đại diện trên YouTube" width="732" height="167" />

3. Chọn **View your channel** (Xem kênh của bạn).

   <img src="https://github.com/user-attachments/assets/be5cdc27-8518-4dc6-8b3a-e77ed46d39c0" alt="Tùy chọn View your channel" width="238" height="604" />

4. Trên URL kênh, sao chép handle kênh, bao gồm cả ký tự `@`. Ví dụ, từ `youtube.com/@yourchannel`, hãy sao chép `@yourchannel`.

   <img src="https://github.com/user-attachments/assets/08ebe67b-bbe3-4ef2-a988-d0183d9df67c" alt="Handle kênh trong URL YouTube" width="331" height="44" />

5. Dán handle đó vào sau `?id=` trong đường dẫn công cụ. Ví dụ: `https://applesang.github.io/yt-chat-fetcher/?id=@yourchannel`.

   <img src="https://github.com/user-attachments/assets/e41a67c8-2d0b-42ee-a924-c176a96d0a6c" alt="Đường dẫn công cụ kèm handle kênh" width="427" height="46" />

6. Sao chép toàn bộ đường dẫn và thêm vào OBS dưới dạng **Browser Source**.
7. Không bắt buộc: thêm đường dẫn này vào OBS dưới dạng **Custom Browser Dock** để truy cập nhanh.

> [!TIP]
> Bạn có thể thêm [CSS](https://chatv2.septapus.com/) tùy chỉnh trong OBS để giao diện chat gọn gàng hơn.

## Câu hỏi thường gặp

<details>
  <summary>Tại sao video hướng dẫn có <code>@</code>, còn hướng dẫn chữ cũ thì không?</summary>

Công cụ chấp nhận handle kênh có hoặc không có ký tự `@`. Bạn cũng có thể dùng [Channel ID](https://www.youtube.com/account_advanced) của YouTube.

</details>

## Hỗ trợ

Hãy tạo [issue](https://github.com/AppleSang/yt-chat-fetcher/issues) để báo lỗi hoặc đề xuất tính năng mới.
