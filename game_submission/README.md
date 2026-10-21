# Game: Người Gác Tin Nhắn

Template game 2D cho dạng challenge vibe-coding (như Challenge 3 năm 2025). Chạy thuần HTML/CSS/JS, không cần backend.

## Chủ đề
Nâng cao cảnh giác với lừa đảo qua tin nhắn — một vấn đề xã hội Việt Nam, và khớp chủ đề an toàn thông tin của cuộc thi. Người chơi đọc từng tin nhắn và quyết định An toàn hay Lừa đảo, sau mỗi lượt có giải thích dấu hiệu.

## Cách chạy
Mở `game_app/index.html` bằng trình duyệt. Không cần cài gì.

## Màn hình
- Menu: giới thiệu + cách chơi + nút Bắt đầu.
- Play: thẻ tin nhắn, đồng hồ đếm giờ, điểm, mạng, hai nút chọn.
- Feedback: hiện ngay sau mỗi lượt, giải thích vì sao tin đó an toàn/lừa đảo.
- Game Over: điểm, tỉ lệ đúng, xếp hạng, lời khuyên, chơi lại.

## Cách tùy biến nhanh
- Thêm/sửa tin nhắn: mảng `MESSAGES` trong `index.html`. Mỗi tin cần `name`, `num`, `scam` (true/false), `text`, `why`.
- Đổi màu: các biến trong `:root` ở đầu `<style>`.
- Đổi thời gian mỗi lượt: hằng `TIME`.

## Nếu nộp theo cấu trúc như 2025
Đổi tên thư mục này thành `game_submission/` và bổ sung cho đủ: `README.md`, `project_report.pdf` (xem `project_report_outline.md`), `youtube_link.txt`, thư mục `prompts/` (đã có 4 file), `game_app/`, `screenshots/` (tối đa 5 ảnh). Lưu lại prompt vào thư mục `prompts/` ngay khi dùng, đừng để cuối giờ.

## Gợi ý ăn điểm
- Game hoàn chỉnh và chạy mượt hơn là game tham vọng mà lỗi.
- Nội dung bám vấn đề xã hội thật, có tính giáo dục rõ ràng.
- Tránh dùng nhân vật/nhạc có bản quyền. Asset tự sinh hoặc CC0.
