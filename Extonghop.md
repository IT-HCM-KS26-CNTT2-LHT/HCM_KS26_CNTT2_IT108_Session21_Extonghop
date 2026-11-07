# ĐÁP ÁN NỘP BÀI (RÚT GỌN)

## Phần 1: Googling đúng cách

- Câu hỏi văn nói kém hiệu quả vì không chứa lỗi nguyên văn và quá mơ hồ.

| Thành phần | Nội dung |
|---|---|
| Phần mềm/HĐH | Node.js, npm, Windows 11 |
| Mã lỗi | 'npm' is not recognized as an internal or external command |
| Thao tác | Gõ `npm -v` |

**Truy vấn Google:**
- `site:stackoverflow.com npm is not recognized windows`
- `"npm is not recognized as an internal or external command"`
- `npm is not recognized windows -xp`

## Phần 2: Thẩm định StackOverflow

- Chọn **Câu trả lời A**.
- Lý do: Có tích xanh, +186 vote, đúng Windows và npm.
- Câu B là bẫy vì dành cho Windows XP, ít vote, không phù hợp Windows 11.

**Quy trình đọc lướt:**
1. Xem Tags.
2. Xem Accepted Answer.
3. Xem Vote.
4. Đọc lời giải.

## Phần 3: Hỏi AI đúng cách

**Prompt 3 thành phần:**

```text
[Context] Windows 11, VS Code, vừa cài Node.js.
[Raw Error] 'npm' is not recognized as an internal or external command.
[Instruction] Đã thêm PATH nhưng vẫn lỗi, hãy giải thích và đề xuất cách kiểm tra tiếp theo.
```

- Không chạy lệnh AI đề xuất xóa file hệ thống.
- Lệnh nguy hiểm, không liên quan trực tiếp lỗi PATH.

**Hỏi lại AI:**
- Lệnh này xóa gì?
- Liên quan gì đến lỗi npm/PATH?
- Có tài liệu chính thức chứng minh không?

## Phần 4: Bug Report

**Tin nhắn kém:**

```text
Thầy ơi em bị lỗi npm.
```

**Tin nhắn chuẩn:**

```text
Context: Windows 11, VS Code, vừa cài Node.js.
Expected: npm -v hiển thị phiên bản.
Actual: 'npm' is not recognized as an internal or external command.
Log & Screenshot: Đính kèm ảnh và log lỗi.
```

- Phím tắt chụp màn hình: **Windows + Shift + S**.
- Che mật khẩu, API Key, Token trước khi gửi ảnh.
