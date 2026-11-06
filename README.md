# -CNTT2-_-NhapMonCNTT-_Session_Ex04
## 1. Vấn đề
Khi sử dụng Git, xuất hiện lỗi `fatal: not a git repository (or any of the parent directories): .git`. Người dùng chưa hiểu ý nghĩa và cách khắc phục lỗi.

## 2. Yêu cầu
Sử dụng mô hình IPO để thiết kế một câu lệnh gửi cho ChatGPT/Gemini sao cho kết quả trả về là hướng dẫn sửa lỗi từng bước bằng tiếng Việt.

## 3. Cách làm

- **Input:** Ngữ cảnh sử dụng Git và mã lỗi nguyên văn.
- **Process:** AI phân tích lỗi, tìm nguyên nhân và đề xuất cách khắc phục.
- **Output:** Bản dịch tiếng Việt và 3 bước sửa lỗi:
  1. Kiểm tra thư mục hiện tại bằng `pwd`.
  2. Dùng `cd` để vào đúng thư mục dự án.
  3. Chạy `git status` để kiểm tra lại.

**Prompt hoàn chỉnh:**

Bạn là chuyên gia Git. Tôi đang sử dụng Git và gặp lỗi `fatal: not a git repository (or any of the parent directories): .git`. Hãy dịch lỗi sang tiếng Việt, giải thích nguyên nhân và hướng dẫn tôi 3 bước sửa lỗi cụ thể, dễ hiểu dành cho người mới học Git.
